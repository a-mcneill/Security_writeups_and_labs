# Phishing Email Alert Report - TryHackMe SOC L1

**Date/Time:** 19:25, 27th March 2025
**Receipient:** Eddie Huffman (IT Manager)
**Sender:** support@microsoft.com
**Severity:** Medium
**Alert Type:** Post-delivery Phishing Classification

---

## Summary

At 19:25 on March the 27th 2025, Eddie Huffman (IT Manager) received an email from support@microsoft.com, detailing a 600% price increase.

The email was classified as phishing by the post-delivery automated analysis. The email contains a REPORT.rar file, commonly used in malicious phishing campaigns. As such, it appears the Microsoft support email has been spoofed, in order to distribute and deceive recipients in to downloading the malware.

---

## Key Indicators

- **Attachment:** 'REPORT.rar' - Commonly used in malware delivery.
- **Body Keywords:** "urgent-notice", "download the report", "600% price increase"
- **Authentification:**  SPF/Fail, DKIM/Fail

---

## Assessment

The combination of failed authentication checks, a compressed rar file, and creation of sense of urgency, led to the assessment that the Microsoft support email had been spoofed and that the email was a phishing attempt.

---

## Screenshot

![Phishing Alert Screenshot](../screenshots/THM_Phishing_Alert.png)
