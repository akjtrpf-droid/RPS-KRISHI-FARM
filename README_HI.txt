R.P.S. कृषि फार्म — Android Demo Source

महत्वपूर्ण:
- यह Android Studio का source project है, APK फ़ाइल नहीं।
- यह offline demo HTML चलाता है।
- इसमें अभी Google Sheet / Apps Script sync नहीं जुड़ा है।
- Demo में जो एंट्री जोड़ी जाती है, वह असली फार्म डेटा नहीं है।

APK बनाने के लिए:
1. Android Studio में यह project folder खोलें।
2. Gradle sync पूरा होने दें (इंटरनेट की जरूरत पड़ सकती है)।
3. Build > Build Bundle(s) / APK(s) > Build APK(s) चुनें।
4. APK app/build/outputs/apk/debug/ में बनेगा।

असली डेटा sync जोड़ने से पहले मौजूदा Apps Script Web App URL और server-side access checks की जरूरत होगी।
