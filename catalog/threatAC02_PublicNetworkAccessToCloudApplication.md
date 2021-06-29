/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /

## AC02 Public Network Access To Cloud Application

|Context|Remote user interacts with a cloud application|
|Problem|Remote user connects to the cloud application though a public network (e.g. Wi-Fi) and can be attacked by a third-party adversary|
|Solution|Apply TLS encryption and certificate for the cloud application;<br /> Apply VPN access to the cloud application|
|References|BNA-4: Man-in-the-middle attack... [SECCRIT] |
|Type|ns:type_ThreatPattern|
|Victim|su:comp_RemoteUser|
|Aggressor|su:comp_CloudApplication|
|Aggr. role|ns:role_Server|
|STRIDE|ns:STRIDE_Information_Disclosure;<br /> ns:STRIDE_Tampering|
|THREAT|ns:threat_txTrafficAnalysisAndSniffing;<br /> ns:threat_txMessageSecrecyViolation;<br /> ns:threat_txSessionHijacking;<br /> ns:threat_txRoutePoisoning;<br /> ns:threat_txMessageReuse|

/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /
