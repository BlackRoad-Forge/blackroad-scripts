<!-- BlackRoad SEO Enhanced -->

# ulackroad scripts

> Part of **[BlackRoad OS](https://blackroad.io)** — Sovereign Computing for Everyone

[![BlackRoad OS](https://img.shields.io/badge/BlackRoad-OS-ff1d6c?style=for-the-badge)](https://blackroad.io)
[![BlackRoad Forge](https://img.shields.io/badge/Org-BlackRoad-Forge-2979ff?style=for-the-badge)](https://github.com/BlackRoad-Forge)
[![License](https://img.shields.io/badge/License-Proprietary-f5a623?style=for-the-badge)](LICENSE)

**ulackroad scripts** is part of the **BlackRoad OS** ecosystem — a sovereign, distributed operating system built on edge computing, local AI, and mesh networking by **BlackRoad OS, Inc.**

## About BlackRoad OS

BlackRoad OS is a sovereign computing platform that runs AI locally on your own hardware. No cloud dependencies. No API keys. No surveillance. Built by [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc), a Delaware C-Corp founded in 2025.

### Key Features
- **Local AI** — Run LLMs on Raspberry Pi, Hailo-8, and commodity hardware
- **Mesh Networking** — WireGuard VPN, NATS pub/sub, peer-to-peer communication
- **Edge Computing** — 52 TOPS of AI acceleration across a Pi fleet
- **Self-Hosted Everything** — Git, DNS, storage, CI/CD, chat — all sovereign
- **Zero Cloud Dependencies** — Your data stays on your hardware

### The BlackRoad Ecosystem
| Organization | Focus |
|---|---|
| [BlackRoad OS](https://github.com/BlackRoad-OS) | Core platform and applications |
| [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc) | Corporate and enterprise |
| [BlackRoad AI](https://github.com/BlackRoad-AI) | Artificial intelligence and ML |
| [BlackRoad Hardware](https://github.com/BlackRoad-Hardware) | Edge hardware and IoT |
| [BlackRoad Security](https://github.com/BlackRoad-Security) | Cybersecurity and auditing |
| [BlackRoad Quantum](https://github.com/BlackRoad-Quantum) | Quantum computing research |
| [BlackRoad Agents](https://github.com/BlackRoad-Agents) | Autonomous AI agents |
| [BlackRoad Network](https://github.com/BlackRoad-Network) | Mesh and distributed networking |
| [BlackRoad Education](https://github.com/BlackRoad-Education) | Learning and tutoring platforms |
| [BlackRoad Labs](https://github.com/BlackRoad-Labs) | Research and experiments |
| [BlackRoad Cloud](https://github.com/BlackRoad-Cloud) | Self-hosted cloud infrastructure |
| [BlackRoad Forge](https://github.com/BlackRoad-Forge) | Developer tools and utilities |

### Links
- **Website**: [blackroad.io](https://blackroad.io)
- **Documentation**: [docs.blackroad.io](https://docs.blackroad.io)
- **Chat**: [chat.blackroad.io](https://chat.blackroad.io)
- **Search**: [search.blackroad.io](https://search.blackroad.io)

---


[![Shell](https://img.shields.io/badge/Shell-400%2B_scripts-4EAA25.svg)](https://gnu.org/software/bash/)
[![Pi Fleet](https://img.shields.io/badge/fleet-5_nodes-FF2255.svg)](https://blackroad.io)
[![WireGuard](https://img.shields.io/badge/WireGuard-mesh-88171A.svg)](https://wireguard.com)
[![Docker](https://img.shields.io/badge/Docker-Swarm-2496ED.svg)](https://docker.com)



**612 shell scripts. 87 Python scripts. One sovereign fleet.**

Automation suite for the entire BlackRoad OS ecosystem — deployment, infrastructure management, AI operations, quantum experiments, monitoring, and fleet orchestration across 5 Raspberry Pi 5 nodes.

## At a Glance

| Category | Count | Description |
|----------|-------|-------------|
| `deploy-*` | 67 | Cloudflare, Pi fleet, service deployment |
| `blackroad-*` | 71 | Core platform operations |
| `memory-*` | 34 | Lucidia memory system management |
| `setup-*` | 21 | Environment and service setup |
| `test-*` | 22 | Integration and smoke tests |
| `br-*` | 22 | BlackRoad CLI shortcuts |
| `claude-*` | 12 | Claude AI integration scripts |
| `quantum-*` | 7 | Quantum simulation runners |
| `cloudflare-*` | 5 | DNS, Workers, Pages management |
| Python scripts | 87 | AI agents, consciousness models, generators |

## Infrastructure

These scripts manage:

- **5 Raspberry Pi 5 nodes** — Alice (.49), Cecilia (.96), Octavia (.97), Aria (.98), Lucidia (.38)
- **WireGuard mesh** — 10.8.0.x inter-node routing
- **2 Hailo-8 AI accelerators** — 52 TOPS total
- **108 Ollama models** — deployment and management
- **48+ custom domains** — DNS and Cloudflare routing
- **18 Cloudflare tunnels** — edge routing
- **Docker Swarm** — container orchestration

## Key Scripts

### Deployment
```bash
./deploy-all-services.sh        # Deploy everything
./deploy-to-cloudflare.sh       # Push to Cloudflare Pages
./DEPLOY_BLACKROAD_ON_ALICE.sh  # Deploy to Alice Pi
./MEGA-DEPLOY.sh                # Full fleet deployment
```

### Infrastructure
```bash
./setup-wireguard.sh            # Configure WireGuard mesh
./add-all-devices-to-network.sh # Network device provisioning
./QUICK_SSH.sh                  # Fast SSH to any Pi
```

### AI / Memory
```bash
./memory-*.sh                   # 34 memory management scripts
./claude-*.sh                   # Claude AI integration
./CONSCIOUSNESS_MASTER_CONTROL.py # AI consciousness framework
```

## Usage

```bash
git clone https://github.com/blackboxprogramming/blackroad-scripts.git
cd blackroad-scripts
chmod +x script-name.sh
./script-name.sh
```

## Related

- [BlackRoad-Operating-System](https://github.com/blackboxprogramming/BlackRoad-Operating-System) — Master monorepo
- [aria-infrastructure-queen](https://github.com/blackboxprogramming/aria-infrastructure-queen) — Aria's infrastructure automation

## License

Copyright 2026 BlackRoad OS, Inc. — Alexa Amundson. All rights reserved.
