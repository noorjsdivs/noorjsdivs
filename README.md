# Noor Mohammad

![Profile Views](https://komarev.com/ghpvc/?username=noor-mohammad-2&label=Profile%20views&color=0e75b6&style=flat)

<div align="center">
  <pre class="ascii-art">
 _   _                 __  __       _                                   _ 
| \ | | ___   ___  _ _|  \/  | ___ | |__   __ _ _ __ ___  _ __ ___   __ _ __| |
|  \| |/ _ \ / _ \| '__| |\/| |/ _ \| '_ \ / _` | '_ ` _ \| '_ ` _ \ / _` / _` |
| |\  | (_) | (_) | |  | |  | | (_) | | | | (_| | | | | | | | | | | | (_| \__,_|
|_| \_|\___/ \___/|_|  |_|  |_|\___/|_| |_|\__,_|_| |_| |_|_| |_| |_|\__,_\__,_|
  </pre>

  <h2>
    <code>console.log('Software Engineer | MERN Enthusiast 🚀')</code>
  </h2>
</div>

---

## 🌐 About Me

Hi! I'm Noor Mohammad, a passionate **Full-Stack Developer** specializing in modern web development technologies. My expertise lies in building dynamic, responsive, and scalable applications. I have a keen interest in the **MERN stack**, **React**, and **Next.js**, and I'm always eager to explore new tools and technologies.

### Portfolio
🔗 [Check out my portfolio](https://noormohammad.reactbd.com/)

### Blog
📘 [Visit my blog](https://blog.reactbd.com/) for in-depth articles and tutorials on web development.

---

## 🚀 Skills & Expertise

### Development
- 💻 Full-Stack Development
- 🌐 MERN Stack (MongoDB, Express.js, React.js, Node.js)
- ⚛️ React.js & Next.js
- 🎨 Tailwind CSS & Styled Components

### Other Areas
- 🔒 Cyber Security
- ⛓️ Blockchain (Learning)
- 🛠️ REST & GraphQL APIs
- 📦 State Management (Redux, Zustand)

---

### [Get my projects from the shop](https://buymeacoffee.com/reactbd/extras)
- **Tech Stack:** Next.js, Tailwind CSS, Stripe, Motion and lot others more

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

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=noor-mohammad-2&show_icons=true&theme=radical" alt="Noor Mohammad's GitHub stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=noor-mohammad-2&theme=radical" alt="Noor Mohammad's GitHub streak" />
</div>

---

## 📬 Let's Connect

<div align="center">
  <a href="https://linkedin.com/in/noor-mohammad-ab2245216" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://twitter.com/noormohammad_me" target="_blank"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" /></a>
  <a href="https://github.com/noor-mohammad-2" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="mailto:noor.jsdivs@gmail.com"><img src="https://img.shields.io/badge/📧_Email-D14836?style=for-the-badge&logoColor=white" alt="Email" /></a>
</div>
