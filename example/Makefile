ARDUINO_VARIANT = nodemcu
SERIAL_PORT = /dev/ttyUSB0
# uncomment and set the right serial baud according to your sketch (default to 115200)
#SERIAL_BAUD = 115200
# uncomment this to use the 1M SPIFFS mapping
#SPIFFS_SIZE = 1
USER_DEFINE = -D_SSID_=\"$(shell echo $ADJUTANT_SSID)\" -D_WIFI_PASSWORD_=\"$(shell echo $ADJUTANT_PASSWORD)\"
OTA_IP = 192.168.0.13
OTA_PORT = 1337
OTA_AUTH = password
include ../esp8266Arduino.mk
