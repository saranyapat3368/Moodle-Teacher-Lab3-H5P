# 🐳 Lab: H5P Interactive Content ใน Moodle
## หัวข้อ: Docker · GitHub Actions · CI/CD · YAML

[![Moodle](https://img.shields.io/badge/Moodle-4.5.8-orange?logo=moodle)](https://moodle.org)
[![H5P](https://img.shields.io/badge/H5P-Interactive%20Content-blue)](https://h5p.org)
[![Docker](https://img.shields.io/badge/Docker-Container-2496ED?logo=docker)](https://docker.com)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-CI%2FCD-2088FF?logo=github-actions)](https://github.com/features/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> ใบงานการทดลองสำหรับการสร้างสื่อการสอนแบบ Interactive ด้วย H5P บน Moodle LMS  
> เนื้อหาเน้นการพัฒนาซอฟต์แวร์สมัยใหม่ด้วย Docker, GitHub Actions, CI/CD Pipeline และ YAML  
> สำหรับนักศึกษาสาขาวิทยาการคอมพิวเตอร์, เทคโนโลยีสารสนเทศ และสาขาที่เกี่ยวข้อง

---

## 📁 โครงสร้างไฟล์

```
h5p-devops-lab/
├── README.md              ← ไฟล์นี้ (คำแนะนำภาพรวม)
├── LAB_H5P_Moodle.md      ← ใบงานหลัก (ขั้นตอนละเอียด)
└── PEER_ASSESSMENT.md     ← แบบฟอร์ม Peer Assessment
```

---

## 🎯 วัตถุประสงค์การเรียนรู้

หลังจากทำใบงานนี้แล้ว นักศึกษาสามารถ:

1. สร้างสื่อ Interactive ด้วย H5P ได้ 6 ประเภทบน Moodle
2. อธิบายแนวคิด Docker, CI/CD, GitHub Actions และ YAML ผ่านสื่อที่สร้าง
3. ออกแบบ Branching Scenario สำหรับสถานการณ์แก้ปัญหา CI/CD จริง
4. เชื่อมต่อ H5P Activity กับ Moodle Gradebook ได้ถูกต้อง

---

## 📋 ประเภท H5P ในใบงานนี้

| ส่วน | ประเภท H5P | หัวข้อเนื้อหา | คะแนน | ความยาก |
|------|-----------|-------------|-------|---------|
| 1 | **Interactive Video** | Docker Container Basics | 10 | ⭐⭐⭐ |
| 2 | **Drag and Drop** | YAML Structure Mapping | 10 | ⭐⭐⭐ |
| 3 | **Fill in the Blanks** | Docker & docker-compose Commands | 5 | ⭐⭐ |
| 4 | **Branching Scenario** | Debug a Failed CI/CD Pipeline | 15 | ⭐⭐⭐⭐ |
| 5 | **Mark the Words** | Dockerfile Instruction Keywords | 5 | ⭐⭐ |
| 6 | **Sort the Paragraphs** | CI/CD Pipeline Steps | 5 | ⭐⭐ |
| | **รวม** | | **50** | |

---

## 🔧 ความต้องการของระบบ

| รายการ | ข้อกำหนด |
|--------|---------|
| Moodle Version | 4.x ขึ้นไป |
| Plugin H5P | ติดตั้งแล้ว (Admin โหลด Content Types ก่อน) |
| เบราว์เซอร์ | Chrome / Firefox / Edge (เวอร์ชันล่าสุด) |
| สิทธิ์ผู้ใช้ | Teacher หรือ Course Creator |
| ความรู้พื้นฐาน | Docker เบื้องต้น, Git, Command Line |

---

## ⏱️ เวลาที่ใช้

| ช่วง | กิจกรรม | เวลา |
|------|---------|------|
| ภาคทฤษฎี | บรรยาย + สาธิต Docker & CI/CD Overview | 30 นาที |
| ส่วนที่ 1 | Interactive Video | 20 นาที |
| ส่วนที่ 2 | Drag and Drop | 20 นาที |
| ส่วนที่ 3 | Fill in the Blanks | 15 นาที |
| ส่วนที่ 4 | Branching Scenario | 40 นาที |
| ส่วนที่ 5 | Mark the Words | 15 นาที |
| ส่วนที่ 6 | Sort the Paragraphs | 15 นาที |
| ประเมินผล | Peer Assessment | 20 นาที |
| **รวม** | | **~175 นาที (≈ 3 ชม.)** |

---

## 📊 เกณฑ์การประเมิน

```
คะแนนรวม 50 คะแนน

ส่วนที่ 1: Interactive Video        10 คะแนน
ส่วนที่ 2: Drag and Drop            10 คะแนน
ส่วนที่ 3: Fill in the Blanks        5 คะแนน
ส่วนที่ 4: Branching Scenario       15 คะแนน
ส่วนที่ 5: Mark the Words            5 คะแนน
ส่วนที่ 6: Sort the Paragraphs       5 คะแนน
```

---

## 🚀 วิธีเริ่มต้น

1. **Admin** ติดตั้ง H5P Plugin และโหลด Content Types ที่จำเป็นก่อน
2. **อ่าน** `LAB_H5P_Moodle.md` ให้ครบก่อนเริ่มปฏิบัติ
3. **ทบทวน** ความรู้พื้นฐาน Docker และ GitHub Actions
4. **เข้าสู่ระบบ** Moodle ด้วยบัญชี Teacher
5. **ทำตามขั้นตอน** ทีละส่วน ถ่าย Screenshot เป็นหลักฐาน
6. **ส่ง Peer Assessment** เมื่อเพื่อนในกลุ่มเสร็จงาน

---

## 📎 แหล่งเรียนรู้เพิ่มเติม

| หัวข้อ | แหล่งอ้างอิง |
|--------|-------------|
| H5P Documentation | https://h5p.org/documentation |
| GitHub Actions Docs | https://docs.github.com/en/actions |
| Docker Documentation | https://docs.docker.com |
| Docker Curriculum | https://docker-curriculum.com |
| pytest Documentation | https://pytest.org |
| YAML Specification | https://yaml.org/spec |
| DevOps Roadmap | https://roadmap.sh/devops |

---

## 👥 ผู้จัดทำ

- **วิชา**: 
- **สถาบัน**: สถาบันเทคโนโลยีพระจอมเกล้าเจ้าคุณทหารลาดกระบัง
- **ผู้สอน**: สุระชัย พิมพ์สาลี
- **ภาคการศึกษา**: 2/2568

---

## 📝 License

MIT License — สามารถนำไปใช้และดัดแปลงเพื่อการศึกษาได้อย่างอิสระ
