# Атлас Восприятия: Кураторство

Веб-приложение для кураторского отбора изображений из архива Ольги Розет.

## Использование

1. Откройте https://[username].github.io/atlas-curation/
2. Просматривайте изображения
3. Используйте кнопки или горячие клавиши:
   - `→` — Одобрить
   - `←` — Отклонить
   - `Пробел` — Пропустить
   - `Backspace` — Отменить последнее действие
4. По завершении скачайте результаты (JSON)

## Структура

- `index.html` — интерфейс кураторства
- `candidates.json` — список изображений для отбора
- `images/` — директория с изображениями (опционально)

## Развертывание

```bash
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/[username]/atlas-curation.git
git push -u origin main
```

Включите GitHub Pages в настройках репозитория (Settings → Pages → Source: main branch).

