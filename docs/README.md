# Документация

# Документация сайта "Автоматизация процессов Московского Политеха"

## 1. Структура проекта

```
project-root/
├── index.html # Главная страница
├── project.html # Страница проекта
├── team.html # Страница команды
├── images/ # Папка с изображениями
│ ├── logo.svg # Логотип Московского Политеха
│ └── journal/ # Фотографии для журнала
│ ├── meeting.jpg
│ └── prototype.jpg
├── css/ # Стили
│ ├── style.css # Основные стили
│ ├── home.css # Стили главной страницы
│ ├── project.css # Стили страницы проекта
│ └── team.css # Стили страницы команды
└── js/ # JavaScript
└── script.js # Основные скрипты
```

## 2. Технологии

- HTML5
- CSS3 (Flexbox, Grid)
- JavaScript (базовый)
- Font Awesome 6.4.0 (иконки)
- Адаптивный дизайн

## 3. Основные компоненты

### 3.1. Шапка сайта
```html
<header>
    <div class="container">
        <div class="header-content">
            <a href="index.html" class="logo-container">
                <img src="images/logo.svg" alt="Московский Политех">
                <span class="logo-text">Московский Политех</span>
            </a>
            <nav>
                <ul>
                    <li><a href="project.html"><i class="fas fa-project-diagram"></i>О проекте</a></li>
                    <li><a href="team.html"><i class="fas fa-users"></i>Участники</a></li>
                </ul>
            </nav>
        </div>
    </div>
</header>
<div class="journal-entry">
    <img src="images/journal/NEW_IMAGE.jpg" alt="Описание фото">
    <div class="journal-content">
        <div class="journal-date">Дата</div>
        <h3>Заголовок</h3>
        <p>Описание события</p>
    </div>
</div>
```
### 3.2. Журнал проекта
```
<section class="project-journal">
    <div class="journal-container">
        <h2>Журнал проекта</h2>
        <div class="journal-grid">
            <div class="journal-entry">
                <img src="images/journal/meeting.jpg" alt="Совещание">
                <div class="journal-content">
                    <div class="journal-date">15 января 2023</div>
                    <h3>Старт проекта</h3>
                    <p>Описание события...</p>
                </div>
            </div>
        </div>
    </div>
</section>
```
## 4. Добавление фотографий
### 1. Создание папки images/journal
### 2. Добавление картинки
```
<div class="journal-entry">
    <img src="images/journal/NEW_IMAGE.jpg" alt="Описание фото">
    <div class="journal-content">
        <div class="journal-date">Дата</div>
        <h3>Заголовок</h3>
        <p>Описание события</p>
    </div>
</div>
```
