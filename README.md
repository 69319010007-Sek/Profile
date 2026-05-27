# Profile
Hello I am Sek54
# 👋 ยินดีต้อนรับสู่ GitHub ของผม/ดิฉัน [ใส่ชื่อของคุณที่นี่]
https://rms.bncc.ac.th/files/importpicstd/01/69319010007.jpg
### 🎓 ข้อมูลการศึกษา
* **สถาบัน:** วิทยาลัยพณิชยการบางนา (Bangna Commercial College)
* **สาขาวิชา:** เทคโนโลยีสารสนเทศ (Information Technology)
* **วิชาที่กำลังเน้น:** การพัฒนาส่วนหลัง (Backend Development)

---

## 🎯 จุดประสงค์ในการเข้าศึกษาต่อ
ผม/ดิฉัน มีความมุ่งมั่นที่จะพัฒนาทักษะด้านการเขียนโปรแกรมและการจัดการระบบฐานข้อมูล โดยเฉพาะในสาขา **เทคโนโลยีสารสนเทศ** เพื่อเป้าหมายดังนี้:
1.  **เข้าใจโครงสร้างระบบ:** เรียนรู้การทำงานของ Server-side และการจัดการ Logic ที่ซับซ้อน
2.  **ต่อยอดทักษะ Backend:** พัฒนา Web Application ที่มีประสิทธิภาพและปลอดภัย
3.  **เตรียมความพร้อมสู่สายอาชีพ:** ฝึกฝนการทำงานร่วมกับผู้อื่นผ่านระบบ Version Control (Git) เพื่อเป็นนักพัฒนาซอฟต์แวร์ในอนาคต

---

## 💻 ทักษะและความสนใจ (Interests)
### 🛠️ Backend Development
* **Language:** JavaScript (Node.js)
* **Framework:** Express.js
* **Database:** MongoDB, MySQL

### ⚙️ Tools & Workflow
* Git / GitHub
* Postman (สำหรับทดสอบ API)
* VS Code

---

## 🚀 ตัวอย่างการเขียน Code ด้วย Node.js
นี่คือตัวอย่างการสร้าง **Simple Web Server** เบื้องต้นโดยใช้ Express.js:

```javascript
// นำเข้า Library express
const express = require('express');
const app = express();
const port = 3000;

// สร้าง Route สำหรับหน้าแรก
app.get('/', (req, res) => {
  res.send('สวัสดีครับ! ยินดีต้อนรับเข้าสู่ระบบ Backend ของผม');
});

// เริ่มต้นการทำงานของ Server
app.listen(port, () => {
  console.log(`Server is running at http://localhost:${port}`);
});