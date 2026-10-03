# 📊 MechLog: สรุปภาพรวมโครงการ ข้อมูลสถาปัตยกรรม และข้อกำหนดแดชบอร์ด (Project Specification & Dashboard Design Spec)

เอกสารฉบับนี้รวบรวมข้อมูลทั้งหมดของโครงการ **MechLog (AI-Powered Smart Maintenance Solution)** เพื่อใช้เป็นพิมพ์เขียว (Blueprint) ในการพัฒนาเว็บแอปพลิเคชัน แดชบอร์ดมอนิเตอร์ และระบบวิเคราะห์ข้อมูลตามหลักวิศวกรรมการบำรุงรักษาอุตสาหกรรม (Industrial Maintenance Engineering)

---

## 1. ข้อมูลสรุปของโครงการ (Project Overview)

* **ชื่อแบรนด์:** **MechLog** (MechLog Technologies / MechLog AI)
* **นิยาม/สโลแกน:** *"จดง่าย ถามคล่อง รู้ล่วงหน้าก่อนเครื่องพัง"* (Smart Logs. Smarter Maintenance.)
* **วิสัยทัศน์:** ยกระดับโรงงานไทยจาก "Breakdown Maintenance (รอพังแล้วค่อยซ่อม)" สู่ **"Predictive Maintenance & Smart Factory 4.0"** ด้วย AI ภาษาไทยที่เข้าใจงานช่างจริง
* **กลุ่มเป้าหมาย (Customer Segments):**
  1. โรงงานอุตสาหกรรมที่มีการนำเข้าเครื่องจักรหลากหลายยี่ห้อ (จีน, ญี่ปุ่น, ยุโรป, ไต้หวัน)
  2. โรงงานขนาดกลางและขนาดย่อม (SME) ที่ขาดแคลนช่างเทคนิคเฉพาะทาง
  3. โรงงานที่ต้องการยกระดับสู่ระบบอัตโนมัติและโรงงานอัจฉริยะ 4.0

---

## 2. การเชื่อมโยงทางธุรกิจ: 9 กล่อง BMC & 4P / 4M

### 2.1 4P Marketing Mix (หน้าบ้าน)
1. **Product:**
   * **Digital Maintenance Logbook:** บันทึกประวัติการซ่อมออนไลน์ ค้นหาย้อนหลังได้ ป้องกันความรู้หายเมื่อช่างลาออก
   * **AI Thai Assistant:** ค้นหาคำตอบจากคู่มือจริงและประวัติการซ่อม แปล Error Code เป็นวิธีแก้ไขภาษาไทยทันที
   * **Predictive AI Engine:** แจ้งเตือนความผิดปกติของอุณหภูมิ การสั่นสะเทือน หรือความถี่การทำงานก่อนเครื่องจักรพัง
2. **Price:**
   * *SaaS Subscription:* 4,000 – 40,000 บาท/เดือน (ขึ้นกับขนาดโรงงานและจำนวนเครื่องจักร)
   * *Implementation & Data Digitization:* 30,000 บาท (นำเข้าคู่มือและประวัติเก่า)
   * *System Integration (PLC/SCADA/IoT):* 30,000 – 100,000 บาท/โครงการ
   * *Custom Model & On-Premises:* 150,000 – 300,000 บาท
3. **Place:** Direct Sales สู่ผู้บริหารโรงงาน, สัมมนาผ่าน FTI/สมาคมอุตสาหกรรม, เครือข่ายตัวแทนจำหน่ายเครื่องจักร (Machine Distributors) และ System Integrators (SI)
4. **Promotion:** ทดลองใช้ฟรี 7 วัน (7-Day Free Trial), High-Touch Onboarding มีวิศวกรลงพื้นที่ฝึกอบรมช่างหน้างาน

### 2.2 4M Operations & Resources (หลังบ้าน)
1. **Man:** วิศวกร AI/ML, นักพัฒนาซอฟต์แวร์, วิศวกรผู้เชี่ยวชาญโรงงาน (Domain Expert) และช่างเทคนิคหน้างาน
2. **Machine/Tech:** GPU Cloud/Edge Computing Server (Advantech, Dell), โมเดล LLM ภาษาไทยสำหรับงานช่าง, สถาปัตยกรรม Prompt Engineering, ฐานข้อมูลคู่มือเครื่องจักร (Machinery Knowledge Base)
3. **Material:** เอกสารคู่มือ (PDF Manuals), Log ระบบ, สัญญาณเซนเซอร์ IoT/PLC/SCADA, มาตรฐานความปลอดภัยข้อมูล Data Residency ภายในประเทศไทย (PDPA)
4. **Method:** กระบวนการแปลงเอกสารกระดาษเป็นดิจิทัล (Digitization), การ Fine-tune โมเดล AI แบบ Human-in-the-loop, มาตรฐานการบำรุงรักษาแบบทวีผลที่ทุกคนมีส่วนร่วม (TPM)

