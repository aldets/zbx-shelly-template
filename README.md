# zbx-shelly-template
Templates to monitor Shelly devices with Zabbix.</br>
Templates we created using Zabbix 6.0.</br>
Each subfolder is meant for that specific model/version. If some are missing, it means I don't have that model.</br>
Prerequisites:
  - A host in Zabbix
    - Add this themplate to the host
    - Add correct info in hosts "Inherited and host macros"

Macros to configure:
- {$SHELLY_HOST} > Either the IP address or a FQDN from your LAN (required)
- {$SHELLY_USER} > If configured
- {$SHELLY_PASS} > If configured
