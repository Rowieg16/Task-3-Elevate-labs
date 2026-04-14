# task-3-Elevate-labs

##  Overview
Use free tools to identify common vulnerabilities on your computer

## Tool Used
- Nessus Essentials (Tenable)

## Scan Details

| Parameter        | Value                |
|------------------|---------------------|
| Target IP        | 172.20.10.5         |
| Scan Type        | Basic Network Scan  |
| Scanner          | Local Scanner       |
| Severity Base    | CVSS v3.0           |
| Scan Duration    | ~9 minutes          |
| Status           | Completed           |


## Summary of Findings

| Severity   | Count |
|------------|------|
| Critical   | 0    |
| High       | 0    |
| Medium     | 1    |
| Low        | 0    |
| Info       | 96   |
| **Total**  | 97   |


## Identified Vulnerability

## SSL Certificate Cannot Be Trusted

- **Severity:** Medium  
- **CVSS Score:** 6.5  
- **Category:** SSL/TLS  

## Description
The scan detected that the SSL certificate used by the target system is not trusted. This typically occurs when the certificate is self-signed or issued by an untrusted Certificate Authority (CA).

## Risk
An untrusted certificate may allow attackers to perform **Man-in-the-Middle (MITM)** attacks, compromising data confidentiality.

## Recommended Fix
- Replace the certificate with one issued by a trusted Certificate Authority
- Properly configure SSL/TLS settings
- Ensure certificate chain validation is correct

##  Informational Findings

- SSL Certificate Information  
- Supported SSL Cipher Suites  
- TLS Configuration Details  
- SMB Service Enumeration  
- HTTP Service Detection  
- Open Ports and Service Discovery  
- MySQL Server Detection  

