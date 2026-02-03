# device-hardware-connector-map
Documenting all external ports and identifying motherboard/ platform details specs and more
Document all external ports, if you can open your desktop also identify all internal connectors. Please take 6-10 labeled photos (ports + any internal components you can safely access) A one page "connector map" (diagram/table) that matches port/connector -> purpose -> common issue (ex: USB C data + power + video sometimes: common issue: wrong cable (Thunderbolt))

If you have a laptop:

Use system tools to identify motherboard / platform details
Collect screenshots: 
System Information (Model/Bios), 
Device Manager (Network adapters, Display adapters), 
Storage type (disk drives / task manager) (HDD/SATA SSD, NVMe SSD (Capacity vs storage left))
OS Name
In general (specs)
Manufacturer and Model of Device
CPU
Cores + threads
RAM Amount
RAM Speed 
On board or dedicated GPU (Model?)

UEFI or Legacy BIOS Mode?
Secure Boot Enabled?
Do you have a TPM?



## Device Overview
My PC has been prebuilt around 2018 with decent specs.
Here is the link https://pcpartpicker.com/user/Telken_/builds/#view=btk6Mp
# Manufacturer:
Gigabyte Technology Co., Ltd''

# OS Name: 
```
Microsoft Windows 11 Pro
```
# CPU:
```
 Processor	Intel(R) Core(TM) i7-8700K CPU @ 3.70GHz, 3696 Mhz, 6 Core(s), 12 Logical Processor(s)

```
![image art](https://github.com/Telken-create/device-hardware-connector-map/blob/1191861bbb43a3830d291131dd7c22b904be8d78/intelcorei7.jpg)
<img width="295" height="33" alt="image" src="https://github.com/user-attachments/assets/8ede5991-3a82-4c47-ab75-5cbab3fb2d2e" />

# RAM :
```
Corsair Vengeance RGB Pro 16 GB (2 x 8 GB) DDR4-3200 CL16 Memory

```
![image alt](https://github.com/Telken-create/device-hardware-connector-map/blob/b8155877cefcbc323893bf8e8eab6222f59b6af7/Corsair%20Vengeance%20RGB%20Pro.jpg)
<img width="134" height="41" alt="image" src="https://github.com/user-attachments/assets/e4584660-64fd-4b8e-afb8-dba85ef8a07b" />

# GPU (Onboard or Dedicated):
```
Gigabyte TURBO OC GeForce GTX 1080 8 GB Video Card

```
![image alt](https://github.com/Telken-create/device-hardware-connector-map/blob/b8155877cefcbc323893bf8e8eab6222f59b6af7/gigabytegeforcegtx.jpg)
<img width="218" height="55" alt="image" src="https://github.com/user-attachments/assets/c915eccd-cd4f-4a94-8349-65e480a64a28" />

# Storage Type (HDD / SATA SSD / NVMe SSD): 
```
2x Samsung 850 Evo 250 GB 2.5" Solid State Drive
Samsung SM961 1 TB M.2-2280 PCIe 3.0 X4 NVME Solid State Drive

```
 ![image alt](https://github.com/Telken-create/device-hardware-connector-map/blob/3681e1d153657c566d769ecf606daa6b51f9da0f/Samsung%20Evo%20250.jpg)
 ![image alt](https://github.com/Telken-create/device-hardware-connector-map/blob/3681e1d153657c566d769ecf606daa6b51f9da0f/Samsung%20SM961.jpg)
 <img width="293" height="112" alt="image" src="https://github.com/user-attachments/assets/9e082fd5-35df-4571-895f-8431eecbef24" />


 

## External & Internal Connector Map

| Port / Connector | Location | Purpose | Common Issues |
|-----------------|----------|---------|---------------|
| USB-C | Left side | Data, Power, Video | Wrong cable (non-Thunderbolt) |
| USB-A 3.0 | Right side | Peripheral connection | Port wear / insufficient power |
| HDMI | Left side | External display | No signal due to resolution mismatch |
| Ethernet (RJ-45) | Rear | Wired networking | Bent pins / driver issues |
| RAM Slot | Internal | Memory expansion | Improper seating |
| NVMe Slot | Internal | Primary storage | BIOS not detecting drive |

## System Information Evidence

### System Information
![System Info](screenshots/system_information.png)

### Device Manager – Network Adapters
![Network](screenshots/device_manager_network.png)

### Device Manager – Display Adapters
![Display](screenshots/device_manager_display.png)

### Storage Information
![Storage](screenshots/storage_info.png)

### BIOS / UEFI
![BIOS](screenshots/bios_uefi.png)

### How To:
Use PowerShell to retrieve information

**Find out your current TimeZone**
