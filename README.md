# Stadt Opfthal

**⚠️ Fictional municipality — created for security awareness demos only. No real systems or data involved.**

---

This repo shows how easy it is to build a targeted password list against a specific organization using nothing but their public website.

Tools used: **CeWL** (scrapes the site for words) and **CUPP** (generates password candidates based on personal/org info). The result is a wordlist tailored to "Stadt Opfthal" — way more effective than rockyou.txt against someone who works there.

The point isn't the attack. It's making the risk visible so people actually change their habits.

---

## What's in here

- `website/` — the fake Stadt Opfthal site (the CeWL target)
- `wordlists/` — generated wordlist output
- `demo/` — GIFs of the full demo
- `tips/` — password recommendations for users and orgs

---

## What users should do

- Use a password manager — stop reusing passwords
- Never use your org name, team, or workplace in a password
- Passphrases work: `Kaffee-Montag-Zürich-42!`
- Turn on MFA everywhere

## What organizations should do

- Block org-related terms in password policies
- Check passwords against breach databases (Have I Been Pwned)
- MFA is not optional
- Run awareness training — regularly, not once a year


