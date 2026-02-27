# SOC Home Lab Architecture (VirtualBox)

A SOC repository documenting the architecture, network plan, and security baseline for a VirtualBox-based home lab used for **detection engineering, alert triage, threat simulation, and DFIR practice**.

## Lab Overview

This lab simulates a small internal network with a dedicated security monitoring sensor and a workstation used for generating both normal and controlled suspicious traffic.

### Assets
- **Ubuntu (Sensor / Security Tooling)**
  - IP: `192.168.1.3/24`
  - Interface: `enp0s3`
  - Role: IDS/monitoring + packet capture + logging

- **Windows 10 (Workstation / Traffic Generator)**
  - IP: `192.168.1.4/24`
  - Role: user activity + controlled adversary simulations

### Network
- Subnet: `192.168.1.0/24`
- Gateway: `192.168.1.1`

## Goals

- Build documented lab infrastructure
- Validate network visibility and telemetry sources
- Support IDS detections, triage workflows and incident documentation
- Produce expected outputs in screenshots 

## Repository Structure
soc-home-lab-architecture/
docs/ # architecture + build notes + baseline controls
assets/
diagrams/ # exported network diagrams (png/svg)
screenshots/ # evidence screenshots used in docs

## Documentation Index

- `docs/00-architecture.md` — topology, asset roles, detection objectives
- `docs/01-network-plan.md` — addressing, routing, VM networking mode
- `docs/02-security-baseline.md` — firewall, accounts, logging, hardening checklist

## Notes

- All “suspicious activity” is simulated **inside the lab environment** .
