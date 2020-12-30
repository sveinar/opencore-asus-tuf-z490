# OpenCore - ASUS TUF GAMING Z490-PLUS (WI-FI)

## Components

- ASUS TUF Gaming Z490-Plus Wifi
- Intel Core i7-10700K

- Corsair RM750x
- NZXT H510 White
- Corsair Force Series MP510 960 GB (two)
- Corsair Vengenance RGB PRO 64GB 3200MHz
- NZXT Kraken X63

- Gigabyte Radeon 5700 XT GPU (DisplayPort)

- For Wifi and Bluetooth
  - Wireless Network Card BCM94360CD Bluetooth 4.0 802.11AC Dual-band For Desktop

## OpenCore

Version 0.6.4.

## What is working

- iGPU (by removing agdpmod=pikera in the bootargs)
- Gigabyte Radeon 5700 XT GPU
- Audio out from the MB
- Bluetooth and Wifi using BCM94360CD card
- Handoff
- Airdrop

## What is not working

- HDMI/DP audio (dual booting to Windows and Realtek drivers overwriting)
