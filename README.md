# MS HOST v6

لوحة استضافة Flask تعمل على Replit وتكتشف مشاريع Python وNode تلقائياً.

## التشغيل
```bash
pip install -r requirements.txt
python app.py
```

يتم استخدام `PORT` تلقائياً، ويجب أن يكون السيرفر مربوطاً على `0.0.0.0`. عند رفع مشروع، يكتشف النظام ملف التشغيل (`main.py` أو `server.js` أو `package.json` وغيرها) وملفات المكتبات (`requirements.txt` أو `pyproject.toml` أو `Pipfile` أو `package.json`) ويثبتها تلقائياً قبل التشغيل.

## متغيرات البيئة
`PORT`, `SECRET_KEY`, `ADMIN_EMAIL`, `ADMIN_PASSWORD`, `USERS_DIR`, `DB_FILE`, `BOT_TOKEN`, `ADMIN_TELEGRAM_ID`

> غيّر كلمة مرور المسؤول الافتراضية عبر `ADMIN_PASSWORD` قبل النشر العام.
