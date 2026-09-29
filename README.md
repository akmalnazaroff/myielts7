# IELTS Telegram Tracker

Bu MVP sizning `Daily Tracker` Excel planningizni o'qiydi va Telegram orqali tasklarni tracking qiladi.

## Funksiyalar
- `/start`
- `/today`
- `/progress`
- Har bir task uchun `Done / Not done`
- SQLite database
- Siz yuborgan `plan.xlsx` avtomatik import qilinadi

## Ishga tushirish

1. Telegram'da @BotFather orqali bot yarating.
2. Token oling.
3. Python 3.11+ o'rnating.
4. Terminalda:
   `pip install -r requirements.txt`
5. Windows PowerShell:
   `$env:BOT_TOKEN="TOKENINGIZ"`
   `python bot.py`

Tokenni hech qachon kodga yozib GitHub'ga yuklamang.

Keyingi bosqichlarda reminder, weekly/monthly statistics va Google Sheets sync qo'shish mumkin.
