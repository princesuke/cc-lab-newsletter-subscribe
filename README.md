# 🧪 Lab: สมัครรับข่าวสาร (React Router)

## 🎯 วัตถุประสงค์
- ใช้งาน `<NavLink>` สำหรับเมนูนำทาง
- ใช้ `useNavigate()` เพื่อเปลี่ยนหน้าแบบ programmatic

## 📝 คำสั่ง
ให้สร้างเว็บไซต์ที่มี 3 หน้า:
- `/news` - ข่าวสารล่าสุด
- `/subscribe` - หน้ากรอก email
- `/success` - ขอบคุณสำหรับการสมัคร

### 🔧 สิ่งที่ต้องทำ:
1. สร้างแบบฟอร์มบนหน้า `/subscribe`
   - ฟิลด์กรอก email
   - ปุ่ม “สมัครเลย”
2. เมื่อกดปุ่ม ให้ใช้ `useNavigate()` ไปยัง `/success`
3. ถ้าไม่ได้กรอก email → ไม่ให้ navigate (validate แบบง่าย ๆ ก็พอ)
4. ใช้ `<NavLink>` ใน Navbar เพื่อเน้นหน้าที่กำลังแสดงอยู่

> 🚫 ห้ามใช้ window.location.href

---

## 💡 ทิป
- ใช้ `useState()` เพื่อเก็บค่า input
- ใช้ `e.preventDefault()` กันหน้า reload
- สไตล์เพิ่มเองได้ตามสะดวก
