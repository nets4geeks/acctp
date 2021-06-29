/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /

## AD02 Broken Access Control

|Context|Someone interacts with a cloud application|
|Problem|No access control, broken (weak) access control, and the authorization issues of the cloud application|
|Solution|Follow the principle of least privilege;<br /> Apply Authorization;<br /> Apply Audit;<br /> Apply Mandatory Access Control (MAC);<br /> Apply Discretionary Access Control (DAC);<br /> Apply Role-Based Access Control (RBAC);<br /> Apply management of user sessions;<br /> Secure user IDs and tokens;<br /> Ensure proper file permissions;<br /> Avoid Path Traversal;<br />|
|References|Broken Access Control [OWASP10]|
|Type|ns:type_ThreatPattern|
|Victim|su:comp_CloudApplication|
|Aggressor|su:comp_CloudApplication;<br /> su:comp_ExternalService;<br /> su:comp_RemoteUser|
|Aggr. role|ns:role_Client|
|STRIDE|ns:STRIDE_Elevation_of_Privilege|
|THREAT|ns:threat_txUnauthorizedAccess;<br /> ns:threat_txInvokingUnauthorizedOperations;<br /> ns:threat_txBypassingControls;<br /> ns:threat_txLeveragingAuthorizationModel|

/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /
