# تطبيق صيدلية الشفاء — بناء APK عبر GitHub

المشروع مجهز ليُبنى تلقائياً عبر GitHub Actions دون تثبيت Android Studio.

## بعد رفع الملفات إلى مستودع GitHub

1. افتح تبويب **Actions**.
2. اختر **Build Android APK**.
3. اضغط **Run workflow** ثم **Run workflow**.
4. انتظر ظهور علامة النجاح الخضراء.
5. افتح عملية البناء، ثم انزل إلى قسم **Artifacts**.
6. حمّل الملف **alshifa-app-debug-apk** وفك ضغطه.
7. ستجد داخله ملف **app-debug.apk** الجاهز للتثبيت.

> قد يبدأ البناء تلقائياً بمجرد رفع الملفات إلى الفرع main أو master.
