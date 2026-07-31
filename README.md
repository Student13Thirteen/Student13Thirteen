# Antonio Fico 👋1️⃣3️⃣

### Management Engineer building self-hosted operational systems

I turn real operational friction into **deployable, diagnosable and reviewable tools**.

My projects sit at the intersection of **Cloud, Linux, technical operations, internal tools and workflow automation**. I enjoy the whole path from an operational problem to a working system: defining the flow, connecting services, deploying on a server, reading logs, testing failure paths, documenting setup and making the result easy for another person to run.

📍 Naples, Italy  
🎓 MSc in Management Engineering — Federico II University of Naples  
🎯 Open to junior opportunities in Cloud, IT Operations, DevOps, automation and technical implementation

## 🚀 Flagship project

### [NFRP](https://github.com/Student13Thirteen/NFRP) — self-hosted operations platform

A transport-focused reference implementation built around a reusable operational core. NFRP connects document intake, controlled imports, human-reviewed `PENDING` workflows, fleet operations and cost control.

```text
upload or import
      ↓
parse and validate
      ↓
PENDING proposal
      ↓
human review and confirmation
      ↓
operational record + cost center
```

The public edition includes:

- guided server setup with generated secrets;
- company name, logo and runtime color-palette customization;
- PostgreSQL, Prisma migrations and synthetic demo data;
- local, LAN/reverse-proxy and optional Cloudflare Tunnel modes;
- `setup`, `doctor`, `backup`, `update` and deterministic demo commands;
- repository safety checks, unit tests, production build and clean-room Docker verification.

```bash
git clone https://github.com/Student13Thirteen/NFRP.git
cd NFRP
bash nfrp setup
```

## 🧰 Other deployable projects

### [DockNextFlare](https://github.com/Student13Thirteen/docknextflare)

A guided Docker deployment for a private Nextcloud instance with MariaDB and optional Cloudflare Tunnel access. Its CLI manages setup, diagnostics, logs, backups and updates; CI performs a clean core installation and verifies health and network isolation.

```bash
bash docknextflare setup
```

### [PwaTruckPocket](https://github.com/Student13Thirteen/pwatruckpocket)

An offline-first driver workflow for trip status updates and travel documents, backed by PocketBase. It includes an IndexedDB queue, retry logic, server-side notifications, Italian/Arabic UI and automated creation of the schema and synthetic demo accounts.

```bash
bash pwatruckpocket setup
```

### [UptimeMonitoring](https://github.com/Student13Thirteen/uptimemonitoring)

A compact Uptime Kuma reliability lab with local, LAN or optional Cloudflare access. A disposable internal target makes downtime and recovery safe to demonstrate, while the CLI provides setup, diagnostics, backup and update operations.

```bash
bash uptimemonitoring setup
```

## 🛠️ Current toolkit

**Infrastructure and networking**  
Linux · Ubuntu Server · Docker · Docker Compose · Cloudflare Zero Trust Tunnels · DNS · reverse-proxy concepts

**Operations and reliability**  
Health checks · logs · backups · monitoring · troubleshooting · clean-room installation tests · GitHub Actions

**Applications and data**  
Next.js · PostgreSQL · Prisma · PocketBase · MariaDB · Nextcloud · PWA workflows

**Automation and development**  
Python foundations · Bash in active development · JavaScript/TypeScript project work · Telegram integrations

## How I work

These projects were developed with AI assistance. My contribution is the **problem definition, workflow design, architecture and deployment choices, iterative direction and review, configuration, testing, troubleshooting, documentation and verification**.

I do not present AI-generated implementation as code written line by line without assistance. I present what I can support in practice: understanding the systems, deploying them, diagnosing problems, validating behavior and continuing to strengthen my independent Python, Bash and software-engineering skills.

## What connects the projects

They are not unrelated tutorials. They explore a consistent question:

> How can small operational organizations adopt useful self-hosted software without turning installation, remote access and maintenance into a second full-time job?

That theme drives the guided installers, optional secure tunnels, synthetic demos, health checks and clean-room CI across the portfolio.

## 📫 Contact

[Email](mailto:antofico13@gmail.com) · [LinkedIn](https://www.linkedin.com/in/antofico13)
