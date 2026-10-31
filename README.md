# Hi, I'm Tung

IT Support in Thailand who also writes software for the team.
I keep the office running (servers, NAS, network, PCs), and when a job keeps coming back
as manual Excel work, I turn it into a small web app.

I build those tools together with AI (Claude Code): I bring the problem, the data and the hardware,
the AI helps me turn it into working code, and I test everything in the real office before it goes live.
I enjoy learning new things and try to pick up one new skill with every project.

## What I build

- **Web apps:** Python (Flask) back end, REST APIs, plain JavaScript / HTML / CSS front end, dark and light themes
- **Excel automation:** openpyxl and pywin32, writing back into the original workbooks so they stay the source of truth
- **Network tooling:** SNMP client for printers, IP address scanning and mapping, SSH file browser for the NAS (paramiko)
- **Reliability:** change history, daily verified backups, a watchdog that restarts the server, smoke tests before each deploy
- **Workflow:** Git and GitHub (branches, pull requests, reviews), PowerShell, Windows Task Scheduler
- **Languages:** Thai, English, Japanese (basic)

## Servers and NAS

- Synology NAS: shared folders, permissions, user accounts
- Restoring deleted or overwritten files from **Snapshot Replication**
- Backup jobs and restores with **Hyper Backup**
- File shares, access over SSH, day-to-day server checks

## Hardware and network

- Repairing desktop PCs and laptops: diagnosing faults and replacing parts (RAM, SSD / HDD, power supply, screen, keyboard, battery)
- PC assembly and upgrades, Windows setup and imaging, peripherals
- LAN cabling and termination, patch panels, switches and Wi-Fi, IP address planning
- Network printers (toner, jams, monitoring), UPS checks and battery replacement

## Currently learning

- **Docker:** packaging my apps so they are easy to deploy and move between servers
- **Databases (SQL):** designing tables and queries, so my apps can grow beyond Excel files

## Projects

**[printer-monitor](https://github.com/tungtrue2518-del/printer-monitor)** (public)
Every network printer on one page: toner and paper, jams, pages printed per day and a toner run-out forecast.
Pure Python standard library, built-in SNMP client, English / Thai / Japanese.

**IT Register Manager** (private, in daily use)
An internal web app for our IT department, replacing hand-edited Excel registers.

- One site for consumables stock, equipment register, UPS battery schedule, IT requests, IP address plan and purchase documents
- Writes back into the original Excel files, so the workbooks stay the source of truth
- Live printer status with usage history and a toner run-out forecast
- IP address map with network scan and next free IPs
- SSH tools to browse, search and copy files on the NAS from the browser
- Change history with real staff names, daily verified backups, a watchdog that restarts the server

---

## ภาษาไทย

สวัสดีครับ ผมชื่อตัง ทำงานด้าน IT Support ในประเทศไทย
มีหน้าที่ดูแลระบบภายในสำนักงาน ได้แก่ เซิร์ฟเวอร์ NAS ระบบเครือข่าย และเครื่องคอมพิวเตอร์
และพัฒนาเครื่องมือขนาดเล็กเพื่อลดงานที่ต้องทำด้วยมือซ้ำ ๆ ใน Excel

ผมพัฒนาโปรแกรมร่วมกับ AI (Claude Code) โดยผมเป็นผู้กำหนดปัญหา ข้อมูล และอุปกรณ์ที่เกี่ยวข้อง
AI ช่วยแปลงแนวคิดเป็นโค้ดที่ใช้งานได้ และผมทดสอบทุกอย่างในสภาพแวดล้อมจริงก่อนนำขึ้นใช้งาน
ผมสนใจเรียนรู้สิ่งใหม่อยู่เสมอ และตั้งใจพัฒนาทักษะใหม่อย่างน้อยหนึ่งด้านในทุกโปรเจกต์

**งานพัฒนาโปรแกรม**
- เว็บแอปพลิเคชันด้วย Python (Flask) และ JavaScript / HTML / CSS
- ระบบอัตโนมัติสำหรับไฟล์ Excel โดยบันทึกกลับลงไฟล์ต้นฉบับ
- เครื่องมือด้านเครือข่าย เช่น ตรวจสถานะเครื่องพิมพ์ผ่าน SNMP แผนผัง IP Address และการจัดการไฟล์บน NAS ผ่าน SSH
- ระบบสำรองข้อมูลรายวันพร้อมตรวจสอบความถูกต้อง และระบบเฝ้าระวังที่รีสตาร์ทเซิร์ฟเวอร์อัตโนมัติ

**งานดูแลเซิร์ฟเวอร์และ NAS**
- บริหารจัดการ Synology NAS ทั้งโฟลเดอร์แชร์ สิทธิ์การเข้าถึง และบัญชีผู้ใช้
- กู้คืนไฟล์ที่ถูกลบหรือถูกเขียนทับผ่าน Snapshot Replication
- ตั้งค่างานสำรองข้อมูลและกู้คืนข้อมูลด้วย Hyper Backup

**งานฮาร์ดแวร์และเครือข่าย**
- ซ่อมคอมพิวเตอร์ตั้งโต๊ะและโน้ตบุ๊ก ตรวจหาสาเหตุอาการเสีย และเปลี่ยนอะไหล่ เช่น RAM, SSD / HDD, Power Supply, จอ, คีย์บอร์ด และแบตเตอรี่
- ประกอบและอัปเกรดคอมพิวเตอร์ ติดตั้งระบบปฏิบัติการ Windows
- เดินสาย LAN เข้าหัว Patch Panel ตั้งค่า Switch และ Wi-Fi วางแผน IP Address
- ดูแลเครื่องพิมพ์เครือข่ายและเครื่องสำรองไฟ (UPS)

**สิ่งที่กำลังเรียนรู้**
- Docker สำหรับจัดแพ็กเกจโปรแกรม เพื่อให้ติดตั้งและย้ายระหว่างเซิร์ฟเวอร์ได้สะดวก
- ฐานข้อมูล (SQL) การออกแบบตารางและการเขียนคำสั่งค้นหา เพื่อให้ระบบรองรับข้อมูลได้มากกว่าไฟล์ Excel

---

Code when it saves the team time, hardware when it needs hands.
