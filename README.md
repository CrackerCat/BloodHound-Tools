# What is this?
A collection of tools that integrate to [BloodHound](https://github.com/BloodHoundAD/BloodHound).

Bloodhound is the defacto standard that both blue and red security teams use to find lateral movement and privilege escalation paths that can potentially be exploited inside an enterprise environment. 
A typical environment can yield millions of paths, representing almost endless opportunities for red teams to attack and creating a seemingly insurmountable number of attack vectors for blue teams to tackle. 

However, a critical dimension that Bloodhound ignores, namely network access, could hold the key to shutting down excessive lateral movement.
This repository contains tools that integrate with Bloodhound’s database in order to reflect network access, for the benefit of both red and blue teams. 

Read more [here](https://zeronetworks.com/blog/adversary-resilience-via-least-privilege-networking-part-1/).
 
# Tools List
## ShotHound
Validate practical paths discovered by BloodHound with [CornerShot](https://github.com/zeronetworks/cornershot).  

## Ransomulator
Simulate ransomware-like infection in your dataset.

## DBCreator
Simulate BloodHound dataset, along with "Open" network access edges.

## CustomQueries
A list of common queries that reflect the network dimension, if it is integrated into the dataset.

## VulnerabilitiesDataImport
Parse Vulnerability Scanners reports and enrich host nodes with information about unpatched vulnerabilities