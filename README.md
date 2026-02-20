# KQL
KQL Queries to detect common attacks against M365.

As I have worked throught the Microsoft Cloud Attack and Defend bootcamp from Pwnedlabs, I have learned a ton about attacking M365 and Entra ID.

The bootcamp also provides defensive advice, and KQL for detecting these attacks. However, the KQL is often not production ready, and is generally written for Microsoft Sentinel rather than Defender advanced hunting.

To test what I have learned, I have taken the provided KQL and modified it to work with Advanced Hunting, and also used Codex to improve it, resulting in fewer false positive detections. Feel free to use these queries as custom detection rules to defend your environment!
