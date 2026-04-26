# SOC-Log-Anomaly-Detector1
# 1. Create the folder and navigate into it
mkdir soc-log-anomaly-detector
cd soc-log-anomaly-detector

# 2. Create the sub‑folders
mkdir src logs reports

# 3. (Optional) Create a .gitignore file so Git doesn’t track virtual‑envs, logs, etc.
cat > .gitignore <<'EOF'
# Byte‑code
__pycache__/
*.pyc
*.pyo
*.pyd
*.pyc

# Logs
logs/
reports/

# OS files
.DS_Store
Thumbs.db
EOF
