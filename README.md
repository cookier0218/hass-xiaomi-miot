# Xiaomi Miot For HomeAssistant

## [Supported Devices](https://github.com/al-one/hass-xiaomi-miot/issues/12)

- HomeAssistant Domain
    - [Miot Device](https://miot-spec.org/miot-spec-v2/spec/devices)
        - [Miot Service](https://miot-spec.org/miot-spec-v2/spec/services)

- [sensor](https://www.home-assistant.io/integrations/sensor)
    - [water-purifier](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:water-purifier:00007821)
        - [tds-sensor](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:tds-sensor:0000780D)
    - [cooker](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:device:cooker:0000A00B)
    - [pressure-cooker](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:device:pressure-cooker:0000A04B)
    - [induction-cooker](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:device:induction-cooker:0000A033)
    - [oven](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:oven:00007862)
    - [microwave-oven](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:microwave-oven:00007843)
    - [health-pot](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:health-pot:00007860)
    - other
        - [environment](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:environment:0000780A)
        - [filter](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:filter:0000780B)
        - [battery](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:battery:00007805)
        - [tds-sensor](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:tds-sensor:0000780D)
        - [illumination-sensor](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:illumination-sensor:0000783D)
- [binary_sensor](https://www.home-assistant.io/integrations/binary_sensor)
    - [toilet](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:toilet:00007877)
- [air_quality](https://www.home-assistant.io/integrations/air_quality)
    - [air-monitor](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:device:air-monitor:0000A008)
        - [environment](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:environment:0000780A)
- [switch](https://www.home-assistant.io/integrations/switch)
    - [switch](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:switch:0000780C)
    - [outlet](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:switch:0000780C)
        - [power-consumption](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:power-consumption:0000780E)
    - [washer](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:washer:00007834)
    - [pet-drinking-fountain](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:pet-drinking-fountain:00007850)
- [light](https://www.home-assistant.io/integrations/light)
    - [light](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:light:0000A001)
    - [night-light](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:night-light:00007883)
- [fan](https://www.home-assistant.io/integrations/fan)
    - [fan](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:fan:00007808)
    - [ceiling-fan](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:ceiling-fan:00007849)
    - [hood](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:hood:0000782B)
    - [airer](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:airer:00007817)
        - [dryer](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:dryer:00007895)
- [climate](https://www.home-assistant.io/integrations/climate)
    - [air-conditioner](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:air-conditioner:0000780F)
        - [fan-control](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:fan-control:00007809)
        - [environment](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:environment:0000780A)
    - [air-conditioner-outlet](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:air-condition-outlet:000078A3)
    - [air-purifier](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:device:air-purifier:0000A007)
    - [air-fresh](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:air-fresh:00007822)
    - [dishwasher](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:dishwasher:0000784D)
    - [heater](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:device:heater:0000A01A)
    - [ptc-bath-heater](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:ptc-bath-heater:0000783B)
    - [light-bath-heater](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:light-bath-heater:0000783A)
    - [electric-blanket](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:electric-blanket:00007844)
    - [water-heater](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:water-heater:0000783E)
    - [water-dispenser](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:water-dispenser:00007891)
- [vacuum](https://www.home-assistant.io/integrations/vacuum)
    - [vacuum](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:vacuum:00007810) (Don't support clean area/point)
- [cover](https://www.home-assistant.io/integrations/cover)
    - [curtain](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:curtain:00007816)
    - [airer](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:airer:00007817)
        - [light](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:light:00007802)
- [humidifier](https://www.home-assistant.io/integrations/humidifier)
    - [humidifier](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:device:humidifier:0000A00E)
    - [dehumidifier](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:device:dehumidifier:0000A02D)
- [camera](https://www.home-assistant.io/integrations/camera)
    - [camera-control](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:camera-control:0000782F)
    - [camera-stream-for-google-home](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:camera-stream-for-google-home:00007831)
    - [camera-stream-for-amazon-alexa](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:camera-stream-for-amazon-alexa:00007830)
- [media_player](https://www.home-assistant.io/integrations/media_player)
    - [play-control](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:play-control:0000781D)
    - [speaker](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:speaker:0000781C)
    - [intelligent-speaker](https://miot-spec.org/miot-spec-v2/spec/service?type=urn:miot-spec-v2:service:intelligent-speaker:0000789B)


## Installing

> Copy `custom_components/xiaomi_miot` folder to `custom_components` folder in your HomeAssistant config folder

```shell
wget https://github.com/al-one/hass-xiaomi-miot/archive/master.zip
unzip master.zip
cp -rf hass-xiaomi-miot-master/custom_components/xiaomi_miot ~/.homeassistant/custom_components/
rm -rf hass-xiaomi-miot-master
```

> Or you can install component with [HACS](https://hacs.xyz)


## Config

### HomeAssistant GUI

> Configuration > Integrations > ➕ > Search `Xiaomi Miot Auto`


### Configuration variables:

- **host**(*Required*): The IP of your device
- **token**(*Required*): The Token of your device
- **name**(*Optional*): The name of your device
- **model**(*Optional*): The model of device, required if config by yaml


### Configuration Xiaomi Cloud:

> If your device return code -4004 or -9999 in logs, You can try this way.

```yaml
# configuration.yaml
homeassistant:
  customize: !include customize.yaml

xiaomi_miot:
  username: xiaomi_username
  password: xiaomi_password
  # server_country: cn

# customize.yaml (Configuration > Customize > Select Entity > Add Other Attribute)
camera.your_entity_id:
  miot_cloud: true          # Enable miot cloud for entity (read, write, action)
  # miot_cloud_write: true  # (Optional) Enable miot cloud (only write)
  # miot_cloud_action: true # (Optional) Enable miot cloud (only action)
  # miot_did: '123456789'   # (Optional) Your miot device id (Get form cloud if empty)
```

Enabled miot cloud for device:

> Configuration > Integrations > Xiaomi Miot Auto > Options > Enable miot cloud


### Customize entity

```yaml
# configuration.yaml
homeassistant:
  customize: !include customize.yaml

# customize.yaml (Configuration > Customize > Select Entity > Add Other Attribute)
climate.your_entity_id:
  bind_sensor: sensor.temperature_entity,sensor.humidity_entity # Sensor entities

camera.your_entity_id:
  video_attribute: 1 # https://github.com/al-one/hass-xiaomi-miot/issues/11#issuecomment-773054167
  check_lan: true    # Check LAN connection in cloud mode
```

> **Recommended**: [Customization Using The UI](https://www.home-assistant.io/docs/configuration/customizing-devices/#customization-using-the-ui)


## Debug

### Get Entity State Attributes

> Developer tools > State > Filter Entity

### Get Debug Logs

```yaml
logger:
  default: warning
  logs:
    custom_components.xiaomi_miot: debug
```


## Obtain miio token

- Use MiHome mod by [@vevsvevs](https://github.com/custom-components/ble_monitor/issues/7#issuecomment-595874419)
  1. Down apk from [СКАЧАТЬ ВЕРСИЮ 6.x.x](https://www.kapiba.ru/2017/11/mi-home.html)
  2. Create folder `/your_interlal_storage/vevs/logs/` ⚠️
  3. Find token from `vevs/logs/misc/devices.txt`
