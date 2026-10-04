<h1 align="center">⚙️ Ax3m-clay / Junior DevOps Engineer</h1>

<p align="center">
  <a href="https://github.com/Ax3m-clay">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=2EA043&center=true&vCenter=true&width=520&lines=Linux+%7C+Docker+%7C+CI%2FCD;Self-hosting+my+own+infrastructure;Fullstack+web+development;Open+to+work+%E2%80%94+Moscow+%2F+Remote" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-open%20to%20work-2ea043?style=flat-square" alt="open to work" />
  <img src="https://img.shields.io/badge/location-Moscow%20%7C%20Remote-1f6feb?style=flat-square" alt="location" />
  <img src="https://img.shields.io/badge/hh.ru%20verified-Docker%20%C2%B7%20API-d63384?style=flat-square" alt="verified skills" />
</p>

###

## 👋 About me

- 🛠️ Junior **DevOps engineer** and **fullstack web developer**
- 🖥️ I run my own homelab on **Proxmox**: Linux VMs, Docker services, automated deployments
- 🚀 I take projects all the way to production: containers, healthchecks, CI/CD
- 🌐 Built and launched websites for real clients — they are still online
- 📚 Next on my roadmap: Kubernetes

###

## 🧰 Tech stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=linux" height="40" alt="linux logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=debian" height="40" alt="debian logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=ubuntu" height="40" alt="ubuntu logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=docker" height="40" alt="docker logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=nginx" height="40" alt="nginx logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/proxmox/proxmox-original.svg" height="40" alt="proxmox logo" />
</div>

###

<div align="center">
  <img src="https://skillicons.dev/icons?i=git" height="40" alt="git logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=github" height="40" alt="github logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=githubactions" height="40" alt="github actions logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=py" height="40" alt="python logo" />
</div>

###

<div align="center">
  <img src="https://skillicons.dev/icons?i=html" height="40" alt="html logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=css" height="40" alt="css logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=js" height="40" alt="javascript logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=nextjs" height="40" alt="nextjs logo" />
</div>

###

## 📦 Featured projects

**🤖 autoschool-bot** — Telegram bot with a Mini App
`Python` `Docker` `Docker Compose` `GitHub Actions` `REST API` `SQLite`
- Containerized a Python service: non-root user, healthcheck, persistent volumes
- CI in GitHub Actions: code check, image build, container security check
- CD with a self-hosted runner: auto-deploy on push, waits for a healthy container, prints logs on failure
- Integrates external APIs (learning platform, LLM) and is exposed over HTTPS

**🏠 Proxmox homelab**
`Proxmox VE` `Debian` `Linux` `SSH` `Docker`
- Proxmox VE on a dedicated server with Debian 13 virtual machines
- Hardened host: separate admin user, SSH disabled on the hypervisor
- Playground for Docker, networking, NAT and CI/CD

**🔐 Self-hosted VPN server**
`Ubuntu Server` `Docker` `WireGuard` `AmneziaWG` `systemd`
- AmneziaWG, WireGuard and OpenVPN running in Docker on a VPS
- Diagnosed connection drops caused by DPI, moved traffic to UDP 443 with a custom systemd unit
- Tuned the kernel network stack (conntrack, UDP buffers) via sysctl
