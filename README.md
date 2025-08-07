#  Phishing Email Analysis Report

## Email Overview
- **Subject**: Microsoft account unusual signin activity  
- **From**: `no-reply@access-accsecurity.com`  
- **Reply-To**: `solutionteamrecognizd03@gmail.com`  
- **Targeted Email**: `phishing@pot`  
- **Date**: Thu, 24 Aug 2023 08:04:23 +0000

---

##  Phishing Indicators Identified

| Indicator | Description | Why It’s Suspicious |
|----------|-------------|---------------------|
| **1. Fake Sender Address** | Uses `access-accsecurity.com` instead of microsoft.com | Not a real Microsoft domain |
| **2. Reply-To Mismatch** | Reply address is a Gmail ID | Legit companies don’t use free Gmail for support |
| **3. SPF, DKIM, DMARC Failed** | SPF: None, DKIM: none, DMARC: permerror | Lacks proper authentication |
| **4. Unusual IP Origin** | IP: `89.144.44.41` traced to unknown location | Not from Microsoft infrastructure |
| **5. Urgency in Language** | Mentions suspicious login from Russia | Designed to induce panic |
| **6. Tracking Pixel** | Hidden image from unknown domain | Used to track user opens |
| **7. Grammar Issues** | "sign.in" instead of "sign-in" | Poor grammar is a phishing sign |
| **8. Suspicious Button** | "Report the User" button leads to Gmail `mailto:` | Microsoft never asks to report via personal email |
| **9. No Legitimate Microsoft URLs** | No links point to microsoft.com | Legit emails always link back to company domain |
| **10. Visual Spoofing** | Mimics Microsoft’s branding (fonts/colors) | Attempts to appear trustworthy |

---

## 🛡 Conclusion
This email is a **phishing attempt** designed to:
- Steal user information via social engineering
- Appear legitimate through fake branding and urgency
- Collect responses via a personal Gmail address

---
