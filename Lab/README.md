# `Lab/` — Lab ทั้งหมด

Lab ของรายวิชา **SC313302 Internetworking · Section 2**
นายธนภัทร สมบูรณ์ — รหัสนักศึกษา 663380347-5

ชื่อโฟลเดอร์ใช้รูปแบบ `LabNN - <หัวข้อ>` เติมเลข 0 ข้างหน้าเลขหลักเดียว เพื่อให้เรียงลำดับได้ถูกต้อง
รายวิชาเริ่มเก็บงาน Lab ตั้งแต่ Lab 3 จึงไม่มี `Lab01` และ `Lab02`

| โฟลเดอร์ | หัวข้อ | ไฟล์ภายใน |
|---|---|---|
| `Lab03 - Configure VLANs` | การกำหนดค่า VLAN | รายงาน `.pdf` + ภาพหน้าจอ 3 รูป |
| `Lab04 - Investigate STP Loop Prevention` | การป้องกัน Loop ด้วย Spanning Tree Protocol | รายงาน `.pdf` + ภาพหน้าจอ 5 รูป |
| `Lab05 - Configure a Wireless Network` | กำหนดค่า Wireless Router (WR) และ Access Point (AP) | รายงาน `.pdf` |
| `Lab06 - WLAN Configuration` | Home Wireless Router และเครือข่ายองค์กรที่จัดการผ่าน WLC (WPA2-Personal / WPA2-Enterprise) | รายงาน `.pdf` |
| `Lab07 - Explore a Wireless Network in Physical Mode` | สำรวจและกำหนดค่าเครือข่ายไร้สายของ XYZ Corporation ใน Physical Mode | รายงาน `.pdf` |
| `Lab08 - Basic Router Configuration Review` | กำหนดค่าพื้นฐานและ interface ของ Router R2 แล้วเชื่อมต่อด้วย SSH | รายงาน `.docx` |
| `Lab09 - IPv4 and IPv6 Static and Default Routes` | Static Route, Floating Static Route, Default Route และ Host Route ทั้ง IPv4 และ IPv6 | รายงาน `.docx` |
| `Lab10 - Modify Single-Area OSPFv2` | 2.4.11 — ปรับ Hello Timer / Dead Timer และ Bandwidth ของ OSPF | `.pka` + ภาพหน้าจอ 6 รูป + ใบงาน ILM `.pdf` + รายงาน `.docx` |
| `Lab11 - Propagate a Default Route in OSPFv2` | การประกาศ (propagate) Default Route ใน OSPFv2 | รายงาน `.pdf` |
| `Lab12 - Verify Single-Area OSPFv2` | ตรวจสอบสถานะ OSPF neighbor / route / process ID และเพิ่ม LAN ใหม่เข้าเครือข่าย | ใบงาน `12.1.pdf` + ภาพหน้าจอ 5 รูป + รายงาน `.docx` |
| `Lab13 - Single-Area OSPFv2 Configuration` | 2.7.1 — กำหนดค่า OSPFv2 แบบ Single-Area ทั้ง Point-to-Point และ Broadcast Multiaccess | `.pka` + ภาพหน้าจอ 3 รูป + รายงาน `.docx` |
| `Lab14 - WAN Concepts` | 7.6.1 — ประเภทของเครือข่าย WAN และทางเลือกการเชื่อมต่อฝั่งผู้บริโภค/ธุรกิจ | `.pka` + ภาพหน้าจอ 11 รูป + รายงาน `.docx` |
| `Lab15 - Back Up Configuration Files` | 10.6.10 — สำรองและกู้คืนไฟล์คอนฟิกกูเรชันผ่าน TFTP Server | `.pka` + ภาพหน้าจอ 2 รูป + รายงาน `.docx` |
| `Lab16 - Upgrade a Cisco IOS Image via TFTP` | 10.7.6 — ใช้ TFTP Server อัปเกรดและสำรอง Cisco IOS Image | `.pka` + ภาพหน้าจอ 4 รูป + รายงาน `.docx` + ใบงาน ILM `.docx` |
| `Lab17 - Configure CDP, LLDP, and NTP` | 10.8.1 — โพรโทคอลค้นหาอุปกรณ์ CDP / LLDP และการซิงโครไนซ์เวลาด้วย NTP | `.pka` + ภาพหน้าจอ 4 รูป + รายงาน `.docx` |
| `Lab18 - Compare Layer 2 and Layer 3 Devices` | 11.5.1 — เปรียบเทียบการทำงานของอุปกรณ์เครือข่ายชั้นที่ 2 และชั้นที่ 3 | `.pka` + ภาพหน้าจอ 3 รูป + รายงาน `.docx` |

## หมายเหตุเรื่องการจัดเรียง

ก่อนจัดเรียง ไฟล์ Lab 10, 12, 13, 14 อยู่ในโฟลเดอร์ที่ดาวน์โหลดมาจาก Google Drive ทั้งก้อน
(เช่น `Lab10-20260806T100832Z-1-001/Lab10/...`) ซึ่งมีโฟลเดอร์ซ้อนกันสองชั้นและมีไฟล์ของ Lab อื่นปนอยู่
จึงได้แกะชั้นที่ซ้อนออก ย้ายไฟล์เข้าโฟลเดอร์ Lab ที่ถูกต้อง และลบสำเนาที่ซ้ำกันออก

| ไฟล์/โฟลเดอร์เดิม | ผลลัพธ์ |
|---|---|
| `Lab10-20260806T100832Z-1-001/Lab10/` | → `Lab10 - Modify Single-Area OSPFv2/` |
| `Lab10-20260806T100832Z-1-001/OSPFv2_Report.docx` | → `Lab10 - Modify Single-Area OSPFv2/` |
| `Lab10-20260806T100832Z-1-001/Lab11/Lab11.docx.pdf` | ลบ (ซ้ำกับไฟล์ใน `Lab11 - Propagate a Default Route in OSPFv2/`) |
| `Lab11/Lab13-20260806T102722Z-1-001/` | ลบ (ซ้ำกับ `Lab13 - Single-Area OSPFv2 Configuration/`) |
| `Lab12-20260806T100931Z-1-001/` | → `Lab12 - Verify Single-Area OSPFv2/` |
| `Lab13-20260806T102722Z-1-001/` | → `Lab13 - Single-Area OSPFv2 Configuration/` |
| `Lab14-20260806T100939Z-1-001/` | → `Lab14 - WAN Concepts/` |

ไฟล์ที่ลบออกทุกไฟล์ตรวจสอบด้วย `md5sum` แล้วว่าเหมือนกับต้นฉบับทุกไบต์ และต้นฉบับยังอยู่ครบในโฟลเดอร์ Lab ของตัวเอง
