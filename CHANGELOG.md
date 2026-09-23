# CutFlow Changelog

## 0.5.6
- เพิ่มไฟล์ `README_ILLUSTRATOR_LAYERS_TH.txt` ที่ขาดจากแพ็กเกจ 0.5.5
- แก้ `[WinError 2]` ตอนสร้างชุด Graphtec/Illustrator

## 0.5.5
- ใช้ Mark.ai ที่ Cutting Master อ่านได้จริงเป็น baseline สำหรับ Type 1
- Type 1 regmark: `31 5.67 2.83 28.35 1224.57 1224.57 ...`
- Type 1 SA info: `SA info 0 0 0 17.01 3 0 0 0 0 0`
- Type 2 คง reference เดิม v0.4.2 จนกว่าจะมีไฟล์ AI Type 2 ที่ยืนยันได้

## 0.5.4
- แก้เปิด Illustrator อัตโนมัติ โดยเปิด SVG ผ่าน Illustrator.exe โดยตรงก่อนเชื่อม COM
- รอเอกสารเปิดจริงก่อนสร้าง Native SA layers และบันทึก AI
- ไม่เสนอ SVG ดิบเป็นไฟล์ตัด Graphtec เพราะยังไม่ใช่ Native SA

## 0.5.3
- แก้ ERR_EMPTY_RESPONSE หลังอัปเดตจากการรัน CutFlow ซ้ำหลาย process
- เพิ่ม single-instance guard ป้องกันการ bind พอร์ต 8765 ซ้ำ
- เพิ่ม health endpoint `/health`
- updater เปิดผ่าน `run_cutflow.bat` เพียงครั้งเดียวหลังติดตั้ง

## 0.5.2
- แก้ Illustrator error `the operation was cancelled` ตอนเปิด SVG อัตโนมัติ
- เปลี่ยนจาก COM `Application.Open` เป็น ExtendScript `app.open()`
- เพิ่มข้อความผิดพลาดที่ชัดเจนขึ้นเมื่อ Illustrator เปิด SVG ไม่สำเร็จ

## 0.5.1
- เพิ่มช่องกำหนดขนาดกระดาษ กว้าง × สูง (cm)
- ค่าเริ่มต้นยังเป็น 33 × 48 cm
- เพิ่มปุ่มสลับแนวกระดาษ
- จำขนาดกระดาษล่าสุดใน LocalStorage
- บันทึกขนาดกระดาษรวมกับ Preset
- Preview, การจัดเรียง, ARMS marks และ SVG export ใช้ขนาดกระดาษที่กำหนดจริง

## 0.5.0
- เพิ่มระบบ GitHub updater
