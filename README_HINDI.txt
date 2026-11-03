SADRUN TRADERS – ANDROID OFFLINE APP PROJECT

यह Android WebView wrapper project है। ऐप का पूरा billing HTML app/src/main/assets/index.html में रखा है। ऐप में INTERNET permission नहीं है और billing UI local HTML से खुलता है।

APK बनाने के लिए कंप्यूटर पर Android Studio आवश्यक है:
1. Android Studio install करें और Android SDK Platform 35 तथा Android Build Tools install करें।
2. ZIP extract करें। Android Studio > Open > इस project का SadrunTradersOffline folder चुनें।
3. Gradle Sync पूरा होने दें। अगर Gradle JDK पूछा जाए तो Android Studio का Embedded JDK (17 या compatible) चुनें।
4. Build > Build Bundle(s) / APK(s) > Build APK(s) चुनें।
5. Build पूरा होने पर app/build/outputs/apk/debug/app-debug.apk मिलेगा। इसे फोन में भेजकर install करें।
6. फोन में Unknown apps / Install unknown apps की अनुमति देनी पड़ सकती है। केवल अपने बनाए APK को install करें।

महत्वपूर्ण:
- इस ZIP में APK binary शामिल नहीं है; इस वातावरण में Android SDK/Gradle उपलब्ध नहीं होने के कारण APK compile नहीं किया जा सका।
- यह पूरी तरह offline, single-device ऐप है। कोई cloud sync या automatic online backup नहीं है।
- App data WebView local storage में रहता है। ऐप uninstall या app storage clear करने से डेटा मिट सकता है। Reports / Backup से JSON backup नियमित रूप से export करें और सुरक्षित जगह रखें।
- पहले dummy product और test bills से जाँचें। वास्तविक बिक्री से पहले GST/tax calculations और invoice format अपने CA से verify करें।
