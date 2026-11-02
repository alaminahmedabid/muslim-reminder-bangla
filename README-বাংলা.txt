Muslim Reminder Bangla — আপডেটেড PWA প্যাকেজ

GitHub repository-র root-এ সব ফাইল ও icons ফোল্ডার আপলোড করুন।
ফাইল: index.html, manifest.webmanifest, sw.js, icons/icon-192.png, icons/icon-512.png

নতুন সুবিধা:
- 192px ও 512px অ্যাপ আইকন
- পৃথক রিমাইন্ডার ON/OFF, সময়, টেস্ট, যোগ ও মুছে ফেলা
- ডিভাইসে স্থানীয় প্রোফাইল নাম
- আগের কুরআন, নামাজের সময়, তাসবিহ ও আমল রিপোর্ট

সীমাবদ্ধতা:
- Gmail sign-in চালু করতে Firebase project ও OAuth configuration দরকার; এখানে ভুয়া লগইন নেই।
- Reminder notification/voice এই ওয়েব অ্যাপ খোলা থাকা অবস্থায় কাজ করে; বন্ধ থাকলে background alarm নিশ্চিত নয়।
- ডেটা এখনো এই ডিভাইসের localStorage-এ থাকে, cloud sync নয়।
- সত্যিকারের APK ও নির্ভরযোগ্য background alarm-এর জন্য native Android wrapper প্রয়োজন।
