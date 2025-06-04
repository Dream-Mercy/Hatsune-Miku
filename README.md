# 🎶 Тема "Vocaloid Dream" для Shikimori
**Описание**: Свежая аниме-тема в стиле Хацунэ Мику с нежными сиреневыми акцентами и сочными зелёными элементами, вдохновлёнными её узнаваемым образом "лука-порея".
➤ **Полностью кастомизируемая** — легко меняются фоны, цвета и анимации
➤ **Адаптивный дизайн** — идеально выглядит на ПК и мобильных
➤ **Интерактивные элементы** с плавными hover-эффектами
![Скриншот](https://i.ibb.co/1t23c9C7/99px-ru-wallpaper-344672-vocaloid-hatsune-miku-vokaloid-hatsune-miku-v.jpg) Фон по умолчанию (можно заменить)

![Скриншот](https://i.ibb.co/wFL2bN0N/99px-ru-wallpaper-328205-vocaloid-vokaloid-hatsune-miku-hatsune-mik.jpg) баннер по умолчанию (тоже можно заменить).
## 🛠 Установка
1.Установи расширение Stylus для Chrome/Firefox.

2.Нажми → RAW-ссылка на CSS.

3.В Stylus выбери "Установить стиль".

Или вставь вручную:
```css
@import url("https://raw.githubusercontent.com/ed-main/ed-main.github.io/master/cssfiles/main_code_1.css");
@import url("https://raw.githubusercontent.com/ed-main/ed-main.github.io/master/cssfiles/main_code_2.css");
@import url("https://raw.githubusercontent.com/ed-main/ed-main.github.io/master/cssfiles/main_code_3.css");
@import url("https://raw.githubusercontent.com/ed-main/ed-main.github.io/master/cssfiles/main_code_4mob.css");
@import url("https://raw.githubusercontent.com/ed-main/ed-main.github.io/master/cssfiles/prof_form_over.css");
@import url("https://raw.githubusercontent.com/Dream-Mercy/Hatsune-Miku//main/Hatsune%20Miku.css");
```
## ✨ Особенности
### 🎨 Цветовая схема
#### Прогрессбары (Лук-порей)
```css
:root {  
  --time-filled: 190, 255, 150; /* Светло-зелёный */
  --time-empty: 210, 240, 180; /* Бледно-зелёный */
  --anime-inprocess: 150, 230, 150; /* Мятный */
  --anime-complete: 100, 220, 100; /* Ярко-зелёный */
  --manga-inprocess: 150, 230, 150; /* Мятный */
  --manga-complete: 100, 220, 100; /* Ярко-зелёный */
}
```
### 🎮 Интерактивные элементы  
1.Кнопки с градиентными переходами

2.Анимированные рейтинги (сиреневые → розовые)

3.Кастомный скроллбар в стиле Project DIVA

### 🌟 Эксклюзивные элементы
маленькая танцующая Хацунэ Мику в углу профиля
```css
.p-profiles-show .b-feedback:after {
content: '';
display: inline-block;
position: fixed;
width: 298px;
height: 298px;
right: -50px;
bottom: 0px;
background: url("https://i.ibb.co/VfcHKS8/mine.gif") no-repeat;
background-size: cover;
z-index: 10;
pointer-events: none;
}
```
Можете добавить ещё одну Мику, просто используйте этот код:
```css
.p-profiles-show .b-feedback:before{ 
content: '';
display: inline-block;
position: fixed;
width: 220px; 
height: 220px; 
left: -25px; 
bottom: 0px; 
background: url("ВАША_МИКУ.gif") no-repeat;
background-size: cover;
z-index: 10; 
pointer-events: none;
}
```
**!** Не забудьте изменить значения width, height, left и bottom под вашу gif, иначе она будет не в том месте на экране (или будет кривой) **!**
### Анимация рейтингов:
**Высокий**: яркий сиреневый

**Средний**: сиреневый

**Низкий**: тёмный сиреневый

## 📱 Адаптивность
1.Оптимизировано для мобильных устройств

2.Гибкая сетка элементов

3.Упрощённая навигация на маленьких экранах
## 🐛 Багрепорты
Нашли ошибку? Создайте issue с:

1.Скриншотом проблемы

2.Версией браузера

3.Шагами для воспроизведения
## 💡 Советы по кастомизации
1.Сменить фон: 
```css
body::after {
  background-image: url("ВАША_ССЫЛКА.jpg");
}
```
2.Сменить баннер:
```css
@media screen and (min-width: 1200px) {
  #profiles_show .profile-head::after {
    content: "";
    display: block;
    position: absolute;
    width: 100%;
    height: 100%;
    background-image: url(СЮДА_ВСТАВЬТЕ_ВАШУ_ССЫЛКУ.jpg);
    background-size: cover;
    background-position: center;
    z-index: 1;
  }
```
Вдохновение: Hatsune Miku, Project DIVA, Vocaloid

«39! 🎵» — Хацунэ Мику

«World is Mine» © Хацунэ Мику
## 📸 Скриншоты  
Тут должны быть скриншоты, но мне лень 😋
## ✨ Совет:
Для полного погружения включите музыку от Хацунэ Мику во время использования темы и просто при проведении времени на сайте!
