# 📸 Web Photo Booth (Cute Blue Theme) 💎❄️

ยินดีต้อนรับสู่โปรเจ็กต์ **Web Photo Booth**! แอปพลิเคชันถ่ายรูปติดบัตร 4 ช็อตสุดน่ารักทำงานผ่านเว็บเบราว์เซอร์ ที่ได้รับการปรับแต่งธีมให้เป็นสีฟ้าพาสเทลสดใส (Sky Blue Theme) สไตล์การ์ตูนผู้หญิง 💙✨

Welcome to the **Web Photo Booth** project! A super cute, browser-based 4-shot photo booth application featuring a pastel sky blue theme with a cute cartoon girl aesthetic. 💙✨

---

## ✨ ฟีเจอร์เด่น / Features
- 📸 **ถ่ายรูปแบบ 4 ช็อต (4-Shot Capture)**: กดครั้งเดียว ถ่ายต่อเนื่อง 4 รูปพร้อมนับถอยหลัง / One click to capture 4 consecutive shots with a countdown.
- 🎀 **ธีมสีฟ้าสุดคิ้วท์ (Cute Blue Theme)**: UI สีฟ้าสดใส, ฟอนต์ลายมือการ์ตูนน่ารัก (Mali Font), ปุ่มสามมิติแบบนูน / Bright blue UI, cute cartoon handwriting font (Mali), and 3D bouncy buttons.
- 🦋 **สติกเกอร์และแอนิเมชัน (Stickers & Animations)**: ของตกแต่งขยับได้ เช่น อีโมจิผีเสื้อ (🦋), เพชร (💎), หิมะ (❄️) / Animated floating decorations like butterflies (🦋), diamonds (💎), and snowflakes (❄️).
- 🖼️ **Photo Strip กราฟิกลายการ์ตูน (Cartoon Photo Strip Graphic)**: รวม 4 รูปในแผ่นเดียว พร้อมเทปแปะมุมสุดชิค และข้อความ "Cute Girls 💎" / Combines 4 photos into one strip with stylish corner tapes and a text overlay saying "Cute Girls 💎".
- 💾 **บันทึกรูปง่ายๆ (Easy Download)**: สามารถกดดาวน์โหลดภาพ Photo Strip เข้าเครื่องได้ทันที / Instantly download the final Photo Strip to your device.

---

## 🚀 วิธีการใช้งาน / How to Use
1. เปิดไฟล์ `index.html` ผ่านเว็บเบราว์เซอร์ (แนะนำให้เปิดบนอุปกรณ์ที่มีกล้อง) / Open `index.html` via a web browser (preferably on a device with a camera).
2. กดยอมรับการเข้าถึงกล้อง / Allow Camera Access when prompted.
3. กดปุ่ม **"เปิดกล้องโลด! 🪄"** เพื่อเข้าสู่โหมดเตรียมถ่าย / Click the **"Open Camera 🪄"** button to enter standby mode.
4. จัดท่าทางให้พร้อม แล้วกดปุ่ม **"ถ่ายเลย! (4 ช็อต)"** / Strike a pose and click **"Capture Now! (4 Shots)"**.
5. รอระบบนับถอยหลัง 3 วินาทีสำหรับแต่ละช็อตแอคชั่น! / Wait for the 3-second countdown for each action shot!
6. เมื่อครบ 4 รูป ระบบจะรวมภาพของคุณให้เป็นแบบตู้สติกเกอร์สุดน่ารัก / Once all 4 photos are taken, the system will generate a super cute photo strip.
7. กดปุ่ม **"บันทึกรูป 💎"** เพื่อดาวน์โหลดไปอวดเพื่อนๆ ได้เลย! / Click **"Save Photo 💎"** to download and share!

---

## 🛠️ เทคโนโลยีที่ใช้ / Tech Stack
- **HTML5 & CSS3**: จัดโครงสร้างและสไตล์ตกแต่ง / For structure and styling.
- **Tailwind CSS**: เฟรมเวิร์ค CSS สำหรับจัดรูปแบบ UI ได้อย่างรวดเร็วและสวยงาม / For rapid UI styling.
- **Vanilla JavaScript**: ควบคุมกล้อง (MediaDevices API) และการรวมภาพถ่าย (Canvas API) / For camera control and image processing.
- **Lucide Icons**: ไอคอนตกแต่งล้ำสมัยและน่ารัก / For modern, minimalist icons.
- **Google Fonts (Mali)**: ฟอนต์ลายมือสไตล์น่ารักสุดคิ้วท์ / For cute handwriting fonts.

---

## 🎨 การปรับแต่งเพิ่มเติม / Customization
หากต้องการแก้ไขสไตล์ คุณสามารถเปิดไฟล์ `index.html` ได้เลย: / To modify styles, edit `index.html` directly:
- **ฟอนต์ / Fonts**: เปลี่ยนลิงก์ Google Font ที่ส่วน `<head>` / Change the Google Font link in the `<head>` section.
- **สีพื้นหลัง / Background Colors**: ค้นหา `background-color` หรือ Tailwind utilities เช่น `bg-sky-50`, `bg-gradient-to-r` / Look for background styles or Tailwind classes.
- **แผ่นรูป Photo Strip**: สามารถปรับสีกรอบหรือคำบรรยายที่ตำแหน่งฟังก์ชัน `combinePhotosAndShowResult()` ใน JavaScript ได้เลย / Adjust strip colors or captions within the `combinePhotosAndShowResult()` JS function.

---

**สนุกกับการถ่ายรูปชิคๆ แบบตู้สติกเกอร์สีฟ้าคิ้วท์ๆ กันนะคะ! 💎🦋✨**  
**Enjoy taking cool photos with this cute blue sticker booth! 💎🦋✨**
