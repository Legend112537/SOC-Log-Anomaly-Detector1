# SOC-Log-Anomaly-Detector1
cat > README.md <<'EOF'
# 🛡️ SOC Log Anomaly Detector

A Python‑based tool that simulates a SOC analyst’s core task: ingesting logs, detecting brute‑force patterns, and producing a concise report.

## 🚀 Features
- **Log Parsing** – Reads standard `auth.log`‑style SSH logs.
- **Anomaly Detection** – Flags IPs with ≥3 failed login attempts.
- **Severity Scoring** – MEDIUM or HIGH based on frequency.
- **JSON Reporting** – Easy integration with SIEMs or other tooling.
