<div align="center">

# 👋 Hi, I'm Teerapong Kaewchuai (ธีรพงษ์ แก้วช่วย)
### 💻 Full-Stack Web Developer | Healthcare & Enterprise Digital Solutions
🎓 **B.Sc. in Information Technology and Digital Innovation** — *Walailak University*  
🏥 **Cooperative Education Intern (30 Weeks / 2 Semesters)** — *Medical Informatics Development, Bangkok Hospital Siriroj (BDMS Group)*  
🗓️ **Internship Period:** *20 April – 13 November 2026 (20 เมษายน – 13 พฤศจิกายน 2569)*  

[![Email](https://img.shields.io/badge/Email-telpls50%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:telpls50@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-trpxmac-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/trpxmac)

</div>

---

## 🛠️ Tech Stack & Tools

<p align="left">
  <img src="https://img.shields.io/badge/React_18_/_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/JavaScript_(ES6+)-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/LINE_LIFF_&_Messaging_API-00C300?style=for-the-badge&logo=line&logoColor=white" alt="LINE API" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" alt="Vitest" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

---

## 🏥 Featured Internship Projects — Bangkok Hospital Siriroj (BDMS)
> ผลงานการออกแบบและพัฒนาระบบสารสนเทศทางการแพทย์และระบบปฏิบัติการภายในโรงพยาบาลกรุงเทพสิริโรจน์ (แผนก Medical Informatics Development) ในการปฏิบัติสหกิจศึกษาต่อเนื่อง **2 ภาคการศึกษา รวมระยะเวลา 30 สัปดาห์ (20 เมษายน – 13 พฤศจิกายน 2569)** แบ่งเป็น **โปรเจกต์พัฒนาเดี่ยว (Solo Full-Stack)** 4 ระบบ และ **โปรเจกต์พัฒนาร่วมกับทีม (Team Co-Developed)** 2 ระบบ

### 👤 1. Solo Projects (ออกแบบและพัฒนาเดี่ยวแบบ End-to-End ครบวงจร)

| โครงการ (Project) | รายละเอียดและจุดเด่นของระบบ (Key Highlights) | Tech Stack | ลิงก์ (Repository) |
| :--- | :--- | :--- | :---: |
| **1. Hospital Cost Estimation MVP**<br>*(ระบบประเมินค่ารักษาพยาบาลและเวชภัณฑ์)* | • ประเมินค่ารักษาผู้ป่วยเคมีบำบัดและเวชภัณฑ์ แยกตามสิทธิ์การรักษา 4 ประเภท (`OPD`, `IPD`, `OPDTR`, `IPDTR`)<br>• ระบบจัดชุดรายการยาและหัตถการ (`Item Set Folding`) คำนวณสัดส่วนค่าใช้จ่ายอัตโนมัติ<br>• รองรับ **Offline Fallback (LocalStorage) & Auto-Migration** ซิงค์ข้อมูลขึ้น PostgreSQL ทันทีเมื่อออนไลน์ พร้อมออกใบประเมินราคา PDF | `React 18` `Vite` `Tailwind v4` `Node.js` `Express` `PostgreSQL` `Puppeteer` `Vitest` | [🔗 View Repo](https://github.com/trpxmac/cost-estimation-mvp) |
| **2. Doctor Leave @ LINE OA**<br>*(ระบบแจ้งลาและอนุมัติวันลาแพทย์ผ่าน LINE)* | • ยื่นใบลาผ่าน **LINE LIFF Mobile UI** ภายใน 60 วินาที พร้อมตรวจสอบโควตาแพทย์รายแผนกแบบเรียลไทม์<br>• แจ้งเตือนและกดอนุมัติ **1-Click Approve** ผ่าน **LINE Flex Message แบบ 1-on-1** (ยึดหลัก PDPA 100% ไม่ส่งเข้ากลุ่มรวม)<br>• ระบบจัดการลาฉุกเฉิน (`Same-Day Emergency Leave`), Web Admin Portal และบันทึก **Audit Trail** ทุกขั้นตอน | `React 19` `Vite` `Tailwind CSS` `LINE LIFF` `LINE Messaging API` `Express 5` `Supabase (PostgreSQL)` | [🔗 View Repo](https://github.com/trpxmac/doctor-leave-line) |
| **3. iPad Document e-Sign Pipeline**<br>*(ระบบลงนามเอกสารดิจิทัลบน iPad เชื่อมต่อ HIS/EHR)* | • ระบบลงลายมือชื่อดิจิทัลบน iPad (รองรับ Apple Pencil) เชื่อมโยงระบบโรงพยาบาล **iMed (HIS)** และ **EDSCare (EHR Archive)**<br>• สถาปัตยกรรม **Pure PDF Vector Pipeline** ไฟล์คมชัดขนาดเล็ก (~14–300 KB)<br>• บริการสกัดข้อมูลดิจิทัลจากใบประเมินราคาด้วย Python (`PyMuPDF`) คำนวณเงินมัดจำ 80% อัตโนมัติ พร้อมฝัง Audit Trail ลายเซ็นตามกฎหมาย | `React 18` `Vite` `Tailwind v4` `Python` `PyMuPDF` `jsPDF` `Signature Pad` | [🔗 View Repo](https://github.com/trpxmac/ipad-document-sign) |
| **4. Nurse Scheduling MVP**<br>*(ระบบจัดตารางเวรพยาบาลอัจฉริยะ)* | • ระบบช่วยจัดตารางเวรพยาบาลรายเดือนอัตโนมัติ (**AI Auto-Scheduling**) ตามเงื่อนไขและโควตาเวร (เช้า/บ่าย/ดึก)<br>• มุมมองปฏิทินแบบ **Ultra-Compact Monthly Roster** และตารางเวรรายบุคคล ดูภาพรวมทั้งตึกได้ในหน้าจอเดียว<br>• คำนวณชั่วโมงทำงานและ OT เปรียบเทียบกับเป้าหมายอัตโนมัติ พร้อมระบบสั่งพิมพ์รายงาน PDF | `React 19` `Vite` `Node.js` `Express 5` `PostgreSQL` `Recharts` | [🔗 View Repo](https://github.com/trpxmac/nurse-scheduling-mvp) |

---

### 👥 2. Team / Co-Developed Projects (พัฒนาร่วมกับทีมฝึกงาน)

| โครงการ (Project) | รายละเอียดและจุดเด่นของระบบ (Key Highlights) | Tech Stack | ลิงก์ (Links) |
| :--- | :--- | :--- | :---: |
| **5. BSI-Stock**<br>*(ระบบบริหารจัดการคลังเวชภัณฑ์และบาร์โค้ด)* | • ระบบจัดการสต็อกสินค้าและพัสดุ รองรับสินค้าหลายไซส์และหมวดหมู่<br>• สร้างและดาวน์โหลดบาร์โค้ดมาตรฐาน `CODE128` พร้อมระบบ **สแกนบาร์โค้ดผ่านกล้องมือถือ/เว็บแคม**<br>• แดชบอร์ดสรุปภาพรวมสต็อกรายวัน กราฟสัดส่วนสินค้า ระบบแจ้งเตือนเมื่อสินค้าใกล้หมด (`Low-Stock Threshold`) และส่งออกไฟล์ Excel | `React 19` `Vite` `Node.js` `Express 5` `PostgreSQL` `Chart.js` `JsBarcode` `html5-qrcode` `SheetJS` | [🔗 View Repo](https://github.com/FEEKNK/BSI-Stock)<br>[🌐 Live Demo](https://bsi-stock.vercel.app) |
| **6. HeightGrowthApp (GrowthFit)**<br>*(ระบบคัดกรองสมรรถภาพทางกายเพื่อกระตุ้นความสูงสำหรับเด็ก)* | • เว็บแอปพลิเคชันสำหรับคลินิกกายภาพบำบัดและเวชศาสตร์การกีฬา ประเมินสมรรถภาพทางกายเด็กตามเกณฑ์มาตรฐานทางคลินิก<br>• คำนวณอายุ/BMI และแบ่งกลุ่มบททดสอบอัตโนมัติ (กลุ่ม 4–6 ปี และ 7–14 ปี)<br>• แปลผลคะแนนเทียบค่ามาตรฐานตามช่วงอายุ-เพศ พร้อมออกรายงานสรุปผลในรูปแบบ **PDF Report (ฝังฟอนต์ไทย + QR Code)** | `JavaScript (ES6+)` `HTML5` `CSS3 (Glassmorphism)` `jsPDF` `Responsive UI` | [🔗 View Repo](https://github.com/FEEKNK/HeightGrowthApp) |

---

## 📌 Quick Links (รวมลิงก์โปรเจกต์ทั้งหมดสำหรับตรวจสอบโค้ด)

- 👤 **Solo Projects:**
  - 🏥 [https://github.com/trpxmac/cost-estimation-mvp](https://github.com/trpxmac/cost-estimation-mvp) — *Hospital Cost Estimation System*
  - 💬 [https://github.com/trpxmac/doctor-leave-line](https://github.com/trpxmac/doctor-leave-line) — *Doctor Leave @ LINE OA (LIFF & Admin Portal)*
  - ✍️ [https://github.com/trpxmac/ipad-document-sign](https://github.com/trpxmac/ipad-document-sign) — *iPad Document e-Sign Pipeline (HIS/EHR Integration)*
  - 📅 [https://github.com/trpxmac/nurse-scheduling-mvp](https://github.com/trpxmac/nurse-scheduling-mvp) — *Intelligent Nurse Roster & Shift Scheduling*
- 👥 **Team Projects:**
  - 📦 [https://github.com/FEEKNK/BSI-Stock](https://github.com/FEEKNK/BSI-Stock) — *Hospital Inventory & Barcode Management System*
  - 🏃 [https://github.com/FEEKNK/HeightGrowthApp](https://github.com/FEEKNK/HeightGrowthApp) — *GrowthFit: Kids Physical Fitness Screening System*
