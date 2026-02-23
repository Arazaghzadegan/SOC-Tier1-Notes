# 🛡️ SOC Tier 1 Notes

A structured knowledge base for **Security Operations Center (SOC) Tier 1 analysts**.  
This repository contains practical notes, playbooks, and quick references to help analysts efficiently monitor, triage, and escalate security events.

---

## 📌 Purpose

The goal of this repository is to:

- Provide quick-reference material for SOC Tier 1 duties  
- Document common alert investigation workflows  
- Standardize initial triage procedures  
- Help new analysts ramp up faster  
- Serve as a personal or team knowledge base  

---

## 🧭 SOC Tier 1 Responsibilities (Overview)

SOC Tier 1 analysts typically:

- Monitor SIEM dashboards  
- Triage security alerts  
- Validate true vs. false positives  
- Perform basic log analysis  
- Escalate confirmed incidents  
- Document investigation steps  

---

## 🔍 Alert Triage Workflow

### Step 1: Alert Intake
- Review alert metadata  
- Identify alert source (EDR, SIEM, IDS, etc.)  
- Check severity and rule triggered  

### Step 2: Initial Validation
- Determine if activity is expected  
- Check asset criticality  
- Review user context  

### Step 3: Log Investigation
Common logs to review:

- Endpoint logs  
- Authentication logs  
- Network traffic  
- Email security logs  
- Cloud audit logs  

### Step 4: Classification
Decide whether the alert is:

- ✅ True Positive  
- ❌ False Positive  
- ⚠️ Benign Positive  
- ❓ Needs escalation  

### Step 5: Response or Escalation
- Contain (if playbook allows)  
- Enrich with context  
- Escalate to Tier 2 if needed  
- Document thoroughly  

---

## 🧰 Common Tools Used

Typical SOC Tier 1 stack:

- SIEM (e.g., Splunk, Sentinel, QRadar)  
- EDR/XDR platforms  
- Threat intelligence platforms  
- SOAR tools  
- Ticketing systems  

---

## 🚨 Common Alert Types

SOC Tier 1 frequently investigates:

- Suspicious logins  
- Multiple failed authentications  
- Malware detections  
- Phishing alerts  
- Impossible travel  
- Privilege escalation  
- Command-and-control traffic  

---

## 📝 Investigation Checklist

Before closing any alert, verify:

- [ ] Alert rule understood  
- [ ] User activity reviewed  
- [ ] Host activity reviewed  
- [ ] False positive ruled out  
- [ ] Evidence documented  
- [ ] Proper classification set  
- [ ] Escalation performed (if required)  

---

## 📚 Recommended Knowledge Areas

To be effective, Tier 1 analysts should understand:

- Networking fundamentals  
- Windows & Linux logs  
- MITRE ATT&CK basics  
- Common attacker techniques  
- Log analysis methods  
- Incident documentation  

---

## 🔗 Future Additions

Planned improvements:

- Detection playbooks  
- Query cheat sheets  
- Real alert case studies  
- MITRE mapping  
- Automation examples  

---

## 🤝 Contributing

Contributions are welcome. You can help by:

1. Creating a feature branch  
2. Adding improvements  
3. Submitting a Pull Request  
4. Providing clear descriptions  

---

## 📄 License

This project is for educational and operational knowledge-sharing purposes.

---

⭐ **Tip:** Bookmark this repo and update it regularly as you gain SOC experience.
