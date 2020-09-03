# Телеграм бот для уведомелений о статусе проверки заданий на dvmn.org

Бот, используя апи dvmn.org следит за статусом проверки ваших заданий и уведомляет в телеграм канал.

## Как установить


Для работы бота нужен Python версии не ниже 3.6.

```bash
pip install -r requirements.txt
```

и настроенные переменные окружения `DEVMAN_TOKEN` (ваш токен из личного кабинета на dvmn), `TELEGRAM_TOKEN` (токен для созданного бота) и `CHAT_ID` (id чата между вами и ботом).

## Как запустить

```bash
python main.py
```

# Цели проекта

Код написан в учебных целях — это урок в курсе по Python и веб-разработке на сайте [Devman](https://dvmn.org).