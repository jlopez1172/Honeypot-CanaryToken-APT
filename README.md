# 🛡️ Honeypot & Canary Token Monitoring — SOC+ Lab Project

This repository documents my SOC+ cybersecurity project, which focuses on deception tools for proactive threat detection. It includes step-by-step implementation of a **Cowrie honeypot** and **Canary Tokens** designed to identify unauthorized access attempts and attacker behavior in a controlled lab environment.

## 🔍 Project Overview

This project explores the strategic use of deception in network security:

- **Cowrie Honeypot**: A simulated vulnerable SSH service deployed on Kali Linux to log attacker interactions.
- **Canary Tokens**: Embedded triggers (e.g., Excel files) that notify defenders when accessed, revealing IP, user agent, and timestamp.

## 🧠 Key Learnings

- Set up and configured Cowrie honeypot using Python virtual environment
- Created and tested multiple Canary Tokens for alerting on access
- Monitored and analyzed log data for attacker behavior
- Documented threat scenarios and alert workflow for SOC operations

## ⚙️ Tools & Technologies

- Kali Linux
- Cowrie (SSH Honeypot)
- CanaryTokens.org
- Python & Virtualenv
- Netstat & Log Analysis
- Email Alerts for Incident Response

## 📁 Structure

- `honeypot-setup/` — Cowrie installation steps and configuration
- `canary-token-tests/` — Token deployment strategies and results
- `logs/` — Sample attacker logs and analysis snippets
- `docs/` — Summary findings and workflow notes

## 🚨 Use Case

Ideal for SOC analysts, penetration testers, and cybersecurity students looking to integrate deception techniques into lab environments or alerting strategies.
