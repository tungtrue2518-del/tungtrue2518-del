# Hi, I'm Tung

IT Support in Thailand, hands-on first. Most of my day is spent with a screwdriver and a cable tester:
building PCs, running LAN cable, setting up the network and keeping printers, UPS and servers alive.

When a job keeps coming back as manual Excel work, I build a small tool for it.
I write those tools together with AI (Claude Code): I know the problem and the hardware,
the AI helps me turn it into working code, and I test everything in the real office before it goes live.

## What I do on site

- **PC & hardware:** assembling and upgrading PCs, troubleshooting, Windows setup and imaging, laptops, peripherals
- **Network:** LAN cabling and termination, patch panels, switches and Wi-Fi, IP address planning, finding who is on which IP
- **Printers & power:** network printers (toner, jams, SNMP monitoring), UPS checks and battery replacement
- **Servers & users:** file shares, NAS over SSH, user accounts, day-to-day helpdesk

## What I build (with AI)

- **Web apps:** Python (Flask) back end, plain JavaScript / HTML / CSS front end
- **Excel automation:** openpyxl, pywin32, keeping the original workbooks as the source of truth
- **Windows tooling:** PowerShell, Task Scheduler, Git and GitHub
- **Languages:** Thai, English, Japanese (basic)

## Projects

**[printer-monitor](https://github.com/tungtrue2518-del/printer-monitor)** (public)
Every network printer on one page: toner and paper, jams, pages printed per day and a toner run-out forecast.
Pure Python standard library, built-in SNMP client, English / Thai / Japanese.

**IT Register Manager** (private, in daily use)
An internal web app for our IT department, replacing hand-edited Excel registers.

- One site for consumables stock, equipment register, UPS battery schedule, IT requests, IP address plan and purchase documents
- Writes back into the original Excel files, so the workbooks stay the source of truth
- Live printer status: toner, paper trays, alerts and a toner run-out forecast
- Change history with real staff names, daily verified backups, a watchdog that restarts the server
- Thai / English / Japanese interface

---

Hardware first, code when it saves the team time.
