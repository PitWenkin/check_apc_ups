# Check APC UPS
Nagios/Icinga script to check APC UPS devices

Used to check APC UPS switches https://www.apc.com

# Usage:
```
./check_apc_ups -h [hostname] -c [community]
```

# Options:
```
  -h [snmp hostname]	Hostname
  -c [community name]	community name (ex: public)
  -p [snmp port]	port for snmp request (default: 161)
  -t [timeout]		duration before doing an timeout in seconds - default 10s
```

# Examples:
```
  ./check_apc_ups -h 1.2.3.4 -c public 
  ./check_apc_ups -h 1.2.3.4 -p 4321 -c public -t 30
```
