# AI Portfolio Website

Современный технологичный сайт-портфолио, созданный с помощью **Accio**.

## Особенности
- **Стиль**: Темно-синий / Неоново-фиолетовый tech-дизайн.
- **Стек**: HTML5, Tailwind CSS, Lucide Icons.
- **Адаптивность**: Полная поддержка мобильных устройств.
- **Контент**: Ссылки на проекты, GPTs агенты, средства автоматизации и AI-стек.

## Как разместить на GitHub Pages

1. **Создайте репозиторий** на GitHub (например, `portfolio`).
2. **Загрузите файлы**: `index.html` и этот `README.md`.
3. **Включите GitHub Pages**:
   - Перейдите в **Settings** (Настройки) вашего репозитория.
   - Выберите вкладку **Pages** в левом меню.
   - В разделе **Build and deployment** выберите ветку `main` и папку `/ (root)`.
   - Нажмите **Save**.
4. Через пару минут ваш сайт будет доступен по адресу `https://ваш-логин.github.io/portfolio/`.

## Изображение
В `index.html` используется прямая ссылка на изображение из Google Drive. Если изображение не отображается:
1. Скачайте изображение из [Google Drive](https://drive.google.com/file/d/1bi5hhQBYWiphqua8dHu6iLTiaDKzo6XM/view?usp=sharing).
2. Поместите его в папку с сайтом под названием `hero.png`.
3. Замените в `index.html` строку:
   ```html
   <img src="https://lh3.googleusercontent.com/d/1bi5hhQBYWiphqua8dHu6iLTiaDKzo6XM" ...>
   ```
   на:
   ```html
   <img src="hero.png" ...>
   ```

---
*Сделано за 10 минут с помощью Accio.*
