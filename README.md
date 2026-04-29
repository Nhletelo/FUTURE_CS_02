# 📧 Phishing Email Detection & Awareness System

## 📌 Overview
This project focuses on analyzing phishing emails and creating awareness on how to identify and prevent phishing attacks. The goal is to simulate real-world email threat analysis and present findings in a clear, user-friendly way.

---

## 🛠️ Tools Used

The following tools were used during the phishing detection process:

- **Google Admin Toolbox (Messageheader)**  
  Used to analyze email headers and verify if the sender is legitimate by checking SPF, DKIM, and DMARC authentication results.

- **MXToolbox**  
  Used to further inspect email headers and check sender reputation.

- **VirusTotal**  
  Used to scan URLs and detect whether links in emails are malicious or safe.

- **WHOIS Lookup**  
  Used to investigate domain information such as registration date and ownership, helping identify suspicious or newly created domains.

- **Browser Tools (Chrome DevTools)**  
  Used to safely inspect links and analyze URLs without clicking them.

---

## 🔍 Analysis Approach

The phishing detection process followed a structured step-by-step approach:

### 1. Email Content Review  
The email was examined for common phishing indicators such as:
- Generic greetings (e.g., “Dear User”)
- Urgent or threatening language
- Suspicious links
- Lack of official branding or contact details

---

### 2. Link Inspection  
All links in the email were carefully inspected without clicking them.  
The URLs were analyzed using VirusTotal to check for malicious activity or suspicious behavior.

---

### 3. Domain Verification  
The domain of the sender and links was checked using WHOIS Lookup to identify:
- Recently created domains
- Hidden or suspicious ownership details

---

### 4. Email Header Analysis  
The email header was analyzed using Google Admin Toolbox and MXToolbox to verify:
- SPF (Sender Policy Framework)
- DKIM (DomainKeys Identified Mail)
- DMARC (Domain-based Message Authentication)

These checks help determine whether the email is authentic or spoofed.

---

### 5. Risk Classification  
Based on the findings, the email was classified into one of the following categories:
- ✅ Safe
- ⚠️ Suspicious
- 🔴 Phishing

---

### 6. Documentation & Reporting  
All findings were documented clearly, including:
- Identified phishing indicators
- Tool results (screenshots)
- Risk level classification
- Prevention recommendations

---

## 🛡️ Outcome
The analysis successfully demonstrated how phishing emails can be detected using simple tools and structured investigation techniques. The project also highlights the importance of user awareness in preventing cyber attacks.

---

## ⚠️ Disclaimer
This project is for educational purposes only. All phishing examples used are simulated or publicly available samples.
