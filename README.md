<div align="center">
  <pre style="font-family: 'Courier New', monospace; font-size: 10px; line-height: 1;">
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

---

### Code Snippets

```javascript
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
```

---

### Skills Table

| 💻 Full-Stack Development | 🌐 MERN Stack           | ⚛️ React & Next.js     |
|---------------------------|-------------------------|------------------------|
| 🎨 Tailwind CSS           | 🔒 Cyber Security       | ⛓️ Blockchain (Learning) |

### Skills List

- 💻 Full-Stack Development
- 🌐 MERN Stack
- ⚛️ React & Next.js
- 🎨 Tailwind CSS
- 🔒 Cyber Security
- ⛓️ Blockchain (Learning)

---

### GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=noor-mohammad-2&show_icons=true&theme=radical" alt="GitHub stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=noor-mohammad-2&theme=radical" alt="GitHub streak" />
</p>
