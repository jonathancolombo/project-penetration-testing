# project-penetration-testing

Vulnerability Assessment and Penetration Test (VAPT) of the Docker container `gabrielec/ptexam4`.

## Scope
Black-box security assessment of the web application running in the container.

## Activities
- Information gathering and enumeration
- Network scanning
- Vulnerability assessment
- Exploitation

## Main findings
- SQL Injection – Authentication Bypass
- Local File Inclusion (arbitrary file read)
- Source code disclosure via `php://filter`
- Blind SQL Injection (username and password hash extraction)
- Offline password cracking with John the Ripper

## Contents
- `Report_Penetration_Testing` – full VAPT report
- `Note_Penetration_Testing` – course summary notes
- `Vulnerabilita` – key points of each phase, from Information Gathering to Post-Exploitation

## Author
Jonathan Colombo
