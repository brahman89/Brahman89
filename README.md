# 👋 Привет, я hate_urban!

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Interactive](https://img.shields.io/badge/INTERACTIVE-README-blue?style=for-the-badge)

<div align="center">

## 🎮 Интерактивные элементы

<!-- Этот iframe загружает интерактивную страницу -->
<iframe 
  src="https://brahman89.github.io/interactive-readme/" 
  width="100%" 
  height="500" 
  style="border:2px solid #ff6b6b; border-radius:10px;"
  title="Интерактивная панель"
  scrolling="no"
>
</iframe>

*👆 Нажмите на элементы выше для взаимодействия!*

</div>

## 📊 GitHub Статистика

<div align="center" id="stats-container">
<!-- Контейнер для динамической статистики -->

### 🏆 Трофеи
![GitHub Trophies](https://github-profile-trophy.vercel.app/?username=brahman89&theme=radical&no-frame=true&column=7&margin-w=15&margin-h=15)

### 📈 Активность
<div class="stats-buttons">
  <button onclick="showStats('weekly')" style="background:#ff6b6b;color:white;border:none;padding:5px 10px;border-radius:5px;">Неделя</button>
  <button onclick="showStats('monthly')" style="background:#4ecdc4;color:white;border:none;padding:5px 10px;border-radius:5px;">Месяц</button>
  <button onclick="showStats('all')" style="background:#45b7d1;color:white;border:none;padding:5px 10px;border-radius:5px;">Всё время</button>
</div>

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=brahman89&count_private=true&show_icons=true&theme=radical&hide_border=true&bg_color=00000000&include_all_commits=true)

### 💻 Используемые языки
<details>
<summary><b>🎯 Показать/скрыть языки программирования</b></summary>

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=brahman89&langs_count=8&layout=compact&theme=radical&hide_border=true&bg_color=00000000&hide=php,batchfile,gherkin,freemarker,xslt,tsql,ruby)

</details>

</div>

---

## 🎬 Overlord Fan
<div align="center" id="overlord-section">
  
![Overlord Animation](https://github.com/brahman89/Brahman89/blob/main/overlord-red-eyes.gif)

*"Слава Аинз Оал Гоуну"*

<div>
  <button onclick="changeTheme('dark')" style="background:#222;color:#ff6b6b;border:none;padding:8px 15px;margin:5px;border-radius:5px;">🌙 Тёмная</button>
  <button onclick="changeTheme('radical')" style="background:#ff6b6b;color:white;border:none;padding:8px 15px;margin:5px;border-radius:5px;">❤️ Radical</button>
  <button onclick="changeTheme('light')" style="background:#fff;color:#333;border:1px solid #ccc;padding:8px 15px;margin:5px;border-radius:5px;">☀️ Светлая</button>
</div>

</div>

---

## 📫 Связь со мной

- **GitHub:** [brahman89](https://github.com/brahman89)
- **Проекты:** Исследуйте мои репозитории чтобы увидеть мои работы

<div id="message-form" style="background:#f5f5f5;padding:15px;border-radius:10px;margin:20px 0;">
  <h3>💌 Оставить сообщение</h3>
  <form onsubmit="event.preventDefault(); submitMessage();">
    <input type="text" id="visitor-name" placeholder="Ваше имя" style="width:100%;padding:8px;margin:5px 0;border:1px solid #ddd;border-radius:5px;">
    <textarea id="visitor-message" placeholder="Ваше сообщение..." style="width:100%;padding:8px;margin:5px 0;border:1px solid #ddd;border-radius:5px;height:80px;"></textarea>
    <button type="submit" style="background:#4ecdc4;color:white;border:none;padding:10px 20px;border-radius:5px;cursor:pointer;">Отправить ✨</button>
  </form>
  <div id="message-response" style="margin-top:10px;"></div>
</div>

---

<div align="center">
  
### ⚡ Факт обо мне
<div id="random-fact" style="background:linear-gradient(45deg, #ff6b6b, #4ecdc4);color:white;padding:15px;border-radius:10px;margin:10px;cursor:pointer;" onclick="showRandomFact()">
  <span style="font-size:1.2em;">🎲 Нажми для случайного факта!</span>
</div>


def about_me():
    interests = ["Python", "Аниме", "Разработка", "Overlord"]
    current_project = "Работаю над интересными проектами"
    return f"{interests} | {current_project}"
