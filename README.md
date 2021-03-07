<style>
.grid-container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  gap: 0px 0px;
  grid-template-areas:
    "one two three four"
    "five six seven eight";
}
.two { grid-area: two; }
.one { grid-area: one; }
.three { grid-area: three; }
.four { grid-area: four; }
.five { grid-area: five; }
.six { grid-area: six; }
.seven { grid-area: seven; }
.eight { grid-area: eight; }

.grid {
  display: grid;
  grid-template-rows: repeat(6, 1fr);
  grid-template-columns: repeat(12, 1fr);
  grid-gap: 10px;
}
.box {
  color: transparent;
  font-size: 4vw;
  padding: 10px;
  background: transparent;
  text-align: center;
}
.box:nth-child(1) {
  grid-column: span 12;
  }
.box:nth-child(2), 
.box:nth-child(3) {
  grid-column: span 6;
  }
.box:nth-child(4),
.box:nth-child(5),
.box:nth-child(6) {
  grid-column: span 4;
  }
.box:nth-child(7),
.box:nth-child(8),
.box:nth-child(9),
.box:nth-child(10) {
  grid-column: span 3;
  }
.box:nth-child(11),
.box:nth-child(12),
.box:nth-child(13),
.box:nth-child(14),
.box:nth-child(15),
.box:nth-child(16) {
  grid-column: span 2;
  }
@media screen and (max-width: 575px) {
    .grid {
      display: block;
      }
    .box {
      margin: 10px 0;
    }
  }
</style>

<p align="center">
  <img src="./assets/me.png">
</p>

<main class="grid">
  <div class="box">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
"></div>
  <div class="box"><img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
"></div>
  <div class="box"><img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=material-ui&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white"></div>
  <div class="box"><img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"></div>
  <div class="box"><img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white"></div>
  <div class="box"><img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"></div>
  <div class="box"><img src="https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white"></div>
  <div class="box"><img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white"></div>
  <div class="box"><img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white"></div>
  <div class="box"><img src="https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/strapi-2e7eea?style=for-the-badge&logo=strapi&logoColor=white
"></div>
  <div class="box"><img src="https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=white
"></div>
</main>

- 🔭 I’m currently working on DR
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
***

<div class="grid-container">
  <div class="two"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white
"></div>
  <div class="one"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white
" /></div>
  <div class="three"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"></div>
  <div class="four"><img src="https://img.shields.io/badge/Messenger-00B2FF?style=for-the-badge&logo=messenger&logoColor=white"></div>
  <div class="five"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"></div>
  <div class="six"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white
"></div>
  <div class="seven"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white
"></div>
  <div class="eight"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white
"></div>
</div>
