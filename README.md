# NX Vehicle Studio

Windows 11 x64 Vehicle Editor — v0.5.2

Hotfix: เติม Drawable1 ให้ Physics child ที่ไม่มี geometry เพื่อรับ Skeleton จากตัวถัง และบังคับตรวจ reference นี้ก่อน Export ตามสาเหตุจาก Crash Dump ของ 0.5.1 งานเก่าต้อง Export ใหม่ ชุด 0.5.2 ยังรอทดสอบใน FiveM จริง

[ดาวน์โหลดรุ่นล่าสุด](https://github.com/xnatta/NXVehicleStudio-releases/releases/latest)

OBJ → สร้างรถเองโดยไม่ใช้ Template → กำหนดชิ้นส่วน/Primary/Secondary/Glass/Emissive/Extra/Mod Kit → เพิ่ม/ลบ Seats กับ Entry points/Dummy → Rig/Physics/Handling → Export YFT/_hi/YTD/Meta/fxmanifest เป็น Resource ใหม่ พร้อมโหมดแก้รถ YFT เดิม

รถพิเศษสร้างใหม่ใช้ฐาน car/bike ยังไม่รองรับ Boat/Aircraft/Weapon authoring ทุกชนิด ไม่มี Ped/YCD ใหม่/Glass shatter/Damage authoring และ Game Acceptance รอผู้ใช้ทดสอบ ไม่อ้างว่าแทน ZModeler ได้ทุกกรณี

ใช้ WebView2 Evergreen Bootstrapper ไม่ต้องมี Node/Rust บนเครื่องปลายทาง ติดตั้ง WebView2 ครั้งแรกต้องใช้อินเทอร์เน็ต อัปเดต HTTPS + Tauri signature พร้อม Recovery ตัวติดตั้งยังไม่มี Authenticode

Source: [NXVehicleModel](https://github.com/xnatta/NXVehicleModel) (private)
