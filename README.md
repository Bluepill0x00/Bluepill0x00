```bash
Bluepill0x00@:~$ whoami
Sneha Chaudhary

Bluepill0x00:~$ whatis role
Cybersecurity Analyst | Creative Writer

Bluepill0x00:~$ cat log.txt
> Focus : Web Security, Forensics, Linux Administration
> Tools : Kali Linux, Fedora, Burp Suite, Wireshark, CyberChef, VirusTotal, Docker
> Langs : Python, JavaScript, PHP, C/C++

Bluepill0x00:~$ forensics-tool --trace-graph
+-------------------------------------------------------------------------+
|                         [ Sample_File.eml ]                             |
|                                  |                                      |
|            +---------------------+---------------------+                |
|            |                                           |                |
|            v                                           v                |
|    [ Header_Data ]                              [ Email_Body ]          |
|            |                                           |                |
|            |====( CyberChef: Decode )====>             |                |
|            v                                           v                |
|  ( Domain Mismatch Check )                    ( URL Extraction )        |
|            \                                           /                |
|             +---------> [ VirusTotal Engine ] <-------+                 |
|                                   |                                     |
|                                   v                                     |
|                        [ Threat / Phishing Score ]                      |
|                                   |                                     |
|                                   v                                     |
|                         [ Forensic_Report.log ]                         |
+-------------------------------------------------------------------------+
[+] Status  : Header Analysis & URL Scan Complete
[+] Verdict : SUSPICIOUS | Confidence: High | Artifact Logged

Bluepill0x00:~ echo $Currently
Breaking web apps, digital forensic investigations, and writing clean documentation.
