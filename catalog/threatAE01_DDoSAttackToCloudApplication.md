/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /

## AE01 DDoS Attack To Cloud Application

|Context|Remote user interacts with a cloud application|
|Problem|DDoS/DoS attack against cloud application from the Internet|
|Solution|Ensure network and server capacity of cloud infrastructure;<br /> Apply Load Balancer;<br /> Apply Content Distribution Network (CDN);<br /> Apply packet filtering;<br /> Apply Access Control Lists (ACLs);<br /> Apply Web Application Firewall (WAF);<br /> Apply reputation-based blocking;<br /> Apply external DDoS protection;<br />|
|References|BNA-2: Denial of Service (DoS) attack against the cloud infrastructure via the public network infrastructure [SECCRIT];<br /> R.15: Distributed Denial Of Service (DDoS) [ENISA];<br /> Distributed Denial of Service [QUIRC];<br />|
|Type|ns:type_ThreatPattern|
|Victim|su:comp_CloudApplication|
|Aggressor|su:comp_RemoteUser|
|Aggr. role|ns:role_Client|
|STRIDE|ns:STRIDE_Denial_of_Service|
|THREAT|ns:threat_txTargetedProcessCrashing;<br /> ns:threat_txResourceExhaustion|

/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /
