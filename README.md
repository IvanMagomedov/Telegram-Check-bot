🤖 Telegram Bot: Проверка Email, Телефона и IP

Этот телеграм-бот выполняет следующие функции:
	•	🔍 Проверка email-адреса
	•	📞 Проверка номера телефона
	•	🌐 Проверка IP-адреса
	•	🕓 Сохраняет и отображает историю последних 10 команд


🚀 Быстрый старт

1. Клонируйте репозиторий


git clone https://github.com/your-username/telegram-bot.git
cd telegram-bot

2. Установите зависимости
Убедитесь, что у вас установлен Python 3.7+ и pip:


pip install -r requirements.txt

3. Создайте .env файл
⚠️ Не публикуйте этот файл в открытом доступе!
Создайте файл .env в корне проекта и добавьте в него ваши токены:

TELEGRAM_TOKEN=your_telegram_bot_token
PHONE_API_TOKEN=your_phone_api_token
EMAIL_API_TOKEN=your_email_api_token

4. Запустите бота

python main.py



🧩 Используемые технологии
	•	python-telegram-bot — библиотека для работы с Telegram Bot API
	•	dotenv — загрузка переменных окружения
	•	requests — запросы к внешним API
	•	json — работа с историей команд
	•	os, time — стандартные модули


📸 Примеры команд
/email example@gmail.com
/phone +123456789
/ip 8.8.8.8
/history










