# 60 Seconds! Reatomized — ม็อดแปลไทย (Thai Translation)

ม็อดแปลไทยโดยแฟน (ไม่เป็นทางการ) เพิ่ม "ไทย" เป็นภาษาใหม่ในเกม ภาษาอื่นยังใช้ได้ตามเดิม
รองรับเฉพาะ 60 Seconds! Reatomized เวอร์ชัน Steam (PC) build 22463805

**ดาวน์โหลด:** [60SecondsReatomized-Thai.zip](https://github.com/bignutchanon/60seconds-reatomized-thai/releases/latest/download/60SecondsReatomized-Thai.zip)
(หรือดูทุกเวอร์ชันที่หน้า [Releases](https://github.com/bignutchanon/60seconds-reatomized-thai/releases))

## ติดตั้ง
1. ปิดเกมก่อน
2. แตกไฟล์ zip แล้วดับเบิลคลิก `install.bat` — ตัวติดตั้งจะหาโฟลเดอร์เกมจาก Steam ให้เอง
   (ถ้าหาไม่เจอ จะให้วางพาธของโฟลเดอร์ที่มีไฟล์ 60SecondsReatomized.exe เอง)
3. เข้าเกม > Options > Audio & Language > Language แล้วกดลูกศรจนขึ้น "ไทย"

ตัวติดตั้งจะตรวจไฟล์เกมก่อนว่าเป็นเวอร์ชันที่ม็อดรองรับ ถ้าไม่ตรงจะยกเลิกโดยไม่แก้ไฟล์ใดเลย
จากนั้นสำรองไฟล์เดิม 5 ไฟล์ใน 60SecondsReatomized_Data เป็น .orig แล้วเขียนทับด้วยไฟล์ของม็อด

## ถอนการติดตั้ง
ดับเบิลคลิก `uninstall.bat` — คืนไฟล์เดิมจาก .orig ทั้ง 5 ไฟล์
หรือใช้ Steam > Properties > Installed Files > Verify integrity of game files

## ข้อควรทราบ
- ตัวหนังสือที่วาดอยู่ในภาพของเกม (ป้าย กระป๋องซุป ฯลฯ) และชื่อคนในเครดิตยังเป็นภาษาอังกฤษ
- ถ้าเกมอัปเดต ม็อดจะหายไปและอาจใช้กับเกมเวอร์ชันใหม่ไม่ได้ (ตัวติดตั้งจะแจ้งเอง) — รอม็อดเวอร์ชันใหม่
- เจอข้อความเพี้ยน ตกขอบ หรือแปลผิด แจ้งได้ที่ [Issues](https://github.com/bignutchanon/60seconds-reatomized-thai/issues) พร้อมภาพหน้าจอ
- ใช้กับเกมแท้เท่านั้น ไม่เกี่ยวข้องกับ Robot Gentleman ผู้พัฒนาเกม ห้ามนำไปขาย

## เครดิต
- แปลและทำม็อด: BigNut
- ฟอนต์ไทย: Mali โดย Cadson Demak (SIL Open Font License 1.1 — อยู่ใน `licenses/OFL-Mali.txt` ในไฟล์ zip)
- ตัดคำภาษาไทยด้วย PyThaiNLP
