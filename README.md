
🤖 Telegram Bot: Проверка Email, Телефона и IP

Этот Telegram-бот позволяет удобно проверять:
	•	📧 Email-адреса
	•	📱 Номера телефонов
	•	🌐 IP-адреса
	•	🕓 Сохраняет и отображает историю последних 10 команд

⸻

🚀 Быстрый старт

1. Клонируйте репозиторий

git clone https://github.com/your-username/telegram-bot.git
cd telegram-bot

2. Установите зависимости

Убедитесь, что у вас установлен Python 3.7+ и pip, затем выполните:

pip install -r requirements.txt

3. Настройте переменные окружения

Создайте файл .env в корне проекта и добавьте туда ваши токены API:

TELEGRAM_TOKEN=your_telegram_bot_token
PHONE_API_TOKEN=your_phone_api_token
EMAIL_API_TOKEN=your_email_api_token

⚠️ Важно: не публикуйте .env в открытом доступе!

4. Запустите бота

python main.py


⸻

🧩 Используемые технологии
	•	python-telegram-bot — взаимодействие с Telegram API
	•	dotenv — загрузка конфигурации из .env
	•	requests — работа с внешними API
	•	json — хранение истории команд
	•	os, time — модули стандартной библиотеки

⸻

💬 Примеры команд

/email example@gmail.com       # Проверка email-адреса
/phone +123456789              # Проверка номера телефона
/ip 8.8.8.8                    # Проверка IP-адреса
/history                       # Просмотр последних 10 команд


⸻

📄 Лицензия

MIT License

⸻
