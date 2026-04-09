# Wordpress-Lab-Vulnerable

## Objective
Conduct a security assessment on a vulnerable WordPress instance deployed in a controlled environment in order to identify and exploit known vulnerabilities.

## Environment
> Vulnerable application obtained from Dockerlabs.es
> Deployment using Docker
> Attacker system: Kali Linux
> Isolated local network

## Disclaimer
"This lab was conducted in a controlled and authorized environment strictly for educational purposes."

## Lab Setup
1. Download the vulnerable environment from Dockerlabs

## Tools Used
> Nmap (network reconnaissance)
> WPScan (WordPress enumeration)
> Netcat (reverse shell connection)
> Public exploit based on CVE
> Reverse shell payload

## Reconnaissance
> Port scanning with Nmap to identify active services
> Identification of WordPress as the running CMS
> Enumeration of users and plugins using WPScan

## Vulnerability Analysis
> Identification of vulnerable plugin: Pie Register
> Research of associated vulnerability using CVE references
> Confirmation that the installed version is vulnerable

## Exploitation
> Use of a public exploit targeting the Pie Register vulnerability
> Cookie manipulation to achieve administrative session hijacking
> Unauthorized access to the WordPress admin panel

## Post-Exploitation
> Upload of a reverse shell to the target server
> Establishment of a remote connection using Netcat
> Gaining system-level access from the attacker machine

## Mitigation
> Update the vulnerable plugin to the latest version
> Remove untrusted or unused plugins
> Implement strong authentication controls
> Deploy a Web Application Firewall (WAF)

## Evidence
(Screenshots stored in the /Screenshots directory)

