# Travis Gadow

**AI Automation Engineer** · IT Operations · DialHaven · Relocating to Germany by December 2026

San Francisco Bay Area · travisgadow@pm.me · [LinkedIn](https://www.linkedin.com/in/travisgadow)

### Technical case study
[DialHaven: architecture, duplicate-callback debugging and operational safeguards](DialHaven-case-study.md). Sanitized September 2026 technical retrospective.

### What I build and run
- **DialHaven** (AI Automation Engineer): an AI phone receptionist I built and operate end to end.
  Twilio → voice bridge behind nginx on a Hetzner Ubuntu VPS (systemd, TLS, SSH keys) → n8n post-call workflows (summary, CRM log, e-mail + alerts).
  - Compared 5 backend-model candidates for a booking task, using measured latency, reliability and cost to guide selection.
  - Audited the whole pipeline in Sep 2026 and fixed 13 bugs from the logs (e.g. duplicate call processing → dedup by call ID).
  - Daily off-server backups with automated integrity checks; health checks with alerting.
  - I direct AI coding assistants for much of the code; architecture, testing, deployment and operations are mine.
- **Home lab:** self-built Ubuntu server with Docker, Tailscale mesh VPN, Pi-hole DNS, systemd services and local LLMs.
  Favorite fix: a service silently fell back from GPU to CPU (~10× slower) because it lacked device permissions; fixed with a system-wide systemd unit.

### Skills
Linux (Ubuntu/Debian) · systemd · Docker · nginx · SSH · Backup & restore · Networking (TCP/IP, DNS, DHCP, NAT, VLANs) · Windows 10/11 · Windows Server & AD (coursework) · n8n · Webhooks/REST · Twilio · Bash · Python · SQL · Git

### Education & certificates
- Las Positas College: Cybersecurity Professional program. Networking, Windows Server, Red Hat Linux, network security, Cisco CCNA 1 (25 of 37 units completed; certificate not completed; GPA 3.47)
- Google IT Support Professional Certificate ([Credly](https://www.credly.com/go/INgqkve6))
- Google Cybersecurity, Data Analytics, AI and Project Management Professional Certificates (Coursera, 2026)
- German: A2, B1 exam planned early 2027