---

## 3. Brand Identity & Design System (CI / UI Guidelines)

* **Logo Symbol:** โครงหัวน็อตหกเหลี่ยม (Hexagon Bolt) ผสานอักษร M และคลื่นสัญญาณเซนเซอร์ (Pulse Wave) พร้อมจุดเตือนสีส้ม
* **Base Color Theme:** พื้นสีขาวสะอาดตา (Clean Industrial White `#FFFFFF` / Slate Light `#F8FAFC`) พร้อมเส้นกริดวิศวกรรมบางๆ
* **Brand Primary Colors:**
  * `Primary Navy:` `#0A2268` (ความมั่นคง ปลอดภัยระดับองค์กร)
  * `Electric Cobalt:` `#1877F2` (ความแม่นยำทางเทคโนโลยี AI)
  * `Safety Amber / Alert Orange:` `#F77F00` (การแจ้งเตือนความเสี่ยง / Warning)
  * `Healthy Green:` `#10B981` (สถานะเครื่องจักรปกติ / Normal)
  * `Danger Red:` `#EF4444` (เครื่องจักรหยุดทำงาน / Breakdown Downtime)
* **Typography:** 
  * ภาษาไทย: **TH Sarabun PSK** หรือ **Sarabun** (เป็นทางการ อ่านง่าย ชัดเจน)
  * ภาษาอังกฤษและตัวเลข: **Urbanist** หรือ **Chakra Petch** (ทรงเหลี่ยม เรขาคณิต สไตล์ Tech)

---

## 4. โครงสร้างแดชบอร์ดและตัวชี้วัดสำคัญ (Key Performance Indicators - KPIs)

แดชบอร์ดของ MechLog ออกแบบตามหลัก **Total Productive Maintenance (TPM)** และ **Reliability Engineering** โดยแบ่งออกเป็น 4 มิติสำคัญ:

### 4.1 กลุ่มตัวชี้วัดความพร้อมของเครื่องจักร (Equipment Reliability & Availability)
1. **OEE (Overall Equipment Effectiveness) - ประสิทธิผลโดยรวมของเครื่องจักร:**
   $$\text{OEE} = \text{Availability (ความพร้อม)} \times \text{Performance (สมรรถนะ)} \times \text{Quality (คุณภาพ)}$$
   *ค่าเป้าหมายมาตรฐานสากล: $\ge 85\%$*
2. **MTBF (Mean Time Between Failures) - ระยะเวลาเฉลี่ยระหว่างการเสียแต่ละครั้ง:**
   $$\text{MTBF} = \frac{\text{เวลาทำงานรวมของเครื่องจักร (Operating Hours)}}{\text{จำนวนครั้งที่เครื่องพัง (Number of Failures)}}$$
   *ตัวชี้วัดความทนทานและความเสถียร ยิ่งค่าสูงยิ่งดี*
3. **MTTR (Mean Time To Repair) - ระยะเวลาเฉลี่ยในการซ่อมแซม:**
   $$\text{MTTR} = \frac{\text{เวลารวมที่ใช้ในการซ่อมบำรุง (Total Repair Time)}}{\text{จำนวนครั้งที่ซ่อม (Number of Repairs)}}$$
   *ตัวชี้วัดความเร็วของทีมช่างและ AI ยิ่งค่าต่ำยิ่งดี (เป้าหมาย: ลดลง 30–50% ด้วย AI Assistant)*
4. **Unplanned Downtime (ชั่วโมงการหยุดทำงานกะทันหัน):** 
   * จำนวนชั่วโมงที่ไลน์การผลิตหยุดชะงัก เปรียบเทียบกับมูลค่าความเสียหายเชิงเศรษฐศาสตร์ (ต้นทุนค่าแรง + โอกาสการผลิตที่สูญเปล่า)

### 4.2 กลุ่มตัวชี้วัดงานซ่อมบำรุงเชิงรุก (Maintenance Strategy Ratio)
1. **PM vs BM Ratio (อัตราส่วนการบำรุงรักษาเชิงป้องกัน ต่อ การซ่อมเมื่อพัง):**
   * เป้าหมายโรงงาน 4.0: การซ่อมเชิงป้องกัน (PM/PdM) $\ge 80\%$, การซ่อมฉุกเฉิน (BM) $\le 20\%$
