/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /

## AD01 Broken Authentication

|Context|Someone interacts with a cloud application|
|Problem|No authentication or broken (weak) authentication of the cloud application|
|Solution|Apply access-token authentication;<br /> Apply password-based authentication;<br /> Apply certificate-based authentication;<br /> Ensure no use of default passwords;<br /> Ensure security of credentials, avoid placement into source code;<br /> Apply credentials rotation policy;<br /> Apply strong passwords policy;<br /> Apply weak-password checks;<br /> Apply failed password delay;<br /> Apply failed password block by host;<br /> Apply multi-factor authentication;<br /> Apply mutual authentication;<br /> Apply social identity authentication;<br /> Apply Single-Sign-On;<br />|
|References|Broken Authentication [OWASP10];<br /> Insufficient Identity, Credential, Access and Key Management [CSA10];<br /> Multi-Factor Authentication, Federation (Single Sign-On), Access Token, Mutual Authentication [Rath];<br />|
|Type|ns:type_ThreatPattern|
|Victim|su:comp_CloudApplication|
|Aggressor|su:comp_CloudApplication;<br /> su:comp_ExternalService;<br /> su:comp_RemoteUser|
|Aggr. role|ns:role_Client|
|STRIDE||

/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /
