Fahim Siam Traders - Android Local Business App
================================================

এটি একটি Android Studio project। এই পরিবেশে Android SDK/Gradle build tool নেই,
তাই এখানে সরাসরি APK compile বা test করা সম্ভব হয়নি। এই ZIP-এ APK তৈরির সম্পূর্ণ
প্রজেক্ট সোর্স দেওয়া হলো।

APK তৈরি:
1. কম্পিউটারে Android Studio ইনস্টল করুন।
2. Android Studio > Open নির্বাচন করে এই ফোল্ডারটি খুলুন।
3. Gradle sync শেষ হতে দিন (প্রথমবার ইন্টারনেট লাগবে)।
4. Build > Build Bundle(s) / APK(s) > Build APK(s) নির্বাচন করুন।
5. APK পাবেন: app/build/outputs/apk/debug/app-debug.apk
6. ফোনে APK পাঠিয়ে Install করুন। প্রয়োজনে Android Settings-এ এই ফাইল/অ্যাপের
   জন্য Install unknown apps অনুমতি দিন।

ফিচার:
- বিক্রি, কাস্টমারের বাকি ও বাকি আদায়
- পণ্য/স্টক তালিকা
- খরচ
- ড্যাশবোর্ড ও রিপোর্ট
- CSV export (Excel-এ খোলা যাবে)
- JSON backup/restore
- LocalStorage-এ অফলাইন ডেটা

গুরুত্বপূর্ণ:
- ডেটা শুধু এই অ্যাপের লোকাল WebView storage-এ থাকে।
- অ্যাপের ডেটা Clear বা Uninstall করলে হিসাব হারাতে পারেন।
- নিয়মিত JSON backup নিয়ে নিরাপদ স্থানে রাখুন।
- এই প্রাথমিক সংস্করণে বিক্রি এন্ট্রি পণ্যের স্টক স্বয়ংক্রিয়ভাবে কমায় না;
  পণ্য তালিকা আলাদাভাবে রক্ষণাবেক্ষণ করতে হবে।
- এটি debug APK build-এর জন্য প্রস্তুত; Play Store release-এর জন্য আলাদা signing
  ও release configuration প্রয়োজন।
