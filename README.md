<div align="center">
  
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Space+Grotesk&weight=800&size=40&pause=1000&color=FF4500&center=true&vCenter=true&width=800&lines=UI+CAPTURE;BRUTALIST+SCREEN+GRABBER;PIXEL-PERFECT+SELECTION" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="600">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/VERSION-13.0.0-FF4500?style=for-the-badge&logo=googlechrome&logoColor=white" />
  <img src="https://img.shields.io/badge/MANIFEST-V3-111111?style=for-the-badge" />
  <img src="https://img.shields.io/badge/STATUS-ACTIVE-00FF00?style=for-the-badge" />
</p>

> *Чистый, удобный и невероятно мощный инструмент для захвата UI-элементов, блоков и длинных страниц.*

</div>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/fire.gif" width="100%">
</p>

## ⚡ ВОЗМОЖНОСТИ [FEATURES]

### 🎯 Умный скриншот элемента `[ALT+1]`
Автоматически определяет настоящий визуальный или кликабельный элемент, подсвечивает его с помощью кастомных кибер-рамок (CRT Scanline, Cyber Glitch, Hacker Terminal) и сохраняет чистый PNG.

### 🖥️ Скриншот видимой области (Viewport) `[ALT+2]`
Мгновенный захват экрана. Идеально для быстрой фиксации того, что вы видите прямо сейчас.

### 📜 Полный скриншот страницы `[ALT+3]`
> **СУПЕР-ФИЧА:** Склеивает длинную страницу из нескольких кадров с автоматическим пре-скроллом!
- Умный алгоритм заранее прокручивает страницу, чтобы активировать *Lazy Load* изображения и CSS-анимации.
- Скрывает `fixed`/`sticky` элементы (например, плавающие шапки), чтобы не появлялись дублирующиеся артефакты.
- Никаких полос прокрутки, никаких искажений. Идеальный результат.

### 🎛️ Плавающее окно (Undock) `[ALT+M]`
Расширение можно открепить от браузера! Оно превращается в независимый плавающий виджет, который можно перемещать по всему экрану, чтобы он не мешал при работе.

### 📐 Точная работа с DPI
Использует `Device Pixel Ratio` вашего монитора для безупречной `pixel-perfect` обрезки даже на 4K дисплеях.

---

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/fire.gif" width="100%">
</p>

## ⚙️ АРХИТЕКТУРА [UNDER THE HOOD]

<details>
<summary><b>[ ПОКАЗАТЬ ВНУТРЕННОСТИ ]</b></summary>

### ⬛ `background.js`
Мозг расширения. Отвечает за:
- Глобальные горячие клавиши (Shortcuts)
- Захват видимого экрана вкладки
- Маршрутизацию плавающих окон
- Сохранение чистого PNG напрямую в загрузки (без создания лишних папок).

### 🟧 `content.js`
Фронтлайн операций:
- Интеллектуальная математика `getBoundingClientRect`
- Умный алгоритм прокрутки для полного скриншота
- Скрытие `fixed`/`sticky` элементов для чистой съемки
- Учет DPI при обрезке канваса

### 🟥 `popup.html` / `popup.js`
Панель управления в стиле *Brutalist*:
- Настроена под 3 языка (English, Română, Русский)
- Анимированные SVG-логотипы (Cyber Skull, Alien, Glitch и др.)
- Настройка стиля рамок прицеливания
</details>

---

## 🚀 УСТАНОВКА [INSTALLATION]

1. Скачайте этот репозиторий на свой ПК.
2. Распакуйте главный арих в любом месте.
3. Распакуйсте архив Ui inspector.
4. Откройте Google Chrome и перейдите в **Расширения** (`chrome://extensions/`).
5. Включите тумблер **Режим разработчика** (Developer mode) в правом верхнем углу.
6. Нажмите кнопку **Загрузить распакованное** (Load unpacked).
7. Выберите папку с проектом.

**СИСТЕМА ГОТОВА К РАБОТЕ.** 🟢

---

## 🕹️ ИСПОЛЬЗОВАНИЕ [HOW TO USE]

1. Кликните по иконке расширения в браузере или используйте **Горячие Клавиши** (`ALT+1`, `ALT+2`, `ALT+3`, `ALT+M`).
2. При захвате элемента — наведите курсор на нужный блок. Появится анимированная рамка с размерами.
3. Кликните левой кнопкой мыши.
4. Файл сохранится автоматически с именем формата `screenshot-[timestamp].png`.

*(Окно расширения закроется само, чтобы не попасть в кадр)*

---

## 🔐 РАЗРЕШЕНИЯ [PERMISSIONS]

- `activeTab` — доступ к активной странице для вычислений координат.
- `tabs` — управление вкладками и внедрение скриптов.
- `downloads` — автоматическое сохранение файлов скриншотов.
- `storage` — сохранение ваших настроек стиля и языка.
- `<all_urls>` — работа расширения на любых сайтах без исключений.

---

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="600">
</p>

<div align="center">

### 💻 РАЗРАБОТЧИКИ [CREDITS]

**Maxim** — ✈️ <a href="https://t.me/Scheptic" target="_blank">Telegram (@Scheptic)</a><br>
**Antigravity (AI)** — 🌌 <a href="https://antigravity.google/" target="_blank">antigravity.google</a>



> *"Built with cold logic and pixel-perfect precision."*



<img src="https://komarev.com/ghpvc/?username=maxim-pintea-ui-capture&color=FF4500&style=for-the-badge&label=VISITS" alt="Profile Views" />

</div>
