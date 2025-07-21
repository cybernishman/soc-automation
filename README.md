# SOC-Automation
Industry-grade incident analysis, threat enrichment, and security workflow automation (Power Automate + n8n + OpenAI + Google).

# 🚨 SOC Automation Project: AI-Powered Email & Network Threat Detection

---

## ⭐ Overview

This project is **Security Operations Center (SOC) automation workflow** that detects, triages, and reports phishing emails and network threats—using only accessible, free, cloud-native tools.

**Why is it special?**
It bridges “student project” and *industry-ready security automation*—using the same modular, event-driven design seen in enterprise SOCs, but with tools available to anyone.

---

## 🏗️ Architecture

* **Power Automate (Cloud):** Detects and parses phishing/malware emails, logs them as structured incidents.
* **Google Sheets:** Acts as a shared “SOC log bus” for incident data, enabling seamless handoff between automations.
* **n8n:** Ingests, enriches, and AI-scores network logs and email incidents; triggers real-time Slack alerts for high-risk findings.
* **OpenAI:** Provides AI-driven triage, risk scoring, and actionable recommendations for each incident.
* **Looker Studio:** Real-time dashboarding and analytics for all SOC activity.

> **Integration Pattern:**
> Power Automate and n8n are “loosely coupled” via Google Sheets, emulating the log/event bus approach of advanced SOC environments.

---

## 🔥 Key Features

* **Automated phishing/malware email detection** and triage.
* **Network log ingestion** with enrichment (IP intelligence, threat feeds).
* **AI-driven risk scoring and summaries** for every alert.
* **Central, cloud-based SOC incident log** (no local infra needed).
* **Real-time Slack notifications** for critical risks.
* **Live analytics dashboard** for full situational awareness.

---

## 💡 What Makes This Stand Out

* **Mirrors enterprise automation:** Follows “log bus” modularity used in real SOCs and MSSPs—showing you understand modern, scalable architecture.
* **Bridges multiple cloud tools:** Demonstrates skill integrating Power Automate, n8n, OpenAI, and cloud-based dashboards without a SIEM budget.
* **Resourceful, upgrade-ready:**

  * Used Google Sheets as a workaround for message bus/SIEM integration, but fully documented how this maps to enterprise tools.
  * *For recruiters: shows you can “do more with less”—but also know how to design for scale and upgrade later.*
* **End-to-end automation:**

  * From threat detection to enrichment to alerting and reporting—no manual intervention.

---

## 🛠️ Tools Used — and Industry Equivalents

| This Project            | Industry Standard Alternative            |
| ----------------------- | ---------------------------------------- |
| Power Automate          | Microsoft Sentinel, Defender, Logic Apps |
| n8n                     | SOAR (XSOAR, Sentinel Playbooks)         |
| Google Sheets (log bus) | SIEM (Splunk, Sentinel, ELK, QRadar)     |
| Slack                   | Teams, PagerDuty, ServiceNow             |
| OpenAI                  | Built-in ML/AI in SIEM/SOAR              |
| Looker Studio           | SIEM/PowerBI/Kibana dashboards           |

*All steps are fully upgradeable—just swap Google Sheets for a SIEM, n8n for SOAR, and you have an enterprise-ready pipeline.*

---

## 🚀 What Did I Learn?

* **Integrating no-code and pro-code tools for real SOC automation**
* **Designing modular, event-driven workflows** that scale
* **Building AI-powered enrichment** and risk scoring
* **Presenting actionable security data for analytics and management**
* **Documenting industry mappings and upgrade paths** (workaround vs enterprise)

---

## 🎯 Use Cases

* **For recruiters & SOC leads:**

  * Demonstrates hands-on experience with automation, integration, and practical security operations.
  * Shows both “builder” and “architect” mindset: not just using tools, but understanding best practices and future upgrades.

* **For learners:**

  * A clear blueprint to move from academic projects to real-world SOC workflows—without needing expensive tools.

---
Built by [ManishPulluru] — [LinkedIn](https://www.linkedin.com/in/manish-pulluru-918507196/) 
