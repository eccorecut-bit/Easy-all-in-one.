Easy core cut all in one — Android APK project

গুরুত্বপূর্ণ:
- এটি Android Studio/online CI দিয়ে APK বানানোর source project; এটি নিজে APK ফাইল নয়।
- APK তৈরি করতে GitHub account এবং repository তৈরি/আপলোড করতে হবে।
- GitHub Actions-এ Build Android APK workflow চালালে app-debug.apk artifact পাওয়া যাবে।
- অ্যাপের হিসাব এই ফোনের WebView local storage-এ থাকবে। অ্যাপের data clear/uninstall করলে data হারাতে পারে; নিয়মিত backup রাখুন।

মোবাইল দিয়ে APK বানানোর সংক্ষিপ্ত ধাপ:
1) GitHub-এ সাইন ইন করে New repository তৈরি করুন (যেমন easy-core-cut-app)।
2) ZIP extract করে ভেতরের সব ফাইল repository-তে upload করুন; .github ফোল্ডারসহ।
3) Repository-এর Actions tab খুলুন। প্রথমবার workflow enable করতে বললে enable করুন।
4) "Build Android APK" workflow বেছে Run workflow চাপুন।
5) কাজ শেষ হলে workflow run খুলে নিচের Artifacts থেকে Easy-core-cut-all-in-one-APK ডাউনলোড করুন।
6) ZIP artifact extract করে app-debug.apk খুলুন। Android অনুমতি চাইলে এই উৎস থেকে install অনুমতি দিন।

নিরাপত্তা: APK শুধু নিজের তৈরি repository/workflow থেকে ডাউনলোড করুন।
