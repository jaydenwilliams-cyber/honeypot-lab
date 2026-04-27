# AWS Honeypot Lab — T-Pot 24.04.1

## Overview
## Overview
Deployed T-Pot honeypot framework on AWS EC2, exposed to the public internet to capture
real-world attack telemetry over 24 hours. Built a Python script to automate IOC extraction
and feed attack data into an LLM API for automated TTP mapping to MITRE ATT&CK.
Lab currently running — findings populating after collection window closes.


## Environment
- Cloud: AWS EC2 (us-east-2)
- Instance: m7i-flex.large (8GB RAM, 128GB storage)
- OS: Ubuntu 24.04 LTS
- Honeypot Framework: T-Pot 24.04.1 (Hive Edition)
- Active Honeypot Services: Cowrie, Dionaea, Honeytrap, Suricata, Elasticpot,
  Mailoney, Ciscoasa, Miniprint, Tanner, and more

## Setup
1. Deployed Ubuntu 24.04 EC2 instance on AWS
2. Configured security groups to expose all honeypot ports to the internet
3. Cloned T-Pot from telekom-security/tpotce
4. Installed T-Pot Hive edition with Kibana dashboard
5. Collected 24-hour attack telemetry

## Findings
*Populating after 24-hour collection window — check back soon.*

## MITRE ATT&CK Mapping
*Populating after analysis.*

## Screenshots
*Coming soon.*

## Tools Used
T-Pot, AWS EC2, Kibana, Elasticsearch, Suricata, Docker, Ubuntu
