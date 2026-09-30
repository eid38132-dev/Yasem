# بنية Wake Word في ياسم

```text
الميكروفون
   ↓
WakeWordEngine
   ↓
اكتشاف «ياسم»
   ↓
SpeechRecognizer (ar-EG)
   ↓
Intent/Command Engine
   ↓
تنفيذ الأمر
   ↓
Text-to-Speech
   ↓
عودة للاستماع
```

الهدف هو ألا يبقى SpeechRecognizer مفتوحًا طوال الوقت بعد الانتقال للمحرك المتخصص.
