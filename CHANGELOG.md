# CutFlow Changelog

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
