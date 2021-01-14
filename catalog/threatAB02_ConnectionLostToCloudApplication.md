/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /

## AB02 Connection Lost To Cloud Application

|Context|Someone interacts with a cloud application|
|Problem|Connection lost to the cloud application|
|Solution|Ensure fault tolerance of the network connection;<br /> Apply clustrer-like configuration and load balancing of the cloud application;<br /> Apply Multi Availability Zone Deployment;<br /> Apply Content Distribution Networks (CDN)|
|References|BNA-3: Loss of wide-area network connectivity... [SECCRIT]|
|Type|ns:type_ThreatPattern|
|Victim|su:comp_CloudApplication;<br /> su:comp_RemoteUser;<br /> su:comp_ExternalService|
|Aggressor|su:comp_CloudApplication|
|Aggr. role|ns:role_Server|
|STRIDE|ns:STRIDE_Denial_of_Service|

/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /
