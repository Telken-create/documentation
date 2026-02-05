# System Information Inventory (CLI + GUI) #

## PC Overview
My PC has been prebuilt around 2018 with decent specs.
Here is the link https://pcpartpicker.com/user/Telken_/builds/#view=btk6Mp
# Manufacturer:
Gigabyte Technology Co., Ltd

## OS Name: 
```
Microsoft Windows 11 Pro
```
## CPU:
```
 Processor	Intel(R) Core(TM) i7-8700K CPU @ 3.70GHz, 3696 Mhz, 6 Core(s), 12 Logical Processor(s)

```
![image art](https://github.com/Telken-create/device-hardware-connector-map/blob/1191861bbb43a3830d291131dd7c22b904be8d78/intelcorei7.jpg)
<img width="295" height="33" alt="image" src="https://github.com/user-attachments/assets/8ede5991-3a82-4c47-ab75-5cbab3fb2d2e" />

## RAM :
```
Corsair Vengeance RGB Pro 16 GB (2 x 8 GB) DDR4-3200 CL16 Memory

```
![image alt](https://github.com/Telken-create/device-hardware-connector-map/blob/b8155877cefcbc323893bf8e8eab6222f59b6af7/Corsair%20Vengeance%20RGB%20Pro.jpg)
<img width="134" height="41" alt="image" src="https://github.com/user-attachments/assets/e4584660-64fd-4b8e-afb8-dba85ef8a07b" />

## GPU (Onboard or Dedicated):
```
Gigabyte TURBO OC GeForce GTX 1080 8 GB Video Card

```
![image alt](https://github.com/Telken-create/device-hardware-connector-map/blob/b8155877cefcbc323893bf8e8eab6222f59b6af7/gigabytegeforcegtx.jpg)
<img width="218" height="55" alt="image" src="https://github.com/user-attachments/assets/c915eccd-cd4f-4a94-8349-65e480a64a28" />

## Storage Type (HDD / SATA SSD / NVMe SSD): 
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



### How To PowerShell:
Today we will be using PowerShell to retrieve information
of our PC Specs!
Start of by seraching Powershell under Search bar and, rightclick PowerShell and click Run as Administrator.
This is where you will get started to run commands and search files, specs and more.
<img width="679" height="423" alt="image" src="https://github.com/user-attachments/assets/2244aca7-272e-4033-ac97-e3ae38e53d9e" />



***Find your PC Specs***

To find list of Computer Specs, type Get-ComputerInfo on PowerShell. Then, look up your specs

<img width="942" height="148" alt="image" src="https://github.com/user-attachments/assets/b15fc1a0-c95e-4247-9e89-0e0da7657a2f" />
<img width="503" height="22" alt="image" src="https://github.com/user-attachments/assets/5167af22-d4df-43ca-84cc-6af414a1f6e8" />

To find your GPU, type this command -->

```
gwmi win32_VideoController | FL Name
```
<img width="489" height="105" alt="image" src="https://github.com/user-attachments/assets/b0c17253-07f8-4125-812d-f273b4982e3b" />

***Find out your Ram***

To find your Ram, Type this command 
```
Get-WmiObject Win32_PhysicalMemory | Format-Table BankLabel, Capacity, Manufacturer

```

<img width="869" height="141" alt="image" src="https://github.com/user-attachments/assets/2005ae02-3f5b-41a4-8478-69ac66116565" />

***Find out your CPU***

To find your CPU, Type this command
```
Get-CimInstance Win32_Processor

```
<img width="970" height="114" alt="image" src="https://github.com/user-attachments/assets/b158b458-f81d-4c64-8917-8591d2389b7e" />





