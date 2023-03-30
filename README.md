# tor_setings

SOCKSPort 37.252.15.134:31100

Log notice file /dev/null
Log debug file /dev/null

IPv6Exit 1

RunAsDaemon 1

BridgeRelay 0
ExitRelay   0
ORPort      0
DirPort     0

AvoidDiskWrites 1
Sandbox 1 
SafeSocks 1

EnforceDistinctSubnets 1
ClientDNSRejectInternalAddresses 1
ServerDNSDetectHijacking 1
GeoIPExcludeUnknown 1


#запрет вход
ExcludeExitNodes {ru},{ua}

#выход  {de}, {fr}, {fi}, {nl}, {nz}, {no}, {ch}, {se}, {dk}, {ee}
ExitNodes {NL}

StrictNodes 1
