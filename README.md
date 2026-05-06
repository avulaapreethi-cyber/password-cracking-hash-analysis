# Password Cracking & Hash Analysis Lab

## Overview
This project demonstrates password hash analysis and cracking techniques in a controlled lab environment using John the Ripper and Hashcat.

## Tools Used
- Kali Linux
- John the Ripper
- Hashcat

## Techniques Practiced
- MD5 hash generation
- Dictionary attacks
- Rule-based attacks
- Wordlist analysis
- Hash identification

## Example Commands

### Generate MD5 Hash
```bash
echo -n "admin123" | md5sum

AND Next

Crack Hash Using John

john --format=raw-md5 --wordlist=small.txt hash.txt

Crack Hash Using Hashcat

hashcat -m 0 -a 0 hash.txt small.txt
