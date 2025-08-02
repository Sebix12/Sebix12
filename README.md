# Hi, I'm Sebastian 👋

I'm a full-stack developer, electrotechnician student, and infrastructure enthusiast based in Hungary. I build automation tools, bots, monitoring systems, and self-hosted services running on Proxmox, Debian, nginx, and low-level Linux.

---

## 🛠️ What I Do

- **GABS**: Creator of a real-time Discord moderation bot with an SQLite backend, live control panel, and modular plugin support.
- **Automation**: Develop advanced Windows batch scripts, perform penetration testing, and manage Minecraft servers, backups, and network infrastructure.
- **Homelab**: Operate a fully self-hosted infrastructure stack including servers, networking gear, and custom-built tools. It powers everything from game servers and Proxmox virtualization to audio routing and backups.

---

## 🖥️ My Setup

### PowerEdge R630 (Compute Node)

- Dual 14-core CPUs (28 threads each, 56 total)
- 32GB DDR4 ECC RAM
- Drives: 1TB SSD, 1TB HDD, 750GB HDD, 120GB SSD, 240GB SSD
- Runs Proxmox with Debian, Ubuntu, and Windows 10 VMs
- Handles all incoming requests, backend/frontend, and Minecraft computation
- Dual gateway connections + tunnel to backup

### IBM Server (Storage Node)

- 8-core CPU, 48GB DDR3 ECC RAM
- 3×1.8TB HDDs for storage + 1TB cache HDD
- Dual 60GB SAS RAID 1 boot drives
- Runs TrueNAS CORE with IPMI
- Handles storage, compression, and file management (~3.5TB)

### Networking & Integration

- 1Gbps direct link between servers for low-latency access
- PowerEdge routes to IBM for storage and redundancy
- Proven performance under 200+ player Minecraft load over 3 servers

---

## 🔧 Services & Automation

- Power Distribution Unit (custom-built)
- Backup portals with auto-generated index

Everything is scripted or automated where possible using Bash, Python, and systemd services. From nightly backups to dynamic DNS and Discord bot-based monitoring (like GABS), it's all designed to run hands-off.

---

## 📬 Let's Connect

- Email: [ghsebestyen@gmail.com](mailto:ghsebestyen@gmail.com)
- Discord: redactedofficial
- GitHub: [github.com/Sebix12](https://github.com/Sebix12)
- YouTube: [@redactedofficial](https://www.youtube.com/@redactedofficial)

Feel free to reach out for collaborations, questions, or just to say hi!

---


## 📈 Stats

![Sebi's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Sebix12&show_icons=true&hide_title=true&count_private=true&hide=prs&theme=radical)

---

Thanks for visiting my profile! 🚀
