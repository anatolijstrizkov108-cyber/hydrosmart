# HydroSmart — персональный трекер гидратации

Мобильное приложение (iOS/Android) для расчёта индивидуальной нормы воды
и адаптивных напоминаний.

## Стек
- Flutter / React Native
- Firebase (Auth + Firestore)
- OneSignal (push)
- ML Kit (анализ паттернов активности)
- Погодный API

## Структура
- `docs/` — SMART-задание (Заданий № 3)
- `lib/` (или `src/`) — исходный код
- `.gitignore`, `.gitattributes`, `.env.example` — конфигурация Git

## Запуск
1. Скопировать `.env.example` → `.env` и заполнить ключи.
2. `flutter pub get` (или `npm install`).
3. `flutter run` (или `npm start`).