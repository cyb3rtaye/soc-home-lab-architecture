cat > docs/01-network-plan.md <<'EOF'
# Network Plan (VirtualBox)

## Addressing
- Ubuntu sensor: 192.168.1.3/24
- Windows workstation: 192.168.1.4/24
- Gateway: 192.168.1.1

## Connectivity Validation
Ubuntu -> Windows:
- ping 192.168.1.4

Windows -> Ubuntu:
- ping 192.168.1.3

## Evidence
Screenshots are stored in:
- assets/screenshots/
EOF