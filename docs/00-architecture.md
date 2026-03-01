cat > docs/00-architecture.md <<'EOF'
# SOC Home Lab Architecture

## Purpose
This lab provides a controlled environment to practice SOC workflows:
- detection engineering
- alert validation
- triage and investigation
- evidence capture and reporting

## Assets
- Ubuntu (Sensor / Security Tooling)
  - IP: 192.168.1.3/24
  - Interface: enp0s3
- Windows 10 (Workstation / Traffic Generator)
  - IP: 192.168.1.4/24

## Network
- Subnet: 192.168.1.0/24
- Gateway: 192.168.1.1

## Detection Objectives
1. Validate sensor visibility
2. Establish baseline traffic expectations
3. Generate controlled suspicious activity inside the lab
4. Capture evidence and produce SOC-style documentation
EOF