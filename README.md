This repository is dedicated to housing custom Sigma rules designed for Blue Team operations and Security Operations Center (SOC) environments.

Project Overview:
The goal of this lab is to create precise, behavior-based detection rules to identify malicious activity across enterprise networks while minimizing false positives.

Rule 1: Detect Suspicious PowerShell Encoded Commands

File Name: powershell_encoded_command.yml

Objective: Detects attackers using PowerShell with encoded commands or its short aliases (-enc, /enc, -en, /en) to bypass command-line auditing and logging.

Log Source: Windows Sysmon (Event ID 1)

Author: Abdul Aziz Taiba
