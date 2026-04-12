<div align="center">

# XPoint Solutions

**Building the future of IoT tracking and geospatial analytics**

[![AdaTrack](https://img.shields.io/badge/AdaTrack-Production%20IoT%20Platform-0366d6?style=for-the-badge&logo=satellite&logoColor=white)](https://adatrack.io)
[![Discord](https://img.shields.io/badge/Discord-Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/sdZjavNUtS)

</div>

---

### About Us

We are **XPoint Solutions**, a software development company based in Kosice, Slovakia, focused on building high-performance infrastructure for the IoT industry. Our flagship product, **AdaTrack**, powers real-time asset tracking and telemetry analytics for organizations worldwide.

### AdaTrack — Real-time IoT Tracking & Geospatial Analytics at Scale

[AdaTrack](https://adatrack.io) is a production-grade IoT platform built for high-throughput telemetry ingestion and real-time geospatial analytics. It processes millions of UDP packets per second, decodes proprietary binary payloads, and streams live data to a WebGL-powered dashboard.

**Key capabilities:**

- **UDP-First Ingestion** — Kernel-tuned Go backend with microsecond latency
- **Dynamic Payload Decoders** — Define binary-to-JSON decoders in JavaScript, update live
- **Real-Time Tracking** — GPU-accelerated map rendering (Deck.gl) for thousands of assets
- **Self-Hosted Maps** — Built-in OpenStreetMap tile server, no third-party accounts needed
- **Geofencing & Alerts** — PostGIS-powered virtual boundaries with instant notifications
- **No-Code Workflows** — Automated actions based on telemetry events or thresholds
- **Enterprise RBAC** — Granular role-based access control with resource ownership

### Quick Start

```bash
# Pull and run with Docker
docker-compose up -d
# Open http://localhost:8080
```

Available as **Docker images**, **standalone binaries** (Linux, macOS, Windows), and **SaaS** at [adatrack.io](https://adatrack.io).

### Open Source Projects

| Repository | Description |
|---|---|
| [**adatrack**](https://github.com/xpointsolution/adatrack) | Production-grade IoT platform for telemetry & geospatial analytics |
| [**gps-compare**](https://github.com/xpointsolution/gps-compare) | Algorithm for fair GPS route comparison using geometric distance |
| [**osm_downloader**](https://github.com/xpointsolution/osm_downloader) | Automated GPX trace downloader from OpenStreetMap |

### Get in Touch

- **Website:** [adatrack.io](https://adatrack.io)
- **Documentation:** [adatrack-io.gitbook.io](https://adatrack-io.gitbook.io)
- **Discord:** [Join our community](https://discord.gg/adatrack)
- **Email:** xpointsolution@gmail.com
- **Location:** Kosice, Slovakia
