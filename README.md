# Network Security Threats Report

Author: Mahak Rana   
Objective: Explain common network security threats — how they work, why they are dangerous, and how to defend against them.

---

## 1. Introduction

The internet is a busy place, but it’s not always safe. Just like in the real world, there are “bad actors” online who try to disrupt services, steal data, or pretend to be someone they’re not.  

This report covers three major types of network security threats:

1. Denial of Service (DoS) Attacks  
2. Man-in-the-Middle (MITM) Attacks  
3. Spoofing Attacks

For each, we’ll explain how it works, give a real-world example, and share ways to stay protected.

---

## 2. Common Network Security Threats

### 2.1 Denial of Service (DoS) Attacks

🔹 What it is  
A DoS attack happens when a server or network is flooded with so many requests that it can’t respond to real users.  
When this is done using many devices at once, it’s called a **DDoS (Distributed DoS) attack.

🔹 Why it’s bad  
- Websites or apps become unavailable.  
- Businesses lose money and reputation.  
- Can be used as a distraction while other attacks happen.  

🔹 Real example  
In 2018, GitHub faced one of the largest DDoS attacks ever — **1.35 Tbps of traffic — which temporarily took their site offline.

🔹 How to prevent it  
- Use firewalls and intrusion prevention systems.  
- Apply rate limiting to control traffic spikes.  
- Use DDoS protection services like Cloudflare or Akamai.  
- Have backup servers and load balancing.

---

### 2.2 Man-in-the-Middle (MITM) Attacks

🔹 What it is  
A MITM attack is when someone secretly intercepts communication between two people or systems — for example, between you and a website.

Attackers can:  
- Read your messages.  
- Steal your login details.  
- Change the data being sent.

🔹 Why it’s bad  
- Sensitive information can be stolen (passwords, credit cards).  
- Data can be altered without your knowledge.  
- Leads to identity theft and fraud.

🔹 Real example  
In 2015, some Lenovo laptops had pre-installed adware called **Superfish that intercepted encrypted traffic, making MITM attacks possible.

🔹 How to prevent it  
- Always use HTTPS websites.  
- Avoid public Wi-Fi or use a VPN.  
- Enable certificate pinning in apps.  
- Educate users to avoid fake Wi-Fi hotspots.

---

### 2.3 Spoofing Attacks

🔹 What it is  
Spoofing is when an attacker pretends to be a trusted person, device, or service. They “fake” their identity to trick victims.

Types of spoofing include:  
- IP Spoofing — fake source IP addresses.  
- Email Spoofing — fake sender email addresses.  
- DNS Spoofing — redirecting you to a malicious website.

🔹 Why it’s bad  
- Used in phishing scams to steal information.  
- Can spread malware.  
- Damages trust in communication systems.

🔹 Real example  
From 2013 to 2015, attackers tricked Google and Facebook employees into sending them **over $100 million by using fake invoices in an email spoofing scam.

🔹 How to prevent it  
- Use SPF, DKIM, and DMARC for email authentication.  
- Secure DNS with DNSSEC.  
- Use packet filtering to block fake IP addresses.  
- Train employees to detect phishing attempts.

---

## 3. Quick Comparison

| Threat Type | Goal | Real Example | How to Protect |
|-------------|------|--------------|----------------|
| DoS/DDoS | Overwhelm and take down a service | GitHub DDoS 2018 | DDoS protection, firewalls, rate limiting |
| MITM | Intercept or change communication | Lenovo Superfish 2015 | HTTPS, VPN, certificate pinning |
| Spoofing | Pretend to be someone trusted | Google/Facebook email scam | SPF/DKIM/DMARC, DNSSEC, user training |

---

## 4. Conclusion

Cyber threats like DoS, MITM, and spoofing are serious, but they can be reduced with the right mix of technology, **good practices, and **user awareness. Staying secure online means being alert, using encryption, and keeping systems updated.

---

## 5. References

1. [Cloudflare – What is a DDoS Attack?](https://www.cloudflare.com/learning/ddos/what-is-a-ddos-attack/)  
2. [OWASP – Man-in-the-Middle (MITM)](https://owasp.org/www-community/attacks/Man-in-the-middle)  
3. [Cisco – Spoofing Attacks](https://www.cisco.com/c/en/us/products/security/what-is-spoofing.html)
