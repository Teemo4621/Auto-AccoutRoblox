## BASIC-Auto-GENERATOR-ACCOUNT

เอ้าไว้สร้างไอดี roblox เองไวกว่าสร้างเองเเน่นอน!! สามารถเอาไปเป็นเเนวทางได้
เเต่ถ้าจะเปลี่ยนหรือเพิ่มอะไร **ให้เครดิตด้วยนะคับ**<br>
(ผมเขียนนานมาเเล้วตั้งเเต่หัดเชียนโค้ดใหม่ๆเเต่ไม่ได้ลง เพราะลืมเเหะๆๆ ไปขุดเจอมา ถ้าว่างๆ เดี๋ยวจะมาทำให้ดีขึ้นนะคับบ)

ถ้าไม่เข้าใจตรงไหนให้ DM ผ่าน Discord ได้เลยนะคับ<br>
Discord: ZEMON#1269<br>
DiscordServer: https://discord.gg/mD55fcuPP8<br>

## ต้องติดตั้งNodeJSก่อนนะคับ | Install NodeJs
สำคัญมากๆ(ไม่มีจะใช้ไม่ได้นะคับ)

* NodeJs [กดโหลดเลย](https://nodejs.org/en/)

## 📚 ขั้นตอนการติดตั้ง | How to install :

```node
git clone https://github.com/Teemo4621/Auto-AccoutRoblox.git
cd Auto-AccoutRoblox
npm install or setup.bat
```

## การเพิ่ม Discord Webhook | Adding Discord Webhook
ให้ไปที่ไฟล์ `config.json` เเล้วใส่ลิ้ง URL webhook ลงไป
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

## 💻 วิธีการรัน | How to Start:

```node
node .
or
start.bat
```

## 🕹การใช้งาน | Usage
`rounds` คือให้ใส่จำนวนรอบที่ต้องการสร้างรหัส เช่น 4 ระบบจะสร้าง บัญชี roblox ขึ้นมา 4 บัญชี <br />
`prefix username` คือให้ใส่ คำนำหน้าชื่อลงไป เช่น zemon เเล้วระบบรันตัวเลขตามจำนวนรอบ <br />
