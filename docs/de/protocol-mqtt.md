![Logo](../../admin/shelly.png)

# ioBroker.shelly

## MQTT

### Wichtige Hinweise

- Es ist nicht möglich, den Shelly-Adapter mit einem existierenden MQTT-Broker in deinem Netzwerk zu verbinden
- Der Shelly-Adapter startet einen eigenen MQTT-Broker, welcher auf dem Port ``1882`` gestartet wird, um einen Konflikt mit anderen MQTT-Brokern auf dem gleichen System zu vermeiden
- Der Standard-Port des MQTT-Brokers kann in der Konfiguration des Adapters angepasst werden
- Es ist kein Wissen über das MQTT-Protokoll erforderlich - sämtliche Kommunikation wird intern behandelt

### Konfiguration

1. Öffne die Shelly-Adapter Konfiguration im ioBroker
2. Wähle ```MQTT und HTTP``` als *Protokoll* in den *Allgemeinen Einstellungen*
3. Öffne das Tab **MQTT Einstellungen**
4. Wähle einen Benutzernamen und ein sicheres Passwort (Du musst diese Informationen auf den Shelly-Geräten hinterlegen)

![iobroker_general](./img/iobroker_general_mqtt.png)

![iobroker_mqtt](./img/iobroker_mqtt.png)

Aktiviere MQTT auf deinen Shelly-Geräten:

1. Öffne die Shelly-Webkonfiguration in einem Browser (nicht in der Shelly App!)
2. Gehe zu ```Internet & Security settings -> Advanced - Developer settings```
3. Aktiviere MQTT und gib die gerade konfigurierten Benutzerdaten und die IP-Adresse deiner ioBroker-Installation ein - gefolgt von Port 1882 (beispielsweise ```192.168.20.242:1882```)
4. Speichere die Konfiguration - der Shelly startet automatisch neu

**Ändere nicht den ```(custom) MQTT prefix``` - der Adapter funktioniert nicht, wenn Du diesen Wert anpasst!**

![shelly gen1](./img/shelly_mqtt-gen1.png)

- **Ändere nicht die "client id" in dieser Konfiguration**
- **Für Generation 2 Geräte müssen alle RPC-Optionen aktiviert werden (siehe Screenshot)!**
- SSL darf nicht aktiviert werden

![shelly gen2](./img/shelly_mqtt-gen2.png)
