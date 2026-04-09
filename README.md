# Jiraporn Portfolio

---

# FIIT: Second-Hand Fashion Platform

## Project Overview
ระบบโมบายแอปพลิเคชันที่เป็นสื่อกลางการซื้อขายสินค้าแฟชันมือสอง  
โดยมุ่งเน้นการแก้ไขปัญหาความยุ่งยากในการเลือกซื้อ และความกังวลเรื่องคุณภาพสินค้า

---

## Business Analyst Role & Responsibilities
ในฐานะ Business Analyst ดิฉันดูแลรับผิดชอบตั้งแต่การรวบรวมความต้องการไปจนถึงการส่งมอบระบบ (Full SDLC):

* **Requirement Engineering:** ดำเนินการสัมภาษณ์เชิงลึก (User Interviews) และจัดทำ Journey Mapping เพื่อระบุ Pain Points 
* **Backlog Management:** แปลงข้อมูลเชิงคุณภาพ (Qualitative Insights) ให้เป็น **MVP Backlog** และเขียน **User Stories** เพื่อใช้ในการพัฒนา 
* **System Design:** ออกแบบโครงสร้างฐานข้อมูลเชิงสัมพันธ์ (**ERD**) สำหรับการลงประกาศสินค้าและระบบยืนยันตัวตนผู้ขาย เพื่อความโปร่งใส 
* **Technical Bridging:** พัฒนา High-fidelity Prototyping ผ่าน **Figma** และเขียน Front-end ส่วนหนึ่งด้วย **Svelte** 

## Problem Statement

จากการวิเคราะห์พฤติกรรมผู้บริโภคผ่านการสัมภาษณ์เชิงลึกและการสำรวจ พบปัญหาหลักในตลาดสินค้ามือสองดังนี้:

**Trust & Security**  
ความกังวลเรื่องการโดนโกงและสุขอนามัยของสินค้า  

**Time-Consuming**  
ผู้ซื้อไม่มีเวลาไปเลือกซื้อด้วยตัวเองหรือรอคิว CF สินค้า  

**Sizing Issues**  
ปัญหาเรื่องไซส์สินค้าที่ไม่ตรงตามจริงหรือไม่ชัดเจน  

---

## Persona

**Target Group**  
กลุ่มคนอายุ 18–22 ปี รายได้ 5,000 – 10,000 บาท  

**Characteristics**  
มองหาเสื้อผ้าที่สะท้อนตัวตนในราคาคุ้มค่า  
ชอบมีส่วนร่วมกับคอมมูนิตี้แฟชัน  
ไม่ชอบวิธีการสั่งซื้อที่ยุ่งยาก  

**Pain Points**  
ไม่มีเวลาไปซื้อเอง  
กังวลเรื่องความสะอาด  
เบื่อขั้นตอนการสั่งซื้อที่ซับซ้อน  

---

## User Flow

1. **Onboarding**  
   ผู้ใช้เข้าสู่ระบบและระบุความสนใจ เพื่อรับการแนะนำสินค้าที่ตรงใจ  

2. **Browsing & Discovery**  
   ค้นหาสินค้าผ่านระบบ Smart Filter  
   (แยกตามหมวดหมู่ แบรนด์ และสภาพสินค้า)  

3. **Engagement**  
   ตรวจสอบรายละเอียดสินค้าผ่านภาพถ่ายและคำอธิบาย  
   รวมถึงการรีวิวจากผู้ซื้อคนอื่น  

4. **Seamless Transaction**  
   สั่งซื้อและชำระเงินผ่านระบบที่ปลอดภัย  
   พร้อมติดตามสถานะการจัดส่งสินค้าได้ทันที  

---

## Design Decisions

**Trust-Building Features**  
เพิ่มระบบการยืนยันตัวตนของผู้ขาย และระบบ Rating  
เพื่อลดความเสี่ยงจากการโดนโกง  

**Simplified UI**  
ออกแบบหน้าจอให้ใช้งานง่าย (User-Friendly)  
เพื่อลดความยุ่งยากในขั้นตอนการ CF หรือซื้อสินค้า  

**Data-Driven Requirements**  
ออกแบบโครงสร้างฐานข้อมูล (Database Schema)  
ที่รองรับการจัดการ Order, Shipment  
และการสื่อสารระหว่างผู้ซื้อ–ผู้ขาย (Chat System) อย่างเป็นระบบ  

---

## Business Model Insights

**Value Propositions**  
ระบบที่โปร่งใส ตรวจสอบได้ และช่วยประหยัดเวลา  

**Key Activities**  
การพัฒนาแพลตฟอร์ม และการทำกิจกรรมทางการตลาดเพื่อสร้างคอมมูนิตี้  

**Revenue Streams**  
- ค่าธรรมเนียมการขาย (Commission)  
- ค่าบริการดันโพสต์ (Promoted Posts)  
- ค่าโฆษณา (Advertising)  

---
## Technical Stack & Skills Applied
* **Documentation:** Requirement Elicitation  
* **Design & Dev:** Figma, Svelte 
* **Data:** Relational Database Design 
## Prototype
(https://www.figma.com/proto/aNdXdOhom009ph02EJZgPD/Untitled?node-id=0-1&t=N0isE5kT7y257Od0-1)
