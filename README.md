# كود بالعربي — أولى ثانوي 2027

منصة تعليمية عربية جاهزة كبداية عملية، مبنية بـ HTML/CSS/JavaScript + Firebase Realtime Database + Firebase Authentication.

## التشغيل
1. افتح Firebase Console لمشروع `code-a7783`.
2. فعّل Authentication > Sign-in method > Email/Password.
3. أنشئ Web App داخل المشروع وانسخ إعداداته.
4. افتح `firebase-config.js` واستبدل:
   - `YOUR_FIREBASE_WEB_API_KEY`
   - `YOUR_MESSAGING_SENDER_ID`
   - `YOUR_FIREBASE_APP_ID`
5. غيّر `ADMIN_EMAIL` إلى بريد المدير.
6. طبّق قواعد `database.rules.json` على Realtime Database.
7. ارفع الملفات كما هي إلى GitHub Pages أو Netlify أو أي استضافة static.

## الصفحات
- `index.html` الرئيسية
- `login.html` تسجيل الدخول
- `register.html` إنشاء حساب
- `dashboard.html` لوحة الطالب
- `course.html?id=c1` صفحة الكورس
- `lesson.html?course=c1&lesson=l1` صفحة الدرس
- `admin.html` لوحة الإدارة

## ملاحظات
- فيديوهات YouTube تُعرض داخل المنصة عبر Embed، ولا يتم نسخ أو رفع ملفات الفيديو.
- بيانات الدروس التجريبية تُزرع تلقائيًا في أول تشغيل إذا كانت قاعدة البيانات لا تحتوي على `courses`.
- رابط قاعدة البيانات مضمّن بالفعل: https://code-a7783-default-rtdb.firebaseio.com/
- للحصول على تسجيل دخول يعمل فعليًا يجب وضع Web App config من Firebase؛ رابط قاعدة البيانات وحده لا يحتوي على API key الخاص بتطبيق الويب.
