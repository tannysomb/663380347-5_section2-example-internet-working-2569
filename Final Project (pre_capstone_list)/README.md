# `Final Project (pre_capstone_list)/` — Final Project

นายธนภัทร สมบูรณ์ — รหัสนักศึกษา 663380347-5

โฟลเดอร์นี้เก็บ Final Project โดยโคลนตัวโปรเจกต์เข้ามาไว้ข้างในโดยตรง (ไม่ได้ใช้เพียงไฟล์ `.md` ที่มีลิงก์)

---

## 1. `Fabric Technologies/` — Final Project / Pre-Capstone ของรายวิชานี้

**SC313302 INTERNETWORKING · FABRIC TECHNOLOGIES**

การจำลองและนำเสนอการสื่อสารระหว่าง LAN สองฝั่งผ่าน **Underlay Network** และ **GRE Overlay Network**
พร้อมสาธิตผลกระทบเมื่อ Underlay ล่ม และขั้นตอนการตรวจสอบ/กู้คืน

**Topology** — `PC-A — Edge-1 — ISP — Edge-2 — PC-B` โดยมี GRE Tunnel เชื่อม Edge-1 กับ Edge-2 ผ่านเครือข่าย ISP

| ส่วน | รายละเอียด |
|---|---|
| Underlay | `10.0.12.0/30` (Edge-1 ↔ ISP) และ `10.0.23.0/30` (ISP ↔ Edge-2) |
| Overlay | GRE `Tunnel0` — `172.16.0.1/30` ↔ `172.16.0.2/30` |
| LAN-A / LAN-B | `192.168.10.0/24` / `192.168.20.0/24` |
| การจำลองความเสียหาย | ปิด interface `G0/1` บน Edge-1 → Traffic ผ่าน GRE Overlay ไปไม่ถึง PC-B |
| การกู้คืน | พบ interface `administratively down` → `no shutdown` → ตรวจสอบและ ping ซ้ำ |

**ไฟล์ภายใน**

| ไฟล์ | รายละเอียด |
|---|---|
| `Fabric_Technologies.pkt` | ไฟล์ Cisco Packet Tracer ของ Topology ที่ใช้ |
| `Fabric_Technologies_Presentation.pptx` | สไลด์นำเสนอ (ต้นฉบับ PowerPoint) |
| `Fabric_Technologies_Presentation.pdf` | สไลด์นำเสนอ (PDF) |
| `Fabric_Technologies_Summary_Notes.pdf` | สรุปแนวคิดและผลการจำลอง Underlay / GRE Overlay |
| `Fabric_Topology_Topology_.png` | ภาพ Topology |
| `CLI Verification.mp4` | วิดีโอสาธิตการตรวจสอบผ่าน CLI |

---

## 2. `Enhanced Task Manager CLI/` — Final Project ของรายวิชา CP352301 Script Programming

**Week 12: Final Project Development & Presentation** — Enhanced Task Manager CLI

> **ที่มา** — โฟลเดอร์นี้เดิมชื่อ `Lab 12 - Final Project Development` อยู่ที่ root ของ repository นี้
> เป็นงาน Final Project ของรายวิชา **CP352301 Script Programming** (ไม่ใช่รายวิชา Internetworking)
> ที่ถูกอัปโหลดมาไว้ที่นี่ จึงย้ายเข้ามาเก็บในโฟลเดอร์ Final Project และระบุที่มาไว้ให้ชัดเจน
> งานอื่น ๆ ของรายวิชานั้นอยู่ที่ [`Other Works/Script Programming (CP352301).md`](../Other%20Works/Script%20Programming%20(CP352301).md)

โปรแกรมบริหารจัดการรายการงานผ่าน Command-Line Interface เขียนด้วย Python เชิงวัตถุ
รองรับงาน 3 ชนิด (`Task`, `DueDateTask`, `PriorityTask`), ระบบ Tags, การค้นหา (Search),
การกรองหลายเงื่อนไข (Multi-criteria Filter), การจัดเรียง (Polymorphic Sort) และบันทึกข้อมูลเป็น JSON

**ไฟล์ภายใน**

| ไฟล์ / โฟลเดอร์ | รายละเอียด |
|---|---|
| `main.py` | จุดเริ่มต้นโปรแกรม |
| `src/cli_interface.py` | เมนู 10 ข้อ และการตรวจสอบอินพุต |
| `src/task_manager.py` | Business Logic — CRUD + Search / Filter / Sort |
| `src/data_persistence.py` | โหลด/บันทึก JSON ตามชนิดงาน |
| `src/task.py` | Domain Models — `Task` → `DueDateTask`, `PriorityTask` |
| `tests/test_task_manager.py` | ชุดทดสอบอัตโนมัติ 8 กรณี |
| `data/tasks.json` | ข้อมูลสาธิต 7 รายการ |
| `screenshots/` | ภาพหน้าจอผลการรัน 9 รูป |
| `README.md` | คำอธิบายโปรเจกต์และวิธีใช้งาน |
| `PLAN.md` | เอกสารออกแบบระบบ |
| `SUBMISSION_CHECKLIST.md` | รายการตรวจสอบก่อนส่งงาน |
| `00-สารบัญไฟล์.md` | สารบัญไฟล์ทั้งหมดในโฟลเดอร์ |
| `รายงาน Lab 12 - Final Project Development.docx` | รายงานฉบับเต็ม |
| `โจทย์แลป - Week 12 Final Project Development.docx` | เอกสารโจทย์ต้นฉบับ |

**วิธีรัน**

```bash
cd "Final Project (pre_capstone_list)/Enhanced Task Manager CLI"
python main.py
python -m unittest discover -s tests
```
