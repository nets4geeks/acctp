/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /

## AD03 Data Breach By Cloud Application

|Context|Someone interacts with a cloud application|
|Problem|Data breach (information disclosure) by the cloud application|
|Solution|Ensure data security of cloud infrastructure;<br /> Apply data classification;<br /> Apply access controls as per classification;<br /> Avoid storing of sensitive data;<br /> Ensure strong encryption algorithms and protocols;<br /> Ensure security of key management;<br /> Ensure the use of strong hashing functions for storing passwords;<br /> Avoid Client Side Caching;<br />|
|References|Sensitive Data Exposure [OWASP10];<br /> Data Breaches [CSA10];<br /> R.19: Compromise service engine [ENISA];<br /> Compromise service engine [QUIRC];<br /> Computation on Encrypted Data [Rath];<br />|
|Type|ns:type_ThreatPattern|
|Victim|su:comp_CloudApplication|
|Aggressor|su:comp_CloudApplication;<br /> su:comp_ExternalService;<br /> su:comp_RemoteUser|
|Aggr. role|ns:role_Client|
|STRIDE|ns:STRIDE_Information_Disclosure|

/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /
