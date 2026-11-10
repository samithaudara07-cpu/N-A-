N&A AI Android Project

මෙය ඔබ ලබාදුන් index.html එක Android WebView app එකක් ලෙස විවෘත කරන Android Studio project එකකි.

APK එක සෑදීම:
1. පරිගණකයක Android Studio ස්ථාපනය කර විවෘත කරන්න.
2. මෙම ZIP එක Extract කරන්න.
3. Android Studio -> Open -> Extract කළ NA_AI_Android_Project folder එක තෝරන්න.
4. Gradle sync අවසන් වන තුරු රැඳී සිටින්න.
5. Build -> Build Bundle(s) / APK(s) -> Build APK(s) තෝරන්න.
6. APK එක app/build/outputs/apk/debug/ තුළ ලැබේ.
7. එය ඔබගේ Android phone එකට යවා ස්ථාපනය කරන්න.

වැදගත්:
- මෙම ZIP එක APK එක නොව APK සෑදීමට අවශ්‍ය source project එකයි. APK build කිරීමට Android Studio සහ Android SDK සහිත පරිගණකයක් අවශ්‍යයි.
- AI පිළිතුරු ලබාගැනීමට Groq API Key එක අවශ්‍යයි. App එකේ Settings තුළ key එක ඇතුළත් කළ යුතුයි.
- දැනට ඇති HTML එක API key එක browser storage/local app storage තුළ තබයි. එය වෙනත් අයට බෙදා නොදෙන්න. ආරක්ෂිත public release එකකට API key එක server එකක තබන backend එකක් අවශ්‍යයි.
- Voice typing පහසුකම Android WebView / device speech service සහාය මත රඳා පවතී; සෑම දුරකථනයකම ක්‍රියා කරන බවට සහතිකයක් නැත.


Phone එකෙන් Cloud APK Build කිරීම (GitHub Actions):
1. GitHub account එකකට sign in වෙන්න.
2. github.com/new වෙත ගොස් අලුත් repository එකක් සාදන්න.
3. ZIP එක extract කර ඇති project එකේ සියලුම files/folders repository එකට upload කරන්න. .github folder එකත් upload විය යුතුයි.
4. Repository එකේ Actions tab එකට යන්න.
5. 'Build N&A AI APK' workflow එක තෝරා 'Run workflow' ඔබන්න.
6. Build එක සාර්ථක වූ පසු workflow run එක විවෘත කර Artifacts යටතේ N-A-AI-debug-APK download කරන්න.
7. ZIP එක extract කර app-debug.apk ස්ථාපනය කරන්න.

GitHub UI එකේ වෙනස්කම් තිබිය හැක. Build fail වුණොත් error message එක එවන්න.
