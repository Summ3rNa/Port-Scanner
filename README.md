# 🔍 PyScanner

A multithreaded TCP port scanner built in Python for a Cybersecurity class project.

## Features
- IP range scanning (single IP, dash range, CIDR)
- Service detection & banner grabbing
- Scan speed control via thread count
- Export results to `.txt` or `.json`
- Interactive CLI menu with input validation

## Requirements
- Python 3.x (no external libraries needed)

## Usage
```bash
python3 pyscanner_final.py
```

---

## 🙈 Step 3 — Create a .gitignore

This prevents junk files from being uploaded:
```
# Python cache files
__pycache__/
*.pyc
*.pyo

# Scan output files (optional - remove if you want to include them)
*.json
*.txt

# OS files
.DS_Store
Thumbs.db
