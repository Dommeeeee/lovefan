
# 🚀 คู่มือการ Deploy เว็บไซต์

## 📋 ตัวเลือกการ Deploy

### 1. GitHub Pages (ฟรี)
1. อัปโหลดโค้ดไปยัง GitHub repository
2. ไปที่ Settings > Pages
3. เลือก Source: Deploy from a branch
4. เลือก Branch: main/master
5. กด Save
6. เว็บจะอยู่ที่ `https://username.github.io/repository-name`

### 2. Netlify (ฟรี)
1. ไปที่ [netlify.com](https://netlify.com)
2. ลาก drop ไฟล์ทั้งหมดไปยัง Deploy area
3. หรือเชื่อมต่อกับ GitHub repository
4. เว็บจะได้ URL แบบ `https://random-name.netlify.app`

### 3. Vercel (ฟรี)
1. ไปที่ [vercel.com](https://vercel.com)
2. Import project จาก GitHub
3. กด Deploy
4. เว็บจะได้ URL แบบ `https://project-name.vercel.app`

### 4. Replit Static Deployment (แนะนำ)
1. เปิด Deployments tab ใน Replit
2. เลือก "Static" deployment type
3. ตั้งค่า Public directory เป็น `./`
4. กด Deploy
5. เว็บจะได้ URL แบบ `https://project-name.replit.app`

## 📁 ไฟล์ที่จำเป็น

- ✅ `index.html` - หน้าหลัก
- ✅ `package.json` - ข้อมูลโปรเจกต์
- ✅ `README.md` - คำอธิบายโปรเจกต์
- ✅ `.gitignore` - ไฟล์ที่ไม่ต้องอัปโหลด
- ✅ `netlify.toml` - การตั้งค่า Netlify
- ✅ `vercel.json` - การตั้งค่า Vercel

## 🔗 ลิงก์ที่เป็นประโยชน์

- [GitHub Pages Guide](https://pages.github.com/)
- [Netlify Deploy Guide](https://docs.netlify.com/)
- [Vercel Deploy Guide](https://vercel.com/docs)
- [Replit Static Deployment](https://docs.replit.com/hosting/deployments-overview)

## 💡 เคล็ดลับ

1. **ใช้ Replit**: ง่ายที่สุด ไม่ต้องย้ายไฟล์ไปไหน
2. **ใช้ GitHub Pages**: ฟรี แต่ต้องมี GitHub account
3. **ใช้ Netlify/Vercel**: เร็ว และมีฟีเจอร์เพิ่มเติม

---

🎉 **ขอให้สนุกกับการแชร์เว็บไซต์รักกับอ้วนนะครับ!** 💖
