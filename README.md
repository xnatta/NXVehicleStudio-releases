# NX Vehicle Studio

Windows 11 x64 Vehicle Editor — v0.6.0

[ดาวน์โหลดรุ่นล่าสุด](https://github.com/xnatta/NXVehicleStudio-releases/releases/latest)

OBJ → สร้างรถเองโดยไม่ใช้ Template → กำหนดชิ้นส่วน/Primary/Secondary/Glass/Emissive/Extra/Mod Kit → เพิ่ม/ลบ Seats กับ Entry points/Dummy → Rig/Physics/Handling → Export YFT/_hi/YTD/Meta/fxmanifest เป็น Resource ใหม่ พร้อมโหมดแก้รถ YFT เดิม

ใหม่: สร้างจากฐานรถ เก็บ Physics/Collision/Handling/การบินของ Resource ที่คุณนำเข้า ล้างโมเดลและที่นั่งเดิม แล้วใส่ OBJ/ที่นั่งใหม่อย่างอิสระ ไม่ต้องมี Mesh ล้อจริง ใช้ชื่อ Model เดิมและปิด Resource ต้นฉบับก่อนทดสอบ ดู BASE-WORKFLOW.md ใน Release

รถพิเศษสร้างใหม่ใช้ฐาน car/bike ยังไม่รองรับ Boat/Aircraft/Weapon authoring ทุกชนิด ไม่มี Ped/YCD ใหม่/Glass shatter/Damage authoring และ Game Acceptance รอผู้ใช้ทดสอบ ไม่อ้างว่าแทน ZModeler ได้ทุกกรณี

ใช้ WebView2 Evergreen Bootstrapper ไม่ต้องมี Node/Rust บนเครื่องปลายทาง ติดตั้ง WebView2 ครั้งแรกต้องใช้อินเทอร์เน็ต อัปเดต HTTPS + Tauri signature พร้อม Recovery ตัวติดตั้งยังไม่มี Authenticode

Source: [NXVehicleModel](https://github.com/xnatta/NXVehicleModel) (private)