2. **PM Compliance Rate (% ความสำเร็จตามแผนการซ่อมบำรุงประจำรอบ):**
   * วัดว่าช่างทำการตรวจสอบเช็กลิสต์ตามรอบเวลาครบถ้วนหรือไม่ (เป้าหมาย: $\ge 95\%$)

### 4.3 กลุ่มตัวชี้วัดประสิทธิภาพของ AI Assistant & การจัดการองค์ความรู้
1. **First-Time Fix Rate (FTFR):** อัตราการซ่อมสำเร็จตั้งแต่ครั้งแรกโดยไม่ต้องรอช่างจากภายนอก
2. **Average Diagnosis Time (ระยะเวลาในการวินิจฉัยปัญหา):** เวลาตั้งแต่พบ Error Code จนกระทั่งช่างค้นพบวิธีแก้ไขจากระบบ AI (เป้าหมาย: ลดจาก 2-4 ชั่วโมง เหลือต่ำกว่า 5 นาที)
3. **Knowledge Base Digitization Progress:** จำนวนคู่มือ (Manuals), สเปกชีต, และประวัติการซ่อมที่แปลงเป็นข้อมูลดิจิทัลพร้อมสืบค้น

### 4.4 กลุ่มตัวชี้วัดการประหยัดต้นทุนและความคุ้มค่า (Economic & ROI Impact)
1. **Estimated Cost Saved (มูลค่าต้นทุนที่ประหยัดได้):** คำนวณจาก Downtime ที่ลดลงได้ $\times$ มูลค่าความเสียหายต่อชั่วโมง
2. **Supplier Dependence Reduction:** ร้อยละของจำนวนครั้งที่แก้ไขปัญหาเครื่องจักรได้เองโดยไม่ต้องจ้าง Supplier ต่างประเทศ

---

## 5. การจัดวางหน้าจอ Mockup Web App (UI Component Layout)

แดชบอร์ด `index.html` ประกอบด้วย 6 องค์ประกอบหลัก:
1. **Header & Navigation Bar:** โลโก้ MechLog, ตัวเลือกสาขาโรงงาน (Line 1/Line 2), การค้นหาแบบอัจฉริยะ (AI Quick Search), และสถานะระบบ
2. **KPI Metrics Cards (Top Row):** 
   * Card 1: **OEE รวม** (เช่น 88.4% พร้อมแถบสีสถานะ)
   * Card 2: **MTBF & MTTR** (เช่น MTBF: 340 ชม. / MTTR: 32 นาที)
   * Card 3: **Unplanned Downtime เดือนนี้** (เช่น 4.2 ชม. ลดลง 45%)
   * Card 4: **ต้นทุนที่ประหยัดได้สะสม** (เช่น ฿420,000 บาท)
3. **Machine Status Grid (Real-time Factory Floor):** 
   * แสดงการ์ดเครื่องจักรแต่ละตัว (CNC Machine, Injection Molding, Robotic Arm, Air Compressor) 
   * ระบุแบรนด์ (Fanuc, Mitsubishi, Yaskawa, Siemens)
   * แสดงสถานะ: *ปกติ (Normal)*, *เตือนความเสี่ยง (Warning)*, *หยุดฉุกเฉิน (Downtime)*
4. **AI Assistant Interactive Module (กล่องถาม-ตอบช่างภาษาไทย):**
   * กล่องค้นหา Error Code (เช่น "Error 1042 แกน X ไม่ขยับ", "Alarm E-07 Overheat")
   * AI แนะนำวิธีแก้ปัญหาพร้อมอ้างอิงหน้าคู่มือจริงและบันทึกช่างรุ่นก่อน
5. **Maintenance Analytics & Charts:**
   * กราฟเปรียบเทียบ PM vs BM รายเดือน
   * กราฟแนวโน้ม Downtime ย้อนหลัง
6. **Recent Maintenance Logs & Activity Stream:**
   * ตารางประวัติงานซ่อมล่าสุด ช่างผู้รับผิดชอบ และสถานะการตรวจรับงานตามมาตรฐาน ISO/TPM

---
*เอกสารนี้ถูกเตรียมไว้ในไดเรกทอรี `Document/test_year/bmc_solo/README.md` และพร้อมสำหรับการนำไปต่อยอดเป็นระบบงานจริง*
