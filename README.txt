کاشێر — پڕۆژەی ئەندرۆید
=========================
ڕێگای ١ (بێ دابەزاندنی هیچ پرۆگرامێک) — GitHub:
  1. ڕیپۆیەکی نوێ لە github.com دروست بکە.
  2. هەموو فایلەکانی ئەم فۆڵدەرە upload بکە (لەگەڵ فۆڵدەری .github).
  3. بڕۆ بۆ Actions > Build APK > چاوەڕێ بکە تا تەواو دەبێت (~٣ خولەک).
  4. لە خوارەوەی پەڕەکە kashier-apk دابگرە، zip ەکە بکەرەوە، app-debug.apk ت دەستدەکەوێت.

ڕێگای ٢ — Android Studio لە ویندۆز:
  File > Open > ئەم فۆڵدەرە هەڵبژێرە
  Build > Build App Bundle(s) / APK(s) > Build APK(s)
  APK لێرە دەبێت: app\build\outputs\apk\debug\app-debug.apk

دامەزراندن لە مۆبایل: APK بنێرە بۆ مۆبایل و بیکەرەوە.
ئەگەر پرسیاری کرد، ڕێگە بە "Install unknown apps" بدە.

گۆڕینی ئەپەکە: تەنها فایلی app/src/main/assets/index.html بگۆڕە و دووبارە build بکە.
