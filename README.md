# 🎯 NeoForge: Universal Document Triage Engine  
*AI Genesis Hackathon Submission — Built in 3 Days*

## 🌐 Live Dashboard  
![Dashboard QR Code](dashboard/dashboard_qr_code.png)  
🔗 [Live Dashboard](https://8fe71b9d-7c93-498e-b1da-da32816e7d13-00-gk0sjemjd72v.kirk.repl.dev/)  
*(Scan QR code or click link to see real-time operator dashboard)*

## 📂 Submission Contents
- `workflow/`: Opus `.opus` file → `NeoForge_Universal_Triage.opus`  
- `sample_data/`: Mock PDF, CSV, email for testing  
- `audit_samples/`: Sample audit PDFs (approved/rejected)  
- `dashboard/`: Replit source code + QR code  
- `README.md`: This document  
- `demo.mp4`: 90-second walkthrough (coming soon!)

## 🏆 Why NeoForge Wins
- ✅ **Reusable**: Works across insurance, KYC, HR, e-commerce returns  
- ✅ **Traceable**: Full audit trail (PDF + JSON) with confidence heatmaps 🟢🟠🔴  
- ✅ **Exception-resilient**: Auto-retry, human review loop, recovery from missing fields  
- ✅ **Operator-first**: Live dashboard with filters + QR access + status counters  
- ✅ **Auditable**: Provenance section in every audit report — shows full lineage

## 📑 Audit Samples
- ✅ [CLM-789_Approved.pdf](audit_samples/CLM789_Approved.pdf) — Auto-approved after human override  
- ⚠️ [CLM-791_Rejected.pdf](audit_samples/CLM791_Rejected.pdf) — Shows exception handling & recovery

## 🧩 How to Run (For Reviewers)
1. Import `workflow/NeoForge_Universal_Triage.opus` into Opus.  
2. Upload files from `sample_data/` (PDF, CSV, email).  
3. Run job → see outputs in Google Sheet mock / audit folder.  
4. (Optional) Deploy dashboard: `cd dashboard && pip install -r requirements.txt && python app.py`

## 📈 Performance
- Batch of 50 claims: **82 seconds** (vs 142s sequential) — **42% faster** via parallel imports + chunking.  
- Handles missing fields, low-confidence, duplicates gracefully.

Built by [Akira & Yusuf] — 2025 AI Genesis Hackathon 🏆
