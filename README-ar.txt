بناء ملف APK
=============
الطريقة الأسهل (بدون كمبيوتر):
1) أنشئ مستودعاً جديداً على github.com وارفع محتويات هذا المجلد كاملاً (بما فيه المجلد المخفي .github).
2) افتح تبويب Actions ثم Build APK وانتظر دقيقتين تقريباً.
3) في أسفل صفحة التشغيل، نزّل phone-repair-apk فيه app-debug.apk ثم ثبّته (فعّل "التثبيت من مصادر غير معروفة").

على الكمبيوتر: افتح المجلد في Android Studio ثم Build > Build APK(s)،
أو نفّذ: gradle assembleDebug
الملف الناتج: app/build/outputs/apk/debug/app-debug.apk

تعديل الأسعار والأرقام: app/src/main/assets/index.html
