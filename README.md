# مليونير كرة القدم - Football Millionaire Web App ⚽🏆

تطبيق ويب تفاعلي لمسابقات كرة القدم مستوحى من برنامج "من سيربح المليون"، مبني بالكامل بتقنيات الويب النقية (HTML5, CSS3, Vanilla JavaScript) وبدون أي مكاتب خارجية مع مؤثرات صوتية عبر Web Audio API.

## المميزات ✨
- **15 مرحلة متدرجة الصعوبة** مع بنك أسئلة كروي متخصص (تاريخ بطولات، أساطير، الكرة الذهبية، دوري الأبطال، وكأس العالم).
- **نظام تسجيل لاعب / زائر (Guest/Player mode)**.
- **وسائل مساعدة كلاسيكية**:
  - 50:50 (حذف إجابتين)
  - رأي الجمهور (Audience poll)
  - تخطي السؤال (Skip question)
- **مؤثرات صوتية مدمجة ديناميكياً** عبر Web Audio API بدون الحاجة لتحميل ملفات mp3 خارجية.
- **تصميم متجاوب بالكامل (Mobile-Friendly)** جاهز للتحويل إلى تطبيق أندرويد عبر WebView أو Cordova/Capacitor.

## طريقة الرفع على GitHub 🚀

1. أنشئ مستودعاً جديداً (New Repository) على حسابك في GitHub.
2. فك ضغط ملف الـ ZIP على جهازك.
3. افتح موجه الأوامر (Terminal أو Git Bash) داخل مجلد المشروع ونفذ:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Football Millionaire Game"
   git branch -M main
   git remote add origin https://github.com/USERNAME/REPO_NAME.git
   git push -u origin main
   ```
4. لتشغيل الموقع أونلاين مجاناً، يمكنك تفعيل **GitHub Pages** من إعدادات المستودع (Settings > Pages) أو ربطه مباشرة بـ **Netlify**.

## ملفات المشروع 📂
- `index.html`: واجهة اللعبة وهيكل الشاشات.
- `style.css`: التصميم والتنسيقات والمؤثرات البصرية.
- `app.js`: منطق اللعبة والأسئلة ومولد الأصوات.
- `README.md`: وثيقة المشروع.
