
# 🎬 Video AI Tool (FastAPI версія)

## ✅ Встановлення
1. Створи віртуальне середовище (рекомендовано):
   python -m venv venv
   source venv/bin/activate (або venv\Scripts\activate в Windows)

2. Встанови залежності:
   pip install -r requirements.txt

3. Створи .env на базі .env.example і введи дані

4. Запусти проєкт:
   uvicorn app.main:app --reload

5. Відкрий браузер: http://127.0.0.1:8000/

## ⚙️ Що вміє:
- Приймає YouTube-посилання
- Запускає обробку (заглушка)
- Генерує назву до відео (T5-small)
- Показує відео та дозволяє завантажити (заглушка)
