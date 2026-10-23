# 663380347-5_section2-example-internet-working-2569

รวมงานทั้งหมดของรายวิชา **SC313302 Internetworking · Section 2** (ปีการศึกษา 2569)

|  |  |
|---|---|
| **ผู้จัดทำ** | นายธนภัทร สมบูรณ์ |
| **รหัสนักศึกษา** | 663380347-5 |
| **รายวิชา** | SC313302 Internetworking · Section 2 |
| **คณะ/มหาวิทยาลัย** | คณะวิทยาศาสตร์ มหาวิทยาลัยขอนแก่น |

---

## โครงสร้างโฟลเดอร์

```
663380347-5_section2-example-internet-working-2569/
├── Lab/                               ← Lab ทั้งหมด (Lab03 – Lab18)
├── Final Project (pre_capstone_list)/ ← Final Project / Pre-Capstone
├── Certificate/                       ← ใบ Certificate จาก netacad.com
├── Other Works/                       ← ไฟล์ .md + ลิงก์ไปยังงานที่อยู่ใน repository อื่น
└── README.md                          ← ไฟล์นี้
```

ทุกโฟลเดอร์หลักมี `README.md` ของตัวเองอธิบายรายละเอียดภายในอีกชั้นหนึ่ง

---

## 1. `Lab/` — Lab ทั้งหมด

Lab ของรายวิชาทั้งหมดอยู่ในโฟลเดอร์นี้ ตั้งชื่อเป็น `LabNN - <หัวข้อ>` โดยเติมเลข 0 ข้างหน้า
(`Lab03` ไม่ใช่ `Lab3`) เพื่อให้ GitHub เรียงลำดับตามเลข Lab ได้ถูกต้อง

| โฟลเดอร์ | Packet Tracer / หัวข้อ |
|---|---|
| [`Lab03 - Configure VLANs`](Lab/Lab03%20-%20Configure%20VLANs) | การกำหนดค่า VLAN |
| [`Lab04 - Investigate STP Loop Prevention`](Lab/Lab04%20-%20Investigate%20STP%20Loop%20Prevention) | การป้องกัน Loop ด้วย STP |
| [`Lab05 - Configure a Wireless Network`](Lab/Lab05%20-%20Configure%20a%20Wireless%20Network) | กำหนดค่า Wireless Router และ Access Point |
| [`Lab06 - WLAN Configuration`](Lab/Lab06%20-%20WLAN%20Configuration) | Home Router และ WLC (WPA2-Personal / WPA2-Enterprise) |
| [`Lab07 - Explore a Wireless Network in Physical Mode`](Lab/Lab07%20-%20Explore%20a%20Wireless%20Network%20in%20Physical%20Mode) | สำรวจเครือข่ายไร้สายใน Physical Mode (XYZ Corporation) |
| [`Lab08 - Basic Router Configuration Review`](Lab/Lab08%20-%20Basic%20Router%20Configuration%20Review) | กำหนดค่าพื้นฐานของ Router และเชื่อมต่อด้วย SSH |
| [`Lab09 - IPv4 and IPv6 Static and Default Routes`](Lab/Lab09%20-%20IPv4%20and%20IPv6%20Static%20and%20Default%20Routes) | Static / Floating Static / Default / Host Route |
| [`Lab10 - Modify Single-Area OSPFv2`](Lab/Lab10%20-%20Modify%20Single-Area%20OSPFv2) | 2.4.11 — ปรับ Hello/Dead Timer และ Bandwidth ของ OSPF |
| [`Lab11 - Propagate a Default Route in OSPFv2`](Lab/Lab11%20-%20Propagate%20a%20Default%20Route%20in%20OSPFv2) | การประกาศ Default Route ใน OSPFv2 |
| [`Lab12 - Verify Single-Area OSPFv2`](Lab/Lab12%20-%20Verify%20Single-Area%20OSPFv2) | ตรวจสอบ OSPF neighbor / route และเพิ่ม LAN ใหม่ |
| [`Lab13 - Single-Area OSPFv2 Configuration`](Lab/Lab13%20-%20Single-Area%20OSPFv2%20Configuration) | 2.7.1 — กำหนดค่า OSPFv2 แบบ Single-Area |
| [`Lab14 - WAN Concepts`](Lab/Lab14%20-%20WAN%20Concepts) | 7.6.1 — แนวคิดและประเภทของเครือข่าย WAN |
| [`Lab15 - Back Up Configuration Files`](Lab/Lab15%20-%20Back%20Up%20Configuration%20Files) | 10.6.10 — สำรอง/กู้คืนไฟล์คอนฟิกผ่าน TFTP |
| [`Lab16 - Upgrade a Cisco IOS Image via TFTP`](Lab/Lab16%20-%20Upgrade%20a%20Cisco%20IOS%20Image%20via%20TFTP) | 10.7.6 — ใช้ TFTP Server อัปเกรด Cisco IOS Image |
| [`Lab17 - Configure CDP, LLDP, and NTP`](Lab/Lab17%20-%20Configure%20CDP,%20LLDP,%20and%20NTP) | 10.8.1 — CDP / LLDP และการซิงโครไนซ์เวลาด้วย NTP |
| [`Lab18 - Compare Layer 2 and Layer 3 Devices`](Lab/Lab18%20-%20Compare%20Layer%202%20and%20Layer%203%20Devices) | 11.5.1 — เปรียบเทียบอุปกรณ์ Layer 2 กับ Layer 3 |

> **หมายเหตุ** — Lab ของรายวิชานี้เริ่มเก็บคะแนนตั้งแต่ Lab 3 จึงไม่มีโฟลเดอร์ `Lab01` และ `Lab02`

