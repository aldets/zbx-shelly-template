# zbx-shelly-template
Templates to monitor Shelly devices with Zabbix.
Prerequisites:
  - A host in Zabbix
    - Add this themplate to the host
    - Add correct info in hosts "Inherited and host macros"

Macros to configure:
- {$SHELLY_HOST} > Either the IP address or a FQDN from your LAN (required)
- {$SHELLY_USER} > If configured
- {$SHELLY_PASS} > If configured
- {$MQTT_BROKER_HOST} > if configured (sample: tcp://mqtt.brocker.host:1883)
- {$MQTT_BROKER_USER} > If MQTT is configured
- {$MQTT_BROKER_PASS} > If MQTT is configured
