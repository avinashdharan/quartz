|   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|
||6e:42:f0:d5:08:b6|docserver|10.0.10.10|docserver||[](http://192.168.0.1/services_dhcp_edit.php?if=opt1&id=0 "Edit static mapping")[](http://192.168.0.1/services_dhcp.php?if=opt1&act=del&id=0 "Delete static mapping")|
||92:55:16:a5:66:f1||10.0.10.11|netserver||[](http://192.168.0.1/services_dhcp_edit.php?if=opt1&id=1 "Edit static mapping")[](http://192.168.0.1/services_dhcp.php?if=opt1&act=del&id=1 "Delete static mapping")|
||aa:11:c0:3c:d2:bb||10.0.10.12|entserver||[](http://192.168.0.1/services_dhcp_edit.php?if=opt1&id=2 "Edit static mapping")[](http://192.168.0.1/services_dhcp.php?if=opt1&act=del&id=2 "Delete static mapping")|
||42:12:9b:1d:3d:50||10.0.10.20|kubemaster||[](http://192.168.0.1/services_dhcp_edit.php?if=opt1&id=3 "Edit static mapping")[](http://192.168.0.1/services_dhcp.php?if=opt1&act=del&id=3 "Delete static mapping")|
||ca:fc:12:4e:ad:b7||10.0.10.21|knode1||[](http://192.168.0.1/services_dhcp_edit.php?if=opt1&id=4 "Edit static mapping")[](http://192.168.0.1/services_dhcp.php?if=opt1&act=del&id=4 "Delete static mapping")|
||c6:34:be:7f:3d:0a||10.0.10.22|knode2|


DNS setting backup
adf


local-data: "docserver.box A 10.0.10.10"
local-data: "netserver.box A 10.0.10.11"
local-data: "entserver.box A 10.0.10.12"
local-data: "proxmox.box A 192.168.0.10"
local-data: "kubemaster A 10.0.10.20"
local-data: "knode1 A 10.0.10.21"
local-data: "knode2 A 10.0.10.22"

local-data: "docserver.box A 192.168.0.50"
local-data: "netserver.box A 192.168.0.51"
local-data: "entserver.box A 192.168.0.52"
local-data: "proxmox.box A 192.168.0.10"
local-data: "lan.box A 192.168.0.7"
local-data: "kubemaster A 192.168.0.53"
local-data: "knode1 A 192.168.0.54"
local-data: "knode2 A 192.168.0.55"

