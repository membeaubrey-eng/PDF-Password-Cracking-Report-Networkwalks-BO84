# PDF Password-Recovery Assessment Report


## 1. Assessment details

| Field | Details |
|---|---|
| Report title | PDF Password-Recovery Assessment |
| Author | Aubrey Membe |
| Organization / course | Networkwalks BO84 |
| Assessment date | [20/11/2026 |
| PDF identifier | Locked PDF 1,2,3 |
| Authorization | Network walks |

## 2. Executive summary

This assessment evaluated whether the password protected **Locked PDF** could be recovered using the approved tools listed below. The assessment was limited to the specified PDF and conducted under **authorization of networkwalks**.

**Outcome:** Password recovered  

**Impact:** Access to the password exposes the locked document contents e.g, confidential records and shows that the protection could be bypassed in a short time with a basic wordlist attack,so the files confidentiality is not reliably protected.  

**Recommendation:** Use a strong, unique password and share it through a separate approved channel. Review whether the document needs password protection or a different access-control method.

## 3. Scope and authorization

**In scope:** Locked PDF 1,2,3 the test document created for this exercise
**Out of scope:** anything other than that file,including other systems,accounts and people 
**Authorization:** This assessment was performed as part of PDF password cracking with the approval of Waqas Karim. The test PDF was created by Network walks for this exercise, and all activity
 Was limited to a controlled lab environment 
**Restrictions:** Testing was limited to the Locked PDF, with no access to other systems or data, and no use of recovered content beyond this assessment

No files outside the stated scope were assessed. **only authorised files were worked on**

## 4. Tools considered

| Tool | Use in this assessment | Notes |
|---|---|---|
| John the Ripper | was used for PDF password cracking | johnny 2.2 win |
| Hashcracker Online | Hash extraction from pdf | https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php#extract |
| Networkwalks Online | [Hash extraction from pdf] | https://networkwalks.com/hash-calculator/ |
| Networkwalks online | Password cracking | https://networkwalks.com/password-cracker/] |

**Data-handling note:** Do not submit a confidential document or derived password data to an online service without explicit authorization and approval of its data-handling terms.

## 5. Assessment approach

The assessment used the approved tools to determine whether the PDF’s password could be recovered within the authorized scope and time limits. Testing was restricted to **Locked PDF 1,2,3**. Any online-service use was limited to **lab environment**.

Detailed operational steps and sensitive values are omitted from this report. Supporting evidence is included in the appendix with secrets and personal information redacted.

## 6. Results

**Overall result:** Recovered 

| Tool | Used? | Result | Evidence reference |
|---|---:|---|---|
| John the Ripper | Yes| password cracked | https://github.com/membeaubrey-eng/PDF-Password-Cracking-Report-Networkwalks-BO84/blob/main/JTR%20shot.png |
| Hashcracker Online | Yes| hash cracked | https://github.com/membeaubrey-eng/PDF-Password-Cracking-Report-Networkwalks-BO84/blob/main/pdf%20online%20extractor.png |
| Networkwalks Online | Yes | hash cracked | https://github.com/membeaubrey-eng/PDF-Password-Cracking-Report-Networkwalks-BO84/blob/main/Networkwalks%20hash%20cracking.png |
| Networkwalks Online | [Yes | Password cracked | https://github.com/membeaubrey-eng/PDF-Password-Cracking-Report-Networkwalks-BO84/blob/main/Networkwalks%20password%20cracking.png |

**Password disclosure:** The recovered password is included in screen shots because the document was created solely for this exercise and holds no sensitive data  
**Limitations:** Testing was limited to 3 PDF, two recovery method and the time and hardware available.Findings apply only to these documents and do not represent the security of other files or systems

## 7. Findings and recommendations

1. **Use a strong, unique password.** Avoid short, reused, or easily guessed passwords.
2. **Protect the password separately.** Do not store it alongside the PDF or send it in the same message.
3. **Review the protection requirement.** PDF password protection may not be the best fit for sensitive documents; consider approved document-access controls.
4. **Use online recovery services cautiously.** Confirm authorization, confidentiality, retention, and deletion terms before submitting any material.
5. **Keep evidence securely.** Redact passwords, hashes, personal information, and unrelated document content from screenshots.

## 8. Conclusion

Based on the authorized assessment, **An authorized test of the Locked PDF recovered its password, showing that its protection was insufficient and should be strengthened with a unique passphrase and secure sharing.**. The result applies only to the tested PDF and the stated assessment conditions; it does not establish the strength of other documents or passwords.

## Appendix A — Screenshot placeholders


### Figure A1 — Authorized test document
**[Insert screenshot here]**  
*Caption: [Show only the document identifier or test context; redact sensitive content.]*

### Figure A2 — John the Ripper result
**[Insert screenshot here, if used]**  
*Caption: [Summarize the relevant result. Redact passwords and sensitive values.]*

### Figure A3 — Hashcracker Online result
**[Insert screenshot here, if used]**  
*Caption: [Summarize the relevant result. Redact passwords, submitted data, and account details.]*

### Figure A4 — Networkwalks Online result
**[Insert screenshot here, if used]**  
*Caption: [Summarize the relevant result. Redact passwords, submitted data, and account details.]*

### Figure A5 — Final verification
**[Insert screenshot here, if appropriate]**  
*Caption: [Show only the minimum evidence needed to substantiate the conclusion.]*