รายละเอียดไฟล์ภายในแต่ละ Lab ดูได้ที่ [`Lab/README.md`](Lab/README.md)

---

## 2. `Final Project (pre_capstone_list)/` — Final Project

| โฟลเดอร์ | งาน |
|---|---|
| [`Fabric Technologies`](Final%20Project%20(pre_capstone_list)/Fabric%20Technologies) | **Final Project / Pre-Capstone ของรายวิชานี้** — Underlay / GRE Overlay (Fabric Technologies) พร้อมไฟล์ Packet Tracer, สไลด์นำเสนอ, Summary Notes และวิดีโอสาธิต CLI |
| [`Enhanced Task Manager CLI`](Final%20Project%20(pre_capstone_list)/Enhanced%20Task%20Manager%20CLI) | Final Project Development (Week 12) ของรายวิชา **CP352301 Script Programming** — โปรแกรม Task Manager แบบ CLI เชิงวัตถุ พร้อมรายงานและ Unit Test |

โปรเจกต์ถูกโคลนเข้ามาไว้ในโฟลเดอร์นี้โดยตรงทั้งสองตัว ไม่ได้ใช้เพียงลิงก์
รายละเอียดดูได้ที่ [`Final Project (pre_capstone_list)/README.md`](Final%20Project%20(pre_capstone_list)/README.md)

---

## 3. `Certificate/` — ใบ Certificate จาก netacad

| ไฟล์ | หลักสูตร |
|---|---|
| `CCNA - Switching, Routing, and Wireless Essentials.pdf` | **CCNA: Switching, Routing, and Wireless Essentials** — ตรงกับรายวิชานี้ |
| `Python Essentials 1.pdf` / `.png` | Python Essentials 1 — จากรายวิชา CP352301 Script Programming |

ทั้งสองใบออกโดย [netacad.com](https://www.netacad.com/) ในชื่อ `thanapat-somb-kkumail-com`
รายละเอียดดูได้ที่ [`Certificate/README.md`](Certificate/README.md)

---

## 4. `Other Works/` — งานที่อยู่ใน repository อื่น

งานบางส่วนเป็นงานกลุ่มหรือเป็นของรายวิชาอื่นที่อยู่ใน repository อื่น จึงไม่ได้โคลนเข้ามา
แต่ทำเป็นไฟล์ `.md` ที่มีลิงก์ไปยังงานนั้น ๆ ตามทางเลือกที่โจทย์อนุญาต

| ไฟล์ | งาน |
|---|---|
| [`Script Programming (CP352301).md`](Other%20Works/Script%20Programming%20(CP352301).md) | รายวิชา CP352301 Script Programming — Lab ประจำสัปดาห์, LabX Basic/Advance, Mini Project (G06) และ Final Project (G11) |
| [`Web App Lab.md`](Other%20Works/Web%20App%20Lab.md) | Web-app-lab — Lab เว็บแอปพลิเคชันด้วย Laravel |

---

## สรุปความต่างจากโครงสร้างที่กำหนด

โครงสร้างในที่นี้ทำตามที่โจทย์กำหนดครบทั้ง 4 ข้อ โดยมีรายละเอียดเพิ่มเติมดังนี้

| หัวข้อ | รายละเอียด |
|---|---|
| ชื่อโฟลเดอร์ย่อยใน `Lab/` | ใช้รูปแบบ `LabNN - <หัวข้อ>` เติมเลข 0 ข้างหน้าเลขหลักเดียว เพื่อให้เรียงลำดับถูกต้องและอ่านหัวข้อได้จากชื่อโฟลเดอร์ |
| ไม่มี `Lab01` – `Lab02` | รายวิชาเริ่มเก็บงาน Lab ตั้งแต่ Lab 3 |
| โฟลเดอร์ `drive-download-...` และ `LabNN-2026...-1-001` เดิม | เป็นโฟลเดอร์ที่ดาวน์โหลดมาจาก Google Drive ทั้งก้อน ได้แกะชั้นที่ซ้อนกันออกและย้ายไฟล์เข้าโฟลเดอร์ Lab ที่ถูกต้องแล้ว |
| ไฟล์ซ้ำที่ลบออก | `Lab10-.../Lab11/Lab11.docx.pdf` (ซ้ำกับ Lab 11) และ `Lab11/Lab13-.../` (ซ้ำกับ Lab 13) — ตรวจแล้วว่าไฟล์เหมือนกันทุกไบต์ (md5 ตรงกัน) ต้นฉบับยังอยู่ครบในโฟลเดอร์ Lab ของตัวเอง |
| `Certificate/` | มี certificate จาก netacad 2 ใบ ใบของรายวิชานี้คือ **CCNA: Switching, Routing, and Wireless Essentials** |
| `Enhanced Task Manager CLI` ใน `Final Project (pre_capstone_list)/` | เดิมชื่อโฟลเดอร์ `Lab 12 - Final Project Development` อยู่ที่ root ของ repository นี้ เป็นงาน Final Project ของรายวิชา CP352301 Script Programming ที่อัปโหลดมาไว้ที่นี่ จึงเก็บไว้ในโฟลเดอร์ Final Project และระบุที่มาให้ชัดเจน |
| `Other Works/` | โฟลเดอร์เพิ่มเติมที่ไม่ได้อยู่ในโจทย์ ใช้เก็บไฟล์ `.md` ที่ลิงก์ไปยังงานใน repository อื่น (งานกลุ่มและรายวิชาอื่น) ตามทางเลือกที่โจทย์อนุญาต |
