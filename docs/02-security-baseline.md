cat > docs/02-security-baseline.md <<'EOF'
# Security Baseline

## Ubuntu (Sensor)
- [ ] system updates applied
- [ ] firewall rules documented (if used)
- [ ] time sync confirmed
- [ ] logging paths identified
- [ ] least privilege for daily user (sudo only when needed)

## Windows 10 (Workstation)
- [ ] Defender enabled (or explicitly documented otherwise)
- [ ] host firewall enabled
- [ ] test user account used for simulations
- [ ] logs available for correlation when needed

## Operational Notes
- This repo does not store secrets, keys, or sensitive logs.
- Any “suspicious activity” is simulated only inside the lab.
EOF