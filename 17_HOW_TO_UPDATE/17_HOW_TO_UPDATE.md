# How to Update — OPENHAB

**Project:** `OPENHAB`
**Category:** CONSUMER_APPLIANCES
**Domain:** consumer appliances and IoT
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
OPENHAB --version
OPENHAB check-update
```

### Applying Updates
```bash
pip install --upgrade OPENHAB
```

### Rolling Back
```bash
pip install OPENHAB==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
