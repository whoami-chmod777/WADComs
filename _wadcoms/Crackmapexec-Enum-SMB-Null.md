---
description: |
  "CrackMapExec (a.k.a CME) is a post-exploitation tool that helps automate assessing the security of large Active Directory networks." - https://github.com/mpgn/CrackMapExec/wiki. This command will enumerate the SMB host using a null session. 

  Command Reference:

  	Target IP: 10.10.10.1

command: |
  crackmapexec smb 10.10.10.1 -u '' -p ''
items:
  - No_Creds
services:
  - SMB
attack_types:
  - Enumeration
OS:
  - Linux
references:
  - https://github.com/mpgn/CrackMapExec
  - https://github.com/mpgn/CrackMapExec/wiki
---
