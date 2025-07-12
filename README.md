diff --git a/README.md b/README.md
index fb9141f3b70c466a57e4451b3ee67f18622458bb..8630c83086551ffe2f74a063f4208fd29d1592bb 100644
--- a/README.md
+++ b/README.md
@@ -1,18 +1,21 @@
 # FB Post Checker 888
 Test deployment trigger by Jarvis.
 โครงการนี้เป็นตัวอย่างสำหรับระบบสำรองข้อมูลและ deploy โปรเจกต์ Firebase แบบง่าย ๆ
 
 ## การติดตั้ง
 
 ```bash
 cd fbpost-checker-deploy && npm install
 ```
 
 ## การใช้งาน
 
 รันคำสั่งสำรองข้อมูลและ deploy ได้ดังนี้
 
 ```bash
 npm run backup
 npm run deploy
 ```
+
+## การทดสอบ
+cd fbpost-checker-deploy && npm test
