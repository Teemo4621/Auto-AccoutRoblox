## Auto-GENERATOR-ACCOUNT

เอ้าไว้สร้างไอดี roblox เองไวกว่าสร้างเองเเน่นอน!! สามารถเอาไปเป็นเเนวทางได้
เเต่ถ้าจะเปลี่ยนหรือเพิ่มอะไร **ให้เครดิตด้วยนะคับ**

## ต้องติดตั้งNodeJSก่อนนะคับ
สำคัญมากๆ(ไม่มีจะใช้ไม่ได้นะคับ)

* NodeJs [กดโหลดเลย](https://nodejs.org/en/)

## 📚 ขั้นตอนการติดตั้ง :

```
git clone https://github.com/Teemo4621/Auto-AccoutRoblox.git
cd NanoSpacePlus
npm install
```

## การเพิ่ม Discord Webhook
ให้ไปที่ไฟล์ `config.json` เเล้วใส่ลิ้งURL webhook ลงไป
```json
{
    "webhook": "ใส่ discord webhook"
}
```
ถ้าไม่ใส่ก็ได้ เเต่บัญชีจะถูกบันทึกลงไปในไฟล์ `account.txt` ที่จะมาหลังจากการสร้างรหัสเสร็จ
```json
{
    "webhook": ""
}
```

## 💻 วิธีการรัน :

```
npm start
npm run dev
```

## 🕹การใช้งาน
`rounds` คือให้ใส่ จำนวนรอบที่ต้องการสร้างรหัส เช่น 4 ระบบจะสร้าง บัญชี roblox ขึ้นมา 4 บัญชี <br />
`prefix username` คือให้ใส่ คำนำหน้าชื่อลงไป เช่น zemon เเล้วระบบจะสุ่มตัวอักษร 5 ตัวต่อท้าย (username ของคุณคือ zemoncxf4t) อะไรประมาณนั้น <br />
`length random password` คือให้ใส่ จำนวนรหัสเเบบสุ่มว่าจะมีกี่ตัว เช่น 4 ห้ามมากกว่า 9 ตัวเพราะ บางทีอาจจะสมัครไม่ได้ <br />
