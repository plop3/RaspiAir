# RaspiAir
Gestion de setup astrophoto

## Matériel
- Raspberry PI 5 8Go
- HAT M2 https://geekworm.com/products/x1001
- M2 1To
- Carte Bigtreetech SRK PICO https://github.com/bigtreetech/SKR-Pico/tree/master
- BME280 / DHT22
- 9DOF I2c (LSM303DLHC + L3GD20)
- Boitier https://geekworm.com/products/x1202-c1

## Fonctions
- Focuser
- Antibuées
- Park/Limits (9DOF)
- Astrophoto
  - CCDciel https://www.ap-i.net/ccdciel/en/start
  - Carte du ciel https://www.ap-i.net/skychart/fr/start
  - Indi https://indilib.org/
  - Phd2 https://openphdguiding.org/

  Le boitier est alimenté en 12V.
  Les fonctions Park/Limits sont assurées par le Raspberry Pi (Pas de bus I2c sur la carte SKR Pico).
  Le Raspberry est alimenté en 5V par la carte SKR Pico.
  Les fonctions focuser, antibuéees sont assurées par la carte SKR Pico.
