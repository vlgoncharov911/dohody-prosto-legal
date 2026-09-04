# Зеркало публичного legal-сайта (локальная рабочая копия)

Источник GitHub: `https://github.com/vlgoncharov911/dohody-prosto-legal`  
Публикация: `https://vlgoncharov911.github.io/dohody-prosto-legal/`

## Что сделано 05.09.2026

- `/main/` синхронизирован с утверждённым пакетом App 1.0.1 / versionCode 2.
- Текущие редакции: Privacy/Terms/PRO/Backup 1.0.1; Deletion/Licenses 1.0.0.
- Создан публичный архив `/main/archive/1.0.0/` из локального `Копии оригиналов/1.0.0/`.
- `/apps/dohody-prosto/` показывает «Версия 1.0.1».
- Demo и `app-ads.txt` не менялись.

## Что сделано 25.08.2026

- Обновлена только Main Privacy → `/main/privacy/` (редакция **1.0.1-main-draft**).
- Demo `/demo/` не менялся.

## Что сделано 24.08.2026

- Обновлён раздел `/main/` — 7 документов Main (редакция 1.0.0-main-draft).
- Обновлена корневая `index.html`: Demo и Main как два отдельных продукта.
- `/demo/` **не менялся** (остался эталон 1.3.x-demo).

## Как опубликовать

На машине с git:

```text
cd C:\EarnOS\dohody-prosto-legal
git add main/privacy/index.html
git commit -m "Main Privacy 1.0.1-main-draft: Yandex Ads links L1/L2"
git push origin main
```

Канон текстов: `Контракты/Документы/RuStore/Копии оригиналов` и `legal/packages/rustore/ru/`.
