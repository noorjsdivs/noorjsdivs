# Noor Mohammad

![Profile Views](https://komarev.com/ghpvc/?username=noor-mohammad-2&label=Profile%20views&color=0e75b6&style=flat)

<div align="center" style="font-family: 'Courier New', Courier, monospace; color: #0e75b6; background: #f5f7fa; padding: 20px; border-radius: 10px; border: 1px solid #ddd;">
  <pre style="font-size: 14px; line-height: 1.4em; color: #0d6efd;">
<span style="color: #dc3545;"> _   _                 __  __       _                                   _ </span>
<span style="color: #28a745;">| \ | | ___   ___  _ _|  \/  | ___ | |__   __ _ _ __ ___  _ __ ___   __ _ __| |</span>
<span style="color: #fd7e14;">|  \| |/ _ \ / _ \| '__| |\/| |/ _ \| '_ \ / _` | '_ ` _ \| '_ ` _ \ / _` / _` |</span>
<span style="color: #20c997;">| |\  | (_) | (_) | |  | |  | | (_) | | | | (_| | | | | | | | | | | | (_| \__,_|</span>
<span style="color: #6f42c1;">|_| \_|\___/ \___/|_|  |_|  |_|\___/|_| |_|\__,_|_| |_| |_|_| |_| |_|\__,_\__,_|</span>
  </pre>

  <h2 style="margin-top: 20px;">
    <code style="color: #212529; font-size: 18px;">console.log('Software Engineer | MERN Enthusiast 🚀')</code>
  </h2>
</div>

---

## 🌐 About Me

Hi! I'm Noor Mohammad, a passionate **Software Engineer** specializing in modern web development technologies. My expertise lies in building dynamic, responsive, and scalable applications. I have a keen interest in the **MERN stack**, **React**, **React Native** and **Next.js**, and I'm always eager to explore new tools and technologies.

### Portfolio
🔗 [Check out my portfolio](https://noormohammad.reactbd.com/)

### Blog
📘 [Visit my blog](https://blog.reactbd.com/) for in-depth articles and tutorials on web development.

---

## 🚀 Skills & Expertise

### 💻 Development
- Full-Stack Development  
- MERN Stack: MongoDB, Express.js, React.js, Node.js  
- React Native for Mobile Apps  
- React.js & Next.js for SPAs and SSR  
- Tailwind CSS & Styled Components  

### 🔧 Other Skills
- Cyber Security  
- Blockchain (Currently Learning)  
- REST & GraphQL APIs  
- State Management: Redux, Zustand 

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

## 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=noorjsdivs&theme=algolia&hide_border=false&include_all_commits=false&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=noorjsdivs&theme=algolia&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=noorjsdivs&theme=algolia&hide_border=false&include_all_commits=false&count_private=true&layout=compact)

 ## 💰 You can support me by Donating
  [![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/reactbd) [![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/reactbd) 

---

## 📬 Let's Connect

<div>
  <a href="https://github.com/noorjsdivs/noorjsdivs/blob/main/README.md" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
  <a href="https://www.linkedin.com/in/noor-mohammad-ab2245193/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://www.facebook.com/Noorlalu143/" target="_blank"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" /></a>
    <a href="mailto:noor.jsdivs@gmail.com"><img src="https://img.shields.io/badge/📧_Email-D14836?style=for-the-badge&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>

</div>
