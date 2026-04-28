# AWS Honeypot Lab — T-Pot 24.04.1

## About

I'm Jayden Williams, a cybersecurity student at Hillsborough Community College pursuing an A.A. in Cybersecurity. I hold CompTIA Security+ and CySA+ certifications and am targeting SOC Analyst and GRC roles.

I built this lab to gain hands-on experience with threat detection, attack telemetry analysis, and MITRE ATT&CK mapping in a real-world environment. Rather than simulated traffic, this honeypot captures live attack data from the public internet — automated scanners, brute force attempts, and reconnaissance probes hitting within hours of deployment.

## Overview

Deployed T-Pot 24.04.1 on AWS EC2, exposed to the public internet to capture real-world attack telemetry. Analyzed attack data through Kibana dashboards and Elasticsearch, identifying attacker TTPs and mapping findings to MITRE ATT&CK.

## Environment

| Component | Details |
|---|---|
| Cloud | AWS EC2 (us-east-2) |
| Instance | m7i-flex.large (4 vCPU, 8 GiB RAM, 128 GiB storage) |
| OS | Debian GNU/Linux |
| Honeypot Framework | T-Pot 24.04.1 (Hive Edition) |
| Active Honeypots | Cowrie, Ciscoasa |
| Analysis Stack | Elasticsearch, Kibana, Suricata |

## Setup

1. Deployed Debian EC2 instance on AWS in us-east-2
2. Configured security group to expose all honeypot ports to the internet (0.0.0.0/0)
3. Cloned T-Pot from `telekom-security/tpotce`
4. Ran installer with Hive edition configuration
5. Accessed Kibana dashboard to monitor live attack telemetry

## Findings

*Populating after collection window closes — check back soon.*

## MITRE ATT&CK Mapping

*Populating after analysis.*

## Screenshots

*Coming soon.*

## Tools Used

T-Pot, AWS EC2, Kibana, Elasticsearch, Suricata, Docker, Debian
