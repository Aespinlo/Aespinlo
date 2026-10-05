<!-- ============================================================
  REPLACE BEFORE PUBLISHING:
  - YOUR_GITHUB_USER  -> your GitHub username
  - YOUR_LINKEDIN_SLUG -> your LinkedIn profile slug
  Delete any line you can't back up in an interview.
============================================================ -->

<div align="center">

# Hi, I'm Andrés Espinel 👋

### Telecommunications Engineer · IIoT & Telemetry · Cloud Infrastructure

*I build the full path from the sensor to the dashboard, and keep the infrastructure underneath it reliable.*

<br>

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

<br>

📍 Valladolid, Spain &nbsp;·&nbsp; 🌍 Open to remote (EU / international) &nbsp;·&nbsp; 🗣️ English B2 · Spanish (native)

</div>

---

## 👨‍💻 About Me

I'm a Telecommunications Engineer (Telematics) from the **University of Valladolid**. At **NTT DATA** I work on critical infrastructure for **Telefónica** and **Cepsa/Moeve**: Linux, VMware vSphere, VLAN-isolated networks, patching, and backup & disaster recovery with NetBackup.

Outside work, I design telemetry and automation systems end to end: MQTT brokers, time-series databases, real-time dashboards, containers and Kubernetes labs. What I enjoy most is turning raw data from the physical world into something observable, secure and dependable.

**What I'm looking for:** industrial digitalization, sensor and telemetry projects, and data-acquisition architectures.

---

## 🧰 Tech Stack

### ☁️ Systems & Cloud
`Linux` · `VMware vSphere` · `PowerCLI` · `Docker` · `Kubernetes` · `VPS administration` · `NetBackup` · `Disaster Recovery (DRP/BRP)`

### 📡 IIoT & Telemetry
`MQTT` · `Mosquitto` · `InfluxDB` · `Grafana` · `Raspberry Pi` · `Arduino` · `Sensor integration` · `Real-time dashboards`

### 🔐 Networks & Security
`IP networking` · `VLANs & network isolation` · `Firewalls` · `SSH` · `Cloudflare Tunnel` · `OS patching (ENS)`

### ⚙️ Dev & Automation
`Python (FastAPI, Flask)` · `C/C++` · `Bash scripting` · `REST APIs` · `SQL` · `n8n` · `Git & GitHub` · `Jira / Confluence`

---

## 🚀 Featured Projects

### 📡 [weather-station-iot](https://github.com/YOUR_GITHUB_USER/weather-station-iot)
**Real-time weather station: end-to-end telemetry architecture (Bachelor's Thesis)**

A complete data-acquisition pipeline, from sensor to public dashboard.

```mermaid
flowchart LR
    A[Sensors] --> B[Mosquitto MQTT broker<br/>Raspberry Pi]
    B --> C[(InfluxDB<br/>time-series)]
    C --> D[Grafana<br/>dashboards]
    D --> E[Cloudflare Tunnel]
    E --> F[bsx.es]
```

- **Stack:** MQTT (Mosquitto) · InfluxDB · Grafana · Raspberry Pi · Cloudflare Tunnel
- **Highlights:** network design, time-series storage, real-time visualization, and secure internet exposure through a Cloudflare Tunnel under a custom domain, with no ports opened on the router.
- 🌐 Live: [bsx.es](https://bsx.es)

---

### ☸️ [k8s-docker-lab](https://github.com/YOUR_GITHUB_USER/k8s-docker-lab)
**Multi-worker Kubernetes cluster and containerization lab**

Home lab to practice production-style operations on virtual machines.

- **Stack:** Kubernetes (control plane + multiple workers) · Docker · Nginx · Bash
- **Highlights:** automated container deployments, horizontal scaling, high-availability validation and **self-healing tests** (killing pods and nodes to watch recovery).
- **Focus:** reproducible setup, documented step by step.

---

### 🔄 [automation-workflows-n8n](https://github.com/YOUR_GITHUB_USER/automation-workflows-n8n)
**Workflow automation and service integration**

- **Stack:** n8n · REST APIs · Webhooks · JSON · Docker
- **Highlights:** automated flows that connect external services and publish content autonomously, replacing repetitive manual work.

---

### 🧠 Dream Decoder: AI app on a self-managed VPS
**Python backend + Gemini API, deployed with Docker**

- **Stack:** Python · Gemini API (prompt engineering) · Docker · Linux VPS · Cloudflare
- **Highlights:** I configured and deployed the whole stack myself, from the Linux server to the containers and the public domain.
- 🌐 Live: [dreamdecoderapp.com](https://dreamdecoderapp.com)

---

## 💼 Professional Experience

| Role | Where | What I do |
|---|---|---|
| **Junior IT Operations & Infrastructure Engineer** (2025 – present) | NTT DATA · Telefónica (GALILEO) | Linux and VMware vSphere operations, backup & restore ownership with NetBackup, OS patching under ENS, technical coordination of 3 junior engineers |
| **Disaster Recovery Engineering Intern** (2025) | NTT DATA · Cepsa/Moeve (BRP) | DR tests for critical services, restores in VLANs isolated from the internet, RTO estimates and feasibility reports |

---

## 🎓 Education

- **B.Sc. in Telecommunication Technologies Engineering (Telematics)**, University of Valladolid (2020 – 2025)
- **Erasmus+**, Aristotle University of Thessaloniki, Greece (2024 – 2025)

---

## 📊 GitHub Stats

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USER&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USER&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR_LINKEDIN_SLUG)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:espinellopezandres@gmail.com)

*Open to conversations about IIoT, telemetry, data acquisition and infrastructure.*

</div>
