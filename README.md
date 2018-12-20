# LINE_Simple_Beacon_ESP32
Arduino code for LINE Simple Beacon work with ESP32

This is fixed version of original source
https://engineering.linecorp.com/ja/blog/detail/149/?fbclid=IwAR19FZud8YY5wNpAYfeQ9gvV3DI6bG8xOb95T8dFc8IkR6E6XM12EWUN4DI

FIXED
- Stack overflow in MAX_BLE_ADVERTISING_DATA_SIZE declare.
- Fix static void updateSimpleBeaconDeviceMessage(char dm[], int dmsize) to support full length of device message(13 byte).
