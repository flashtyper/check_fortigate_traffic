# check_fortigate_traffic
small icinga/nagios script to check the interface traffic of your fortigate

## Usage: 

```bash
./check_fortigate_traffic -h <host> -c <community> -v <version>
```

## Example
```
lukas@ubuntu: ./check_forti_traffic -h 192.168.2.1 -c public -v 2c
CHECK_NETWORK OK - everything is fine | wan1_IfAdminStatus=1;; wan1_IfHCInRate=12912758336;; wan1_IfHCOutRate=972132441;; wan1_IfHighSpeed=1000;; wan1_IfInDiscRate=0;; wan1_IfInErrRate=0;; wan1_IfOperStatus=1;; wan1_IfOutDiscRate=0;; wan1_IfOutErrRate=0;; wan1_IfSpeed=1000000000;; internal4_IfAdminStatus=1;; internal4_IfHCInRate=0;; internal4_IfHCOutRate=0;; internal4_IfHighSpeed=0;; internal4_IfInDiscRate=0;; internal4_IfInErrRate=0;; internal4_IfOperStatus=2;; internal4_IfOutDiscRate=0;; internal4_IfOutErrRate=0;; internal4_IfSpeed=0;; internal5_IfAdminStatus=1;; internal5_IfHCInRate=0;; internal5_IfHCOutRate=0;; internal5_IfHighSpeed=0;; internal5_IfInDiscRate=0;; internal5_IfInErrRate=0;; internal5_IfOperStatus=2;; internal5_IfOutDiscRate=0;; internal5_IfOutErrRate=0;; internal5_IfSpeed=0;; wan2_IfAdminStatus=1;; wan2_IfHCInRate=0;; wan2_IfHCOutRate=0;; wan2_IfHighSpeed=0;; wan2_IfInDiscRate=0;; wan2_IfInErrRate=0;; wan2_IfOperStatus=2;; wan2_IfOutDiscRate=0;; wan2_IfOutErrRate=0;; wan2_IfSpeed=0;; modem_IfAdminStatus=2;; modem_IfHCInRate=0;; modem_IfHCOutRate=0;; modem_IfHighSpeed=0;; modem_IfInDiscRate=0;; modem_IfInErrRate=0;; modem_IfOperStatus=2;; modem_IfOutDiscRate=0;; modem_IfOutErrRate=0;; modem_IfSpeed=0;; ssl.root_IfAdminStatus=1;; ssl.root_IfHCInRate=39459;; ssl.root_IfHCOutRate=672;; ssl.root_IfHighSpeed=0;; ssl.root_IfInDiscRate=0;; ssl.root_IfInErrRate=0;; ssl.root_IfOperStatus=1;; ssl.root_IfOutDiscRate=4;; ssl.root_IfOutErrRate=0;; ssl.root_IfSpeed=0;; internal1_IfAdminStatus=1;; internal1_IfHCInRate=796065261;; internal1_IfHCOutRate=1489723233;; internal1_IfHighSpeed=1000;; internal1_IfInDiscRate=0;; internal1_IfInErrRate=0;; internal1_IfOperStatus=1;; internal1_IfOutDiscRate=0;; internal1_IfOutErrRate=0;; internal1_IfSpeed=1000000000;; internal2_IfAdminStatus=1;; internal2_IfHCInRate=155452786;; internal2_IfHCOutRate=11302221362;; internal2_IfHighSpeed=1000;; internal2_IfInDiscRate=0;; internal2_IfInErrRate=0;; internal2_IfOperStatus=1;; internal2_IfOutDiscRate=0;; internal2_IfOutErrRate=0;; internal2_IfSpeed=1000000000;; internal3_IfAdminStatus=1;; internal3_IfHCInRate=0;; internal3_IfHCOutRate=0;; internal3_IfHighSpeed=0;; internal3_IfInDiscRate=0;; internal3_IfInErrRate=0;; internal3_IfOperStatus=2;; internal3_IfOutDiscRate=0;; internal3_IfOutErrRate=0;; internal3_IfSpeed=0;;
```
