## Hi there 👋

<!--
**yukhyShell5/yukhyShell5** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

<head>
  <meta charset="UTF-8">
  <title>Mini-Jeu CSS</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: #222;
      margin: 0;
      color: white;
      font-family: sans-serif;
    }
    .zone {
      width: 150px;
      height: 150px;
      background: red;
      animation: change 1s infinite;
      animation-play-state: paused;
      cursor: pointer;
    }
    .zone:active {
      animation-play-state: running;
    }
    @keyframes change {
      0%   { background: red; }
      25%  { background: blue; }
      50%  { background: green; }
      75%  { background: yellow; }
      100% { background: red; }
    }
  </style>
</head>
<body>
  <div class="zone"></div>
</body>
