<div align="center">

# NETWORKWALKS-B084-WEEK3-PM1-2

### Week 3 | Password Auditing and Encrypted PDF Password Recovery

**NetworkWalks Cybersecurity Internship Program | Batch B084**

Practical password auditing using John the Ripper, Johnny GUI, PDF hash extraction and dictionary-based password recovery.

</div>

---

## Project Overview

This project involved practical password auditing and recovery exercises as part of the **NetworkWalks Cybersecurity Internship Program (B084)**. The activities focused on examining the security of password-protected PDF documents and understanding how weak or predictable passwords can be identified through dictionary-based password attacks.

The project was divided into two modules. **Project Module 1 (PM1)** involved extracting password hashes from three encrypted PDF documents, configuring John the Ripper through Johnny GUI and performing password recovery using wordlists. **Project Module 2 (PM2)** involved using NetworkWalks' online PDF password recovery tool to extract password verification data and conduct password recovery through its browser-based interface.

Both modules provided practical experience with password hash extraction, password auditing tools and dictionary-based recovery techniques.

## Objectives

- Extract password hashes from encrypted PDF documents.
- Configure John the Ripper Jumbo through Johnny GUI.
- Understand how PDF password verification data is processed.
- Perform dictionary-based password recovery using wordlists.
- Use NetworkWalks' online PDF password recovery tool.
- Evaluate the effectiveness of common password-guessing techniques.
- Understand the security implications of weak and predictable passwords.

## Tools and Technologies

| Tool / Technology | Purpose |
|---|---|
| Windows 10 Virtual Machine | Environment used to perform the exercises |
| John the Ripper Jumbo | Password auditing and recovery |
| Johnny GUI | Graphical interface for managing John the Ripper |
| PDF Hash Extraction Tools | Extracting password hashes from encrypted PDF documents |
| Password Wordlists | Supplying candidate passwords for dictionary attacks |
| NetworkWalks Online Password Recovery Tool | Browser-based PDF hash extraction and password recovery |

---

# Project Module 1 (PM1) | John the Ripper

## 1. PDF Hash Extraction

The first stage involved extracting password verification data from three password-protected PDF documents.

Encrypted PDF documents do not directly expose their original passwords. Instead, password verification data is stored within the document's security structure. Password auditing tools can extract this information into a hash format that can subsequently be tested against candidate passwords.

A PDF hash extraction tool was used to process each of the three documents. The extracted hashes were saved individually as `Hashfile1.txt`, `Hashfile2.txt` and `Hashfile3.txt` for use with John the Ripper.


