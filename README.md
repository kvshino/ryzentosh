# OpenCore config.plist for Ryzen 9 5900X and Radeon RX 6800



<img src="https://github.com/kvshino/ryzentosh/blob/main/screenshots/specs.png" width=40% height=40%>
This repo contains my config for a completely functioning Ryzentosh. 
<br/>
<br/>

**macOS version**: 14.2 (23C64) \
**OpenCore version**: 0.9.7 

## Installation
  - Please be sure to generate your own SSDT-EC.aml according to the <a href="https://dortania.github.io/Getting-Started-With-ACPI/Universal/ec-methods/ssdttime.html">Dortania</a> guide \
  (or simply use the <a href="https://github.com/dortania/Getting-Started-With-ACPI/blob/master/extra-files/compiled/SSDT-EC-USBX-DESKTOP.aml">prebuilt</a> one, changing its name to SSDT-EC.aml).
  - Generate your SMBIOS like shown <a href="https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#platforminfo">here</a>.

## Verified Specification

| **Component**    | **Model**                                   |
| ---------------- | ------------------------------------------- |
| CPU              | AMD Ryzen 9 5900X @ 4.90GHz                 |
| Motherboard      | ASUS B550M-PLUS                             |
| RAM              | 32GB (2 x 16GB) Corsair Vengeance @ 3200MHz |
| GPU              | Sapphire Radeon RX 6800 16GB                |
| Audio Chipset    | ALC S1200A                                  |
| Ethernet         | Realtek RTL8125B 2.5Gb Ethernet             |
| OS Disk (NVMe)   | Samsung 980 Pro 512GB (PCIe 4.0)            |

## Benchmarks

- ### GeekBench 6
  - [CPU](https://browser.geekbench.com/v6/cpu/4041508)
    <br/>
    <img src="https://github.com/kvshino/ryzentosh/blob/main/screenshots/geekbench_cpu.png" width=50% height=50%>
  - [GPU OpenCL](https://browser.geekbench.com/v6/compute/1461431)
    <br/>
    <img src="https://github.com/kvshino/ryzentosh/blob/main/screenshots/geekbench_opencl.png" width=50% height=50%>
  - [GPU Metal](https://browser.geekbench.com/v6/compute/1461447)
    <br/>
    <img src="https://github.com/kvshino/ryzentosh/blob/main/screenshots/geekbench_metal.png" width=50% height=50%>

- ### BlackMagic Disk Speed Test
  - <img src="https://github.com/kvshino/ryzentosh/blob/main/screenshots/DiskSpeedTest.png" width=50% height=50%>

## Screenshots
  <img src="https://github.com/kvshino/ryzentosh/blob/main/screenshots/desktop_1.png" width=75% height=75%>
  <img src="https://github.com/kvshino/ryzentosh/blob/main/screenshots/desktop_2.png" width=75% height=75%>
  <img src="https://github.com/kvshino/ryzentosh/blob/main/screenshots/desktop_3.png" width=75% height=75%>
  
## Credits

- [Apple](https://apple.com) for macOS
- [AMD-OSX Developers](https://github.com/AMD-OSX) for kernel patches for AMD CPUs
- [Acidanthera](https://github.com/acidanthera) for OpenCore and kexts
- [Trulyspinach](https://github.com/trulyspinach) for Ryzen power management and monitoring kexts
- [Aluveitie](https://github.com/aluveitie) for RadeonSensor and RadeonGadget
- [Dortania](https://github.com/dortania) for OpenCore configuration guides
