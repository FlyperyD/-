# Штучний інтелект — окремий вид комп’ютерних технологій

Шкільний проєкт учнів 10-Б класу: **Франческа Артемович** та **Максим Журило**.

Статичний сайт (HTML, CSS, JavaScript) без залежностей і збірки.

## Структура
- `index.html` — весь сайт
- `.nojekyll` — вимикає обробку Jekyll на GitHub Pages

## Публікація на GitHub Pages
1. Створіть репозиторій на GitHub (наприклад, `ai-project`).
2. Завантажте файли з цієї папки в корінь репозиторію:
   ```bash
   git init
   git add .
   git commit -m "Додано сайт проєкту про ШІ"
   git branch -M main
   git remote add origin https://github.com/<ваш-логін>/ai-project.git
   git push -u origin main
   ```
3. У репозиторії: **Settings → Pages → Deploy from a branch → main / (root) → Save**.
4. Через хвилину сайт буде доступний за адресою `https://<ваш-логін>.github.io/ai-project/`.

## Що змінити перед публікацією
- У футері `index.html` замініть `[назва школи]` на реальну назву.
