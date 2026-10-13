# NX Vehicle Studio

โปรแกรม Windows 11 x64 — v0.3.0 Vehicle Foundation

[ดาวน์โหลดตัวติดตั้ง](https://github.com/xnatta/NXVehicleStudio-releases/releases/latest)

นำเข้า OBJ/MTL/Texture และ YFT Legacy/FiveM พร้อม _hi.yft/YTD, Viewport/Hierarchy/Transform/Undo/Redo/Project Save-Load/Performance Monitor

รุ่น 0.3.0 เพิ่ม Drawable/LOD assignment และ Material Presets (Default, Primary, Secondary, Glass, Emissive) แยกเฉพาะชิ้นที่เลือก พร้อมเก็บ Source YFT/YTD และ Resource Meta/Manifest/YCD ที่พบใน Project Schema 2 เปิดโปรเจกต์ Schema 1 ได้

มี Binary YFT Writer ทดลองโครงสร้างจาก OBJ สีล้วน แต่ **ยังไม่มี Skeleton/Physics/Collision/Seat Editor และยังไม่ใช่ Resource รถพร้อมใช้** ยังไม่ยืนยัน Runtime/Shader Fields ครบในเกม อ่านข้อจำกัดใน Release Notes/TEST-REPORT

ติดตั้งสำหรับผู้ใช้ปัจจุบัน ใช้ WebView2 Evergreen มี Bootstrapper ในตัวติดตั้ง เครื่องปลายทางไม่ต้องมี Node/Rust การติดตั้ง WebView2 ครั้งแรกต้องมีอินเทอร์เน็ต ระบบอัปเดต HTTPS + Tauri signature พร้อม Recovery ก่อนติดตั้ง ตัวติดตั้งยังไม่มี Authenticode certificate

[Source/แผนพัฒนาสำหรับเจ้าของโปรเจกต์](https://github.com/xnatta/NXVehicleModel) (private)
