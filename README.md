# X O - تيك تاك تو (Android)

لعبة X O (Tic-Tac-Toe) بسيطة كتطبيق أندرويد، مبنية بـ HTML/CSS/JS ومغلفة بـ Capacitor.

## الميزات
- وضع لاعب ضد لاعب
- وضع لاعب ضد الكمبيوتر (ذكاء اصطناعي minimax)
- تتبع النتائج
- دعم RTL (العربية)

## البناء (APK)
1. ارفع المشروع إلى GitHub (Public repo).
2. GitHub → Actions → "Build Android APK" → Run workflow.
3. حمّل الـ artifact (TicTacToe-Android-APK) → app-debug.apk.
4. ثبّته على هاتفك (قد تحتاج تفعيل "مصادر غير معروفة").

## تشغيل محلي
```bash
python -m http.server 8000 --directory www
```
افتح http://localhost:8000
