# Airgradient-ESPHome
ESPHome config file for AirGradient ONE

Attempts to mimic the original firmware while providing homeassistant integration and addition features.

Heavily influenced by [MallocArray's config](https://github.com/MallocArray/airgradient_esphome) and the [original firmware](https://github.com/airgradienthq/arduino/blob/master/examples/ONE_V9/ONE_V9.ino)

The display uses fonts from U8g2: 
https://github.com/olikraus/u8g2

Requries a secret.yaml containing the following items:
```
wifi_ssid: ""
wifi_password: ""
# true/false
hidden_ssid:
```


TODO:
* re-add support for uploading to airgradient cloud without bricking on networks lacking internet access
