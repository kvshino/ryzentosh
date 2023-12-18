# OpenCore config.plist for Ryzen 9 5900X and Radeon RX 6800


This repo contains my config for a completely functioning Ryzentosh. 
![specs](https://github.com/kvshino/ryzentosh/blob/main/screenshots/specs.png)
<br/>

**macOS version**: 14.2  \
**OpenCore version**: 0.9.7 


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
    ![CPU](https://github.com/kvshino/ryzentosh/blob/main/screenshots/geekbench_cpu.png)
  - [GPU OpenCL](https://browser.geekbench.com/v6/compute/1461431)
    ![GPU OpenCL](https://github.com/kvshino/ryzentosh/blob/main/screenshots/geekbench_opencl.png)
  - [GPU Metal](https://browser.geekbench.com/v6/compute/1461447)
    ![GPU Metal](https://github.com/kvshino/ryzentosh/blob/main/screenshots/geekbench_metal.png)

- ### BlackMagic Disk Speed Test
    ![BlackMagic Disk Speed Test](https://github.com/kvshino/ryzentosh/blob/main/screenshots/DiskSpeedTest.png)

## Screenshots
  ![desktop1](https://github.com/kvshino/ryzentosh/blob/main/screenshots/desktop_1.png)
  ![desktop2](https://github.com/kvshino/ryzentosh/blob/main/screenshots/desktop_2.png)
  ![desktop3](https://github.com/kvshino/ryzentosh/blob/main/screenshots/desktop_3.png)

## Credits

- [Apple](https://apple.com) for macOS
- [AMD-OSX Developers](https://github.com/AMD-OSX) for kernel patches for AMD CPUs
- [Acidanthera](https://github.com/acidanthera) for OpenCore and kexts
- [Trulyspinach](https://github.com/trulyspinach) for Ryzen power management and monitoring kexts
- [Aluveitie](https://github.com/aluveitie) for RadeonSensor and RadeonGadget
- [Dortania](https://github.com/dortania) for OpenCore configuration guides
