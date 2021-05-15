# fleetwood

macOS installation on a GA-H87-HD3 with an Intel i5-4570.

## Hardware

- **CPU:** Intel i5-4570
- **GPU:** ASUS NVIDIA GT 740
- **Memory:** DDR3 16GB
- **Motherboard:** Gigabyte GA-H87-HD3 v? BIOS v?
  - **Ethernet card:** Realtek RTL8111
  - **Audio codec:** Realtek ALC892
- **Storage:** SAMSUNG 840 EVO 120GB SSD
- **Power Supply:** Corsair 430M

## Issues

- Stuttering bluetooth and wireless mouse. Fixed by changing WiFi to 5GHz rather than 2.4GHz.
- Kernel panics. Removed GT 740 and seems to have fixed so far.

## To do

- Change to release versions of OpenCore
- Change to release versions of kexts
- Make bootable backup of this and studiomac
