SADRUN TRADERS – Android Offline App Source Project

यह Android Studio project है। ऐप WebView के अंदर bundled HTML चलाता है; इंटरनेट permission नहीं है और ऐप offline चलता है।

महत्वपूर्ण:
- यह ZIP अभी Android Studio source project है, compiled APK नहीं।
- APK बनाने के लिए Android Studio + Android SDK (API 35) और Gradle 8.7 / Android Gradle Plugin 8.6.1 की जरूरत होगी।
- Android Studio में इस folder को Open करें, Gradle Sync करें, फिर Build > Build APK(s) चुनें।
- APK सामान्यतः app/build/outputs/apk/debug/app-debug.apk में बनेगा।
- APK फोन में भेजकर install करें। Android में unknown app install permission देनी पड़ सकती है।
- ऐप डेटा फोन के ऐप WebView storage में रहता है। Uninstall / Clear storage से डेटा मिट सकता है। Reports > Backup से JSON बैकअप नियमित डाउनलोड करें।
- पहले dummy products और test bills से पूरी तरह जांचें। GST/HSN/tax compliance CA से verify करें।
