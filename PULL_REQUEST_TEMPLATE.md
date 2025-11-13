Add CODEOWNERS for protection

## 📋 Submission Information

**Name:** [Emirhan ÖZKUL]  
**Email:** [ozklemirhan@gmail.com]  
**LinkedIn:** [linkedin.com/in/yourprofile] _(optional)_  
**Submission Date:** [2002-09-19]

---

## ✅ Deliverables Checklist

Please confirm you've included all required items:

- [ x] **Report** (PDF, max 5 pages)
  - [ x] Section 1: Incident Analysis
  - [ x] Section 2: Architecture Review
  - [ x] Section 3: Response & Remediation
  
- [ x] **Video Presentation** (10-15 minutes)
  - [ x] Link provided in `video_link.md`
  - [ x] Video is accessible (tested in incognito)
  - [ x] Duration is within guidelines

- [ x] **File Structure**
```
  submissions/firstname-lastname/
  ├── 
[Document 8 (1).docx](https://github.com/user-attachments/files/23443744/Document.8.1.docx)

  ├── https://drive.google.com/file/d/1VMabiFtMLFSXS-r_lATKRseJKQ8Baiqa/view?usp=drivesdk
  └── notes.md (optional)
```

---

## 📊 Self-Assessment

**Time spent on this lab:** Approximately 3 hours

**Tools used:**
- Log analysis: ___________
- Diagrams: ___________
- Video recording: ___________

**Confidence level:**
- [ x] Very confident in my analysis
- [ x] Confident but some uncertainties
- [ x] Attempted my best with available knowledge

---

## 🎯 Brief Summary (2-3 sentences)

It began with a simple phishing attack and entered the system due to user ignorance and the WAF's correlation and rules being inadequate. Tokens were extracted using SQL injection, and user data was accessed.


---

## 🔍 Key Findings Highlight

**Main attack vectors identified:**
1. Phisihng
2. SQL Enjeksiyon
3. IDOR

**Most critical vulnerability:**
It has been observed that the greatest vulnerability is the human factor (three out of six users clicked on the link), which indicates that we urgently need to provide staff training. On the defense systems side, the rule sets of tools such as WAF and EDR need to be updated with organization-specific rules instead of the default ones.

**Top recommendation:**
Users must be warned not to click on every incoming email, as this constitutes the weakest link in the security chain. Security measures such as WAF and EDR should be customized to the company's needs rather than relying on default rules. It is essential to prevent access to multiple locations with a single token. Additionally, the SOC team must monitor 24/7 to detect incidents before they occur and must take note of them, even if the WAF was unable to block them.
---

## 💭 Challenges & Learnings

**What was most challenging?**
Since the resources were sufficient, I didn't have much trouble.

**What did you learn?**
I realized that things that seem very simple are actually the weakest link. I realized that many vulnerabilities and attacks originate from the simplest places, that no matter how effective firewalls are, every system is always open to attack, and that we must therefore monitor and observe them 24/7. That's why I learned that we must always be up-to-date, active, and correctly evaluate every log and alarm, and prevent potential losses early on.

**What would you do differently?**
As seen in the mail logs, I would block the suspicious IP address. I would monitor accounts that clicked on the link. I would send awareness messages to users and send reminders. I would not set WAF rules to default, but would configure them according to internal company features and monitor the alerts. Even if the WAF was bypassed, checking whether my alerts were false positives would prevent an attack. I would strengthen my software to prevent attacks such as SQL.

---

## 📝 Additional Notes _(optional)_

Any context, assumptions, or additional information you'd like evaluators to know:

[Write here]

---

## ⚖️ Declaration

I declare that:
- [x ] This work is entirely my own
- [ x] I have not copied from other submissions or answer keys
- [ x] I have not modified the provided log files
- [ x] All sources and tools are properly attributed
- [ x] I understand plagiarism results in disqualification

**Signature:** [Emirhan ÖZKUL]  
**Date:** [2025-11-10]

---

## 🚀 Ready for Review

By submitting this PR, I confirm that my work is complete and ready for evaluation.

---

_Thank you for your submission! Our team will review it within 1 week._
