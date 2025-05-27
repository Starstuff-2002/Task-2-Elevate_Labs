# Task-2-Elevate_Labs
Analysing a phishing email


![PHISHING](https://github.com/user-attachments/assets/1399dc9f-35c2-40e7-9c5d-1f0ffc71c8a0)


---

 Sample Email Analyzed:
**Subject**: Change of Password Required Immediately  
**Sender**: IT IT@chitkara.edu.in via ispservices.org  
**Time**: 8:52 PM  
**Screenshot**: See `PHISHING.png`

---

 Phishing Indicators Found

| Indicator | Description |
|----------|-------------|
| **1. Sender Spoofing** | Claimed sender is `chitkara.edu.in` but email was routed via `ispservices.org` — highly suspicious. |
| **2. Urgency Language** | Email uses scare tactics like "security breach" and urges immediate action. |
| **3. Suspicious Link** | Hyperlink says “Change Password” — real URL hidden. Likely leads to fake login page. |
| **4. Generic Signature** | No real name, contact info, or department. Just signed "IT". Not typical of professional communication. |
| **5. Lack of Personalization** | No username or student ID mentioned — looks mass-mailed. |
| **6. Spam Tag** | Gmail automatically flagged the email as "Spam". |

---

Verification Tools

- **Header Analyzer**: Google Admin Toolbox – MessageHeader-  https://toolbox.googleapps.com/apps/messageheader/
- **Link Checker**: Hover in client or use [VirusTotal](https://www.virustotal.com) to analyze URLs.

---

Conclusion

This email shows multiple red flags and should be considered a **phishing attempt**. Do not click any links or respond.

---

 Screenshot

I have included `PHISHING.png` in the repo to show the actual phishing email.
And also the screenshots for the online email analysing tool for headers 

![Screenshot 2025-05-27 213159](https://github.com/user-attachments/assets/c0cf06cf-e43b-47f2-8199-f51524a63959)
![Screenshot 2025-05-27 213207](https://github.com/user-attachments/assets/96a9bff5-ce79-4b97-ade2-385693c4e633)


