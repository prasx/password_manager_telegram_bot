# Password Manager Bot - BotGenPass

Этот проект представляет собой Telegram бота для генерации и хранения паролей. Бот позволяет пользователям генерировать случайные пароли, хранить их в безопасном месте, а также просматривать историю созданных паролей.

## Функциональность

- Генерация случайных паролей различной длины и сложности.
- Хранение последнего сгенерированного пароля и его даты создания.
- Возможность просмотра истории созданных паролей.
- Шифрование паролей с использованием мастер-ключа для обеспечения безопасности данных.

## Технологии

Этот проект реализован с использованием следующих технологий:

- Python 3.11
- [aiogram](https://github.com/aiogram/aiogram) - фреймворк для создания Telegram ботов на Python.
- SQLite - для хранения данных о пользователях и их паролях.
- [cryptography](https://github.com/pyca/cryptography) - для шифрования паролей.

## Использование

Для запуска бота необходимо выполнить следующие шаги:

1. Установить все зависимости, выполнив `pip install -r requirements.txt`.
2. В модуле `connect.py` заполнить API_TOKEN полученный от [https://t.me/BotFather](@BotFather). 
3. Запустить бота, выполнив `python main.py`.


## Дополнительная информация

Этот проект создан в рамках обучения и может быть доработан и расширен в соответствии с потребностями пользователя. Если у вас есть какие-либо вопросы или предложения по улучшению проекта, не стесняйтесь обращаться! [https://t.me/m1_leu](@m1_leu)
