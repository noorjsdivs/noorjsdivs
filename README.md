<div align="center">
  <pre class="ascii-art">
 _   _                 __  __       _                                   _ 
| \ | | ___   ___  _ _|  \/  | ___ | |__   __ _ _ __ ___  _ __ ___   __ _ __| |
|  \| |/ _ \ / _ \| '__| |\/| |/ _ \| '_ \ / _` | '_ ` _ \| '_ ` _ \ / _` / _` |
| |\  | (_) | (_) | |  | |  | | (_) | | | | (_| | | | | | | | | | | | (_| \__,_|
|_| \_|\___/ \___/|_|  |_|  |_|\___/|_| |_|\__,_|_| |_| |_|_| |_| |_|\__,_\__,_|
  </pre>

  <h2>
    <code>console.log('Full-Stack Developer | MERN Enthusiast 🚀')</code>
  </h2>

  <p>
    <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
    <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
    <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
    <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
    <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  </p>

  <p>
    <a href="https://noormohammad.reactbd.com/" target="_blank"><img src="https://img.shields.io/badge/🚀_Portfolio-FF5722?style=for-the-badge&logoColor=white" alt="Portfolio" /></a>
    <a href="https://blog.reactbd.com/" target="_blank"><img src="https://img.shields.io/badge/💻_Blog-0A0A0A?style=for-the-badge&logoColor=white" alt="Blog" /></a>
    <a href="mailto:noor.jsdivs@gmail.com"><img src="https://img.shields.io/badge/📧_Email-D14836?style=for-the-badge&logoColor=white" alt="Email" /></a>
  </p>
</div>

<div class="container">
  <h2 align="center"><code>$ cat mern_stack_example.js</code></h2>

  <pre class="code-content">
// Backend: Express server (server.js)
const express = require('express');
const mongoose = require('mongoose');
const cors = require('cors');

const app = express();
app.use(cors());
app.use(express.json());

mongoose.connect('mongodb://localhost/myapp', { useNewUrlParser: true, useUnifiedTopology: true });

const TaskSchema = new mongoose.Schema({
  title: String,
  completed: Boolean
});

const Task = mongoose.model('Task', TaskSchema);

app.get('/api/tasks', async (req, res) => {
  const tasks = await Task.find();
  res.json(tasks);
});

app.post('/api/tasks', async (req, res) => {
  const task = new Task(req.body);
  await task.save();
  res.status(201).json(task);
});

app.listen(5000, () => console.log('Server running on port 5000'));

// Frontend: React component (TaskList.js)
import React, { useState, useEffect } from 'react';
import axios from 'axios';

const TaskList = () => {
  const [tasks, setTasks] = useState([]);
  const [newTask, setNewTask] = useState('');

  useEffect(() => {
    fetchTasks();
  }, []);

  const fetchTasks = async () => {
    const res = await axios.get('http://localhost:5000/api/tasks');
    setTasks(res.data);
  };

  const addTask = async (e) => {
    e.preventDefault();
    await axios.post('http://localhost:5000/api/tasks', { title: newTask, completed: false });
    setNewTask('');
    fetchTasks();
  };

  return (
    &lt;div&gt;
      &lt;h1&gt;Task List&lt;/h1&gt;
      &lt;form onSubmit={addTask}&gt;
        &lt;input
          type="text"
          value={newTask}
          onChange={(e) => setNewTask(e.target.value)}
          placeholder="New task"
        /&gt;
        &lt;button type="submit"&gt;Add Task&lt;/button&gt;
      &lt;/form&gt;
      &lt;ul&gt;
        {tasks.map((task) => (
          &lt;li key={task._id}&gt;{task.title}&lt;/li&gt;
        ))}
      &lt;/ul&gt;
    &lt;/div&gt;
  );
};

export default TaskList;
  </pre>

  <h2 align="center"><code>$ ls ./skills</code></h2>

  <div class="skill-grid">
    <div class="skill-item">💻 Full-Stack Development</div>
    <div class="skill-item">🌐 MERN Stack</div>
    <div class="skill-item">⚛️ React &amp; Next.js</div>
    <div class="skill-item">🎨 Tailwind CSS</div>
    <div class="skill-item">🔒 Cyber Security</div>
    <div class="skill-item">⛓️ Blockchain (Learning)</div>
  </div>

  <h2 align="center"><code>$ git stats</code></h2>

  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=noor-mohammad-2&show_icons=true&theme=radical" alt="Noor Mohammad's GitHub stats" />
  </p>

  <p align="center">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=noor-mohammad-2&theme=radical" alt="Noor Mohammad's GitHub streak" />
  </p>

  <h2 align="center"><code>$ echo "Let's connect!"</code></h2>

  <p align="center">
    <a href="https://linkedin.com/in/noor-mohammad-ab2245216" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://twitter.com/noormohammad_me" target="_blank"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" /></a>
    <a href="https://github.com/noor-mohammad-2" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  </p>

  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=noor-mohammad-2&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
  </p>
</div>

<style>
  .ascii-art {
    font-family: 'Courier New', Courier, monospace;
    white-space: pre;
    display: inline-block;
    font-size: 10px;
    line-height: 1;
    background: linear-gradient(45deg, #ff00ff, #00ffff);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: gradient 5s ease-in-out infinite;
    background-size: 300% 300%;
  }

  @keyframes gradient {
    0% {
      background-position: 0% 50%;
    }
    50% {
      background-position: 100% 50%;
    }
    100% {
      background-position: 0% 50%;
    }
  }

  .container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background-color: #1e1e1e;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    color: #d4d4d4;
  }

  .code-content {
    background-color: #2d2d2d;
    color: #d4d4d4;
    padding: 20px;
    border-radius: 5px;
    font-family: 'Fira Code', monospace;
    font-size: 14px;
    line-height: 1.5;
    overflow-x: auto;
  }

  .skill-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 15px;
    margin-top: 20px;
  }

  .skill-item {
    background-color: #2d2d2d;
    padding: 15px;
    border-radius: 5px;
    text-align: center;
    font-weight: bold;
    transition: transform 0.2s ease-in-out;
  }

  .skill-item:hover {
    transform: translateY(-5px);
  }

  h2 {
    margin-top: 40px;
    margin-bottom: 20px;
    color: #61dafb;
  }

  img {
    max-width: 100%;
    height: auto;
  }
</style>

