/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /

## AA04 Data Loss By Remote Service

|Context|Cloud application uses a remote service|
|Problem|Data loss (modification) by the remote service|
|Solution|Replace the remote service by a local one;<br /> Apply data encryption;<br /> Apply data backup;<br /> Apply data redundancy;<br /> Apply digital signatures;<br />|
|References||
|Type|ns:type_ThreatPattern|
|Victim|su:comp_CloudApplication|
|Aggressor|su:comp_ExternalService|
|Aggr. role|ns:role_Server|
|STRIDE|ns:STRIDE_Tampering|
|THREAT|ns:threat_txMessageIntegrityViolation;<br /> ns:threat_txCorruption|

/ [Home](/acctp/) / [Catalog](/acctp/catalog/) /
