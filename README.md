# esphome_esp32
YAML file examples for various ESP32 microcontrollers working with ESPHOME

## Examples include:

### esp32c3_qtpy_aht20.yaml
Adafruit ESP32C3 microcontroller in tiny QTPY format with AHT20 temperature/humidity sensor attached via i2c bus.

### esp32s2_aqi.yaml
Adafruit ESP32S2 microcontroller in Feather format with MS8607 temperature/humidity/pressure sensor and PMSA003i air quality particulate sensor attached via i2c bus. Also includes example configuration for BME280 sensor also via i2c bus.

### esp32s2_qtpy_aht20.yaml
Adafruit ESP32S2 microcontroller in tiny QTPY format with AHT20 temperature/humidity sensor attached via i2c bus.

### esp32s2_replay.yaml
Adafruit ESP32S2 microcontroller in Feather format with Feather Wing non-latching relay.

### esp_wroom32_neopixel.yaml
Adafruit ESPWROOM32 microcontroller in Feather format with custom Feather Wing proto board using SN74AHCT125N logic level shifter and external 5v power supply to drive Adafruit NeoPixel LED strips. LEDs can be controlled via Lovelace UI including on/off and color/white values and brightness. Includes configuration for RGBW and RGB NeoPixel strips.
