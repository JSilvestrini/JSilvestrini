<!--
**JSilvestrini/JSilvestrini** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<div align="center">
  <img src="https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/assets/74038190/9be4d344-6782-461a-b5a6-32a07bf7b34e" title="Hello" alt="Hello" width="1024" height="512"/>
</div>
<div align="center">
  <img src="https://komarev.com/ghpvc/?username=JSilvestrini&style=flat-square&color=blue" alt=""/>
  <!-- Place LinkedIn, Email?, Portfolio, etc. Here -->
</div>

---

<h2 align="center">About Me:</h2>

- Developer of [PyMym](https://pypi.org/project/PyMym/), a Windows Python memory manipulation library with support for Python 3.10+
- I'm currently developing a gymnasium environment for Elden Ring and an API wrapper for Pokémon Emerald
- Currently reading Refactoring 2e by Fowler and Beck, along with Design Patterns by the Gang of Four
  <!-- - 📫 How to reach me: Linked in, etc. -->

---

<h2 align="center">Languages and Tools:</h2>

<div align="center">
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-plain-wordmark.svg"  title="Python" alt="Python" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/cplusplus/cplusplus-plain.svg"  title="Cpp" alt="Cpp" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/opengl/opengl-plain.svg"  title="OpenGL" alt="OpenGL" width="40" height="40"/>&nbsp;
  <!-- Add in Godot/GDScript, check others-->
  <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL"  alt="MySQL" width="40" height="40"/>&nbsp;
</div>

---

<h2 align="center">Current Projects</h2>

### PyMym

PyMym is a Python memory manipulation library made using pybind11 and the Windows APIs to quickly access, search, and manipulate memory of different running processes. It was original just ugly tacked on code to my Elden Ring gym project, but after taking a break from the project, I decided to isolate the code and create a library others could use. Currently I am working on other projects, but plan on expanding PyMym into a multiplatform library, with support for Mac coming next (which will give me an excuse to play around with my Mac Book Pro on a large project).

### Elden Ring Gym

This was one of my previous projects that I have recently came back to. It was inspired by a post I saw on Reddit where a user was able to create a gym environment for Dark Souls 3, by using a ground truth model of the game, in which the model was able to get about a 45% win rate against the tutorial boss. The main idea for the project was to use memory manipulation to collect information for the reward function, while using image captures stacked upon each other to create something similar to what a player would see when playing. Before the current refactor/ re-write, I was able to get the model successfully running and training, with the current goal being to resume the training but with higher quality code and (hopefully) a more stable program.

My main goal for the project is to get a higher win rate than 45% against at least one of the many bosses in Elden Ring, create a semi-generalized model, and check the performance of Stable Baselines 3's CNN-LSTM model using a PPO policy compared to the original Duelling Deep Q-Learning.

### AI Plays Pokémon

This project also uses PyMym for memory reading, but instead of using reinforcement learning, API calls to LLMs were going to be used, where the LLM could query game state information and perform actions in game that align with a user instruction. For example: "Catch a shiny Zigzagoon" or "Train my Torchic to level 16" would result in the LLM being able to query relevant information from the game and perform actions until it has accomplished its goal. This was inspired by a video about reinforcement learning in Pokémon Red as well a video series following LLMs attempting to play Minecraft with one another.

</div>

---

<h2 align="center">My Stats:</h2>
<div align="center">
  <img src="http://github-readme-streak-stats.herokuapp.com?user=JSilvestrini&theme=dark&background=000000" alt="Top Langs">
</div>
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JSilvestrini&layout=compact&theme=vision-friendly-dark" alt="Top Langs">
</div>
