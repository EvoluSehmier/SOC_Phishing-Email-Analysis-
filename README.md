# Phishing Email Analysis (SOC Investigation)

## 📌 Executive Summary
A suspicious email was analyzed and determined to be a phishing attempt based on multiple indicators of compromise including spoofed domains and malicious links.

## 🎯 Objective
Identify phishing indicators and assess risk level.

## 🛠 Tools Used
- VirusTotal
- Email Header Analyzer
- WHOIS Lookup

## 🔍 Investigation Steps

### 1. Initial Triage
- Email flagged due to urgent language and suspicious sender

### 2. Header Analysis
- Source IP inconsistent with claimed domain
- SPF/DKIM checks failed

### 3. Domain Analysis
- Domain recently registered
- No legitimate business association

### 4. URL Analysis
- Link redirects to non-secure login page
- Flagged as malicious in VirusTotal

## 🚨 Indicators of Compromise (IOCs)
- Domain: fake-login-alert.com
- IP: 192.168.1.1
- URL: http://fake-login-alert.com/reset

## ⚖️ Risk Assessment
**Severity: High**  
User credential theft likely

## ✅ Response Actions
- Blocked domain
- Reported phishing attempt
- Advised user awareness

## 📚 MITRE ATT&CK Mapping
- T1566.002 – Phishing: Spearphishing Link

## 🧠 Lessons Learned
User awareness and email filtering are critical to preventing phishing attacks.
