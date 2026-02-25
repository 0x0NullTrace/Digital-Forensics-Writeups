# Digital-Forensics-Writeups

Digital Forensics Write-up: Case "The Ghost Artifact" :

I am pleased to share my successful completion of a simulated digital forensics investigation aimed at uncovering suspicious employee activity prior to resignation.

Case Overview: An employee resigned abruptly, leaving behind suspicions of executing a hacking tool and deleting it to cover their tracks. The challenge was to prove "Action," "Intent," and "Timing" despite the physical file being missing from the disk.

Lab Tools Used (Flare-VM):

KAPE: For forensic artifact acquisition.
PECmd: For parsing Prefetch files and extracting execution timestamps.
Registry Explorer: For deep diving into NTUSER.DAT and analyzing UserAssist logs.
Timeline Explorer: To correlate events and reconstruct the incident timeline.

Key Findings:

Identification: Successfully traced the deleted executable named HackTool.exe.
Suspicious Location: The program was executed from a hidden path: C:\Windows\Temp\Hidden_Tool\.
Proof of Intent: By analyzing the UserAssist GUID, I proved that the execution was initiated manually via the Graphical User Interface (GUI), refuting any possibility of automated system triggers.
Temporal Evidence: Achieved second-by-second correlation between the Registry run-time and the Prefetch activation logs.

Digital Forensics is not just about using tools; it's about connecting the dots to reveal the truth.

Full report in screenshots below.

#DigitalForensics #DFIR #CyberSecurity #BlueTeam #InformationSecurity #Investigation #FlareVM #0x0NullTrace #IncidentResponse
