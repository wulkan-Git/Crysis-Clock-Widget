# Crysis Clock Widget 🎮

Стильные аналогово-цифровые часы в тематике игры Crysis с футуристическим дизайном и неоновой подсветкой.

![Crysis Clock](screenshot.png)

## ✨ Особенности

- 🕐 Аналоговые и цифровые часы
- 📱 Полностью адаптивный дизайн (mobile-first)
- 🎨 Neon green стиль в духе Crysis
- ⚡ Плавная анимация стрелок
- 🌐 Работает офлайн
- 🔧 Легко встраивается в WordPress и другие CMS
- 🎯 Интерактивный эффект (кликните по часам)

## 📦 Установка

### 1. Клонирование репозитория

```bash
git clone https://github.com/wulkan-Git/crysis-clock-widget.git
cd crysis-clock-widget
```
### 2. Добавление фонового изображения
Поместите ваше изображение Crysis в папку с файлом и назовите его crysis-background.jpg (или измените путь в CSS).
## 🚀 Использование
Как standalone страница
Просто откройте файл index.html в браузере.
Встраивание в WordPress
## Способ 1: Через HTML виджет
Зайдите в Внешний вид → Виджеты
Добавьте виджет "Произвольный HTML"
Скопируйте всё содержимое между тегами <body> из index.html
Добавьте CSS в Внешний вид → Настроить → Дополнительные стили
JavaScript добавьте перед закрывающим тегом </body> или через плагин
## Способ 2: Через плагин Insert Headers and Footers
Установите плагин WPCode или Insert Headers and Footers
Вставьте полный код в секцию Footer
## Способ 3: Как iframe
```html
<iframe src="path/to/crysis-clock.html" width="500" height="500" frameborder="0"></iframe>
```
## Встраивание в другой сайт
```html
<!-- Вставьте в любое место -->
<div class="crysis-clock-wrapper">
    <!-- скопируйте сюда содержимое .crysis-clock-container -->
</div>

<!-- CSS добавьте в <head> -->
<style>
    /* скопируйте стили отсюда */
</style>

<!-- JS добавьте перед </body> -->
<script>
    /* скопируйте скрипты отсюда */
</script>
```
## 🎨 Настройка
### Изменение цвета подсветки
Найдите в CSS все упоминания #00ff00 и замените на нужный цвет:
#00ffff - голубой (cyan)
#ff00ff - розовый (magenta)
#ffaa00 - оранжевый
### Изменение размера
Измените max-width в .crysis-clock-container:
```CSS
.crysis-clock-container {
    max-width: 400px; /* было 500px */
}
```
## Отключение FPS счетчика
Удалите или закомментируйте:
```html
<div class="crysis-fps" id="fpsCounter">60 FPS</div>
```
## 📱 Браузеры
✅ Chrome (последняя версия)
✅ Firefox (последняя версия)
✅ Safari (последняя версия)
✅ Edge (последняя версия)
✅ Mobile browsers

## 📄 Лицензия
### MIT License
## 🙏 Благодарности
Игра Crysis от Crytek за вдохновение
Все кто использует этот виджет!
