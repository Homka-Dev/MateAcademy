# MateAcademy
# 🎧 Bose Landing Page — MateAcademy Marathon Project

Це адаптивна односторінкова вебсторінка, створена під час марафону від [MateAcademy](https://mate.academy/). Сайт натхненний продукцією компанії **Bose** і демонструє вміння працювати з сучасними інструментами веброзробки: HTML, CSS та SCSS.

---

## 🔗 Демо

🖥 [Переглянути сайт](https://homka-dev.github.io/MateAcademy/) 

---

## 🛠 Технології

- **HTML5** — семантична структура сторінки  
- **SCSS (Sass)** — вкладеність, змінні, чистий і організований стиль-код  
- **CSS3** — анімації, адаптивність  
- **Google Fonts (Inter)** — чистий, сучасний шрифт  
- **Якірна навігація** — плавний скролінг між секціями

---

## 📁 Структура проєкту

mateacademy-bose-landing/
├── index.html
├── css/
│ └── style.css ← скомпільований SCSS
├── scss/
│ └── style.scss ← вихідний файл SCSS
├── images/
│ ├── Logo.png
│ ├── icon/
│ │ ├── Icon-Burger-menu.png
│ │ └── Icon-Close.png
│ ├── header-bg.png
│ ├── Sound waves.png
│ ├── recommended/
│ │ ├── person-1.png
│ │ └── ...
│ └── categories/
│ ├── photo-1.png
│ └── ...
└── footer.png
---

## 📦 Секції сайту

- `Header`: логотип, бургер-меню, заголовок
- `Menu`: адаптивне навігаційне меню з плавною появою
- `Recommended`: секція рекомендованих товарів
- `Categories`: карточки з категоріями (навушники, колонки, окуляри)
- `Why buy direct`: переваги покупки напряму від бренду
- `Footer`: завершальна частина з великим зображенням

---

## 🎨 Особливості стилізації

- **SCSS вкладеність** забезпечує чистоту та зручну підтримку коду
- Використовується **позиціонування, flexbox, transition**
- Ефекти наведення: underline з анімацією на `nav__link`

---

## 🚀 Як запустити локально

```bash
git clone https://github.com/your-username/bose-landing.git
cd bose-landing
# Відкрий index.html у браузері
