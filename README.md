# Свой счёт

Личный трекер подписок, рассрочек, долгов, праздников и дел. Один HTML-файл, данные в Firebase Firestore.

## Настройка облака (один раз)

1. Firebase Console → создай проект → Build → Firestore Database → Create database.
2. Build → Authentication → Get started → Sign-in method → включи Anonymous.
3. Firestore → Rules: вставь содержимое `firestore.rules` и нажми Publish.
4. Project settings → Your apps → Web app (`</>`) → скопируй `apiKey`, `authDomain`, `projectId`, `appId` в блок `CLOUD` в начале скрипта в `index.html`.

## Публикация

Settings → Pages → Deploy from a branch → `main`, папка `/ (root)`.
