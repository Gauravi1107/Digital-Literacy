# Case Study: Phishing Attack — The 2016 Google Docs Phishing Campaign

## What Is Phishing?

Phishing is a type of cybercrime in which an attacker impersonates a trusted entity — such as a bank, employer, or technology company — to deceive victims into revealing sensitive information or granting unauthorized access to their accounts or systems.

---

## Real-World Incident

In May 2017, a large-scale phishing campaign exploited Google's own OAuth system. Attackers sent emails that appeared to be a legitimate Google Docs sharing invitation from a known contact. The email was genuine-looking in every detail — it came through real Google infrastructure, making it especially convincing.

**Source:** *The Guardian*, "Google Docs phishing attack: what happened and what to do," May 4, 2017.

---

## How It Happened — Step by Step

1. **Bait sent:** Victims received an email saying someone shared a Google Doc with them.
2. **Trust established:** The sender appeared to be a real contact, and the email passed spam filters.
3. **Link clicked:** Victims clicked "Open in Docs," which redirected them to a real Google login page.
4. **Permissions granted:** A malicious third-party app — disguised as "Google Docs" — requested full access to Gmail and Contacts.
5. **Propagation:** The app automatically emailed the same phishing link to all of the victim's contacts.

---

## Who Was Targeted?

The attack targeted **general Gmail users**, with a heavy focus on journalists, academics, and professionals whose email contacts made the self-propagating attack more impactful. An estimated **one million accounts** were compromised within hours.

---

## Consequences

- Victims lost control of their Gmail accounts and contact lists.
- Sensitive personal and professional emails were exposed to unauthorized third parties.
- Google was forced to shut down the malicious app within approximately one hour and revoke all granted OAuth tokens.
- The incident highlighted critical gaps in how users and platforms handle third-party app permissions.
- Organizationally, businesses whose employees fell victim risked data breaches, reputational damage, and potential regulatory penalties under data protection laws.

---

## Key Takeaway

Phishing attacks succeed not through technical complexity, but through social engineering — exploiting trust, urgency, and familiarity. Awareness and caution before clicking links or granting app permissions remain the strongest defenses.
