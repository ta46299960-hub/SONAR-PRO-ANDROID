SONAR PRO ULTIMATE — Android WebView project

هذا مشروع Android Studio لتحويل نسخة PWA المرفقة إلى تطبيق Android مستقل (WebView).
لا يحتاج إلى خادم Termux بعد تثبيت التطبيق. يحتاج الإنترنت لبيانات السوق وTradingView.

بناء APK:
1) افتح مجلد SONAR_PRO_ANDROID في Android Studio.
2) انتظر مزامنة Gradle وتنزيل Android Gradle Plugin.
3) اختر Build > Build Bundle(s) / APK(s) > Build APK(s).
4) بعد نجاح البناء ستجد الملف في:
   app/build/outputs/apk/debug/app-debug.apk

المتطلبات:
- Android Studio حديث.
- JDK 17.
- Android SDK Platform 35 وBuild Tools المناسبة.
- اتصال إنترنت أثناء أول مزامنة Gradle.

ملاحظة: هذا مشروع المصدر الجاهز للبناء وليس APK مبنياً. بيئة الإنشاء الحالية لا تحتوي Android SDK أو Gradle، لذلك لم أستطع إصدار APK موثوق هنا.
