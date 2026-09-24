# CutFlow Changelog

## 0.5.8
- เผยแพร่แพ็กเกจอัปเดตและติดตั้งใหม่ พร้อม SHA-256
- ใช้แพ็กเกจ paper-test ที่ยืนยันว่าใช้งานได้ โดยไม่เปลี่ยน Registration Mark หรือ Native SA

## 0.5.7
- คืน Registration Mark Type 1 และ Type 2 ให้ตรงกับ v0.5.0 ที่ใช้งานกับ Cutting Master ได้จริง
- Type 1 กลับเป็น `SA regmark type1 auto 31 2.83 2.83 28.35 1224.57 1224.57 0 -1 0.00 0 0.00 0.00`
- `SA info` ทั้งสอง Type กลับเป็น `SA info 0 0 0 17.01 2 0 0 0 0 0`
- คงระบบปรับขนาดกระดาษเองและการแก้ updater/Illustrator จากรุ่นหลัง


## 0.5.6
- เพิ่มไฟล์ `README_ILLUSTRATOR_LAYERS_TH.txt` ที่ขาดจากแพ็กเกจ 0.5.5
- แก้ `[WinError 2]` ตอนสร้างชุด Graphtec/Illustrator


## 0.5.5
- ใช้ Mark.ai ที่ Cutting Master อ่านได้จริงเป็น baseline สำหรับ Type 1
- Type 1 regmark: `31 5.67 2.83 28.35 1224.57 1224.57 ...`
- Type 1 SA info: `SA info 0 0 0 17.01 3 0 0 0 0 0`
- Type 2 คง reference เดิม v0.4.2 จนกว่าจะมีไฟล์ AI Type 2 ที่ยืนยันได้


## 0.5.4
