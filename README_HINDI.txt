RK SOLUTION — اردو سیکھیں (AdMob APK Project)
================================================

यह Android Studio project APK बनाने के लिए तैयार है।

AdMob:
App ID: ca-app-pub-3822431624321367~7102674903
Live Banner Ad Unit: ca-app-pub-3822431624321367/9355830974

महत्वपूर्ण:
• Debug build में Google का TEST banner लगाया गया है, ताकि testing के दौरान live ads पर accidental clicks न हों।
• Release build में आपकी LIVE Banner Ad Unit ID अपने-आप इस्तेमाल होगी।
• नया Ad Unit बना होने के बाद ads दिखने में Google के अनुसार कुछ समय (कभी-कभी लगभग 1 घंटे तक) लग सकता है।

APK बनाने का तरीका:
1. ZIP को extract करें।
2. Android Studio खोलें।
3. Open चुनकर project folder RK_SOLUTION_URDU_SIKHE_ADMOB खोलें।
4. Gradle Sync पूरा होने दें। Internet चालू रखें ताकि Android Gradle Plugin/AdMob/AndroidX dependencies download हो सकें।
5. ऊपर Build > Build APK(s) चुनें।
6. Debug APK सामान्यतः app/build/outputs/apk/debug/app-debug.apk में बनेगा।

Play Store के लिए:
Build > Generate Signed Bundle / APK > APK या Android App Bundle चुनें।
अपनी release keystore बनाकर सुरक्षित रखें; keystore खोने पर future updates में समस्या हो सकती है।

App में:
• Urdu RTL interface
• Jameel Noori Nastaleeq Kasheeda font
• About Us photo
• حروفِ تہجی, لفظ بنائیں, گنتی, پہاڑے
• AdMob banner
• Internet permission
• Portrait mobile layout

नोट: यह source project APK compilation के लिए तैयार है। इस environment में Android SDK/Gradle build tool उपलब्ध न होने के कारण यहाँ compiled APK बनाना संभव नहीं है।
