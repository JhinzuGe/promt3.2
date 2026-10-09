[readme_md.md](https://github.com/user-attachments/files/33237311/readme_md.md)
# 🤖 หุ่นยนต์ครูน้อย (Little Teacher Robot)

เว็บแอปพลิเคชันเพื่อการเรียนรู้เชิงโต้ตอบสำหรับเด็ก ช่วยเสริมสร้างทักษะและพัฒนาการผ่านหุ่นยนต์ครูน้อยผู้ช่วยสุดน่ารัก

---

## 🚀 การนำขึ้นใช้งานบน Vercel (Deployment to Vercel)

คุณสามารถนำโปรเจกต์นี้ขึ้นใช้งานบน **Vercel** ได้อย่างง่ายดายด้วยวิธีใดวิธีหนึ่งดังต่อไปนี้:

### วิธีที่ 1: ผ่าน Vercel Dashboard (แนะนำ)

1. **อัปโหลดโค้ดขึ้น GitHub / GitLab / Bitbucket**
   - สร้าง repositoryใหม่ และ push โค้ดโปรเจกต์นี้ขึ้นไป

2. **เชื่อมต่อกับ Vercel**
   - เข้าสู่ระบบที่ [Vercel.com](https://vercel.com/)
   - คลิกที่ปุ่ม **"Add New..."** -> **"Project"**
   - เลือก Repository ของคุณที่อัปโหลดไว้

3. **ตั้งค่าการ Deploy (Build Settings)**
   - **Framework Preset**: Vercel จะตรวจจับให้อัตโนมัติ (เช่น Vite, Next.js หรือ Create React App)
   - **Build Command**: `npm run build` หรือ `vite build`
   - **Output Directory**: `dist` หรือ `build` (ขึ้นอยู่กับเครื่องมือที่ใช้)

4. **ตั้งค่า Environment Variables (ถ้ามี)**
   - หากใช้ API Key ให้เพิ่มในหัวข้อ *Environment Variables* ก่อนกด Deploy

5. **กด Deploy**
   - รอ Vercel ประมวลผลสักครู่ เมื่อเสร็จแล้วจะได้ URL สำหรับเข้าใช้งานทันที!

---

### วิธีที่ 2: ผ่าน Vercel CLI

1. ติดตั้ง Vercel CLI บนเครื่องของคุณ:
   ```bash
   npm i -g vercel
   ```

2. ล็อกอินเข้าสู่ระบบ Vercel:
   ```bash
   vercel login
   ```

3. สั่ง Deploy จากโฟลเดอร์โปรเจกต์:
   ```bash
   vercel
   ```

4. หากต้องการนำขึ้น Production ให้ใช้คำสั่ง:
   ```bash
   vercel --prod
   ```

---

## 🛠️ การติดตั้งและรันในเครื่อง (Local Development)

1. **Clone Repository:**
   ```bash
   git clone https://github.com/your-username/little-teacher-robot.git
   cd little-teacher-robot
   ```

2. **ติดตั้ง Package / Dependencies:**
   ```bash
   npm install
   # หรือ
   yarn install
   ```

3. **เริ่มใช้งานในโหมด Development:**
   ```bash
   npm run dev
   # หรือ
   yarn dev
   ```

4. เปิดบราวเซอร์ไปที่ `http://localhost:5173` (หรือ Port ที่ระบบแจ้ง)

---

## 📂 โครงสร้างโปรเจกต์ (Project Structure)

```text
├── public/          # ไฟล์ Static เช่น รูปภาพ, ไอคอน
├── src/             # โค้ดหลักของแอปพลิเคชัน (Components, Logic)
├── index.html       # HTML Main Entry
├── package.json     # รายการ Dependencies และ Scripts
└── README.md        # คู่มือการใช้งานโปรเจกต์
```

---

## 📝 ไลเซนส์ (License)

โปรเจกต์นี้จัดทำขึ้นเพื่อการศึกษาและการพัฒนาสื่อการเรียนรู้ (MIT License)
