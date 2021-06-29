/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /

## AB01 Failure Of Cloud Application

|Context|Someone interacts with a cloud application|
|Problem|Unexpected failure of the cloud application|
|Solution|Ensure fault tolerance of the cloud infrastructure;<br /> Apply automatic recovery of the cloud application;<br /> Apply autoscaling of the cloud application;<br /> Apply clustrer-like configuration of the cloud application (failover and load balancing);<br />|
|References|TIS.043, TIS.142 [BDU]|
|Type|ns:type_ThreatPattern|
|Victim|su:comp_CloudApplication;<br /> su:comp_RemoteUser;<br /> su:comp_ExternalService|
|Aggressor|su:comp_CloudApplication|
|Aggr. role|ns:role_Server|
|STRIDE|ns:STRIDE_Denial_of_Service|
|Threat|ns:threat_txTargetedProcessCrashing;<br /> ns:threat_txResourceExhaustion|

/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /
