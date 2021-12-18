# Windows Configuration

**System Configuration**

```
  CPU       : AMD Ryzen 3 3100 4-Core Processor (8 CPUs), ~3.6GHz
  RAM       : Ripjaws V DDR4-3400MHz CL16-18-18-38 1.35V 8GB Single Stick
  SSD       : Walton Antique 256GB nvme m.2 SSD 
  HDD       : ATA TOSHIBA DT01ACA0 500GB
  MainBoard : Gigabyte B450M DS3H V2 Rev v1.0
  GPU       : AMD RX 470 4GB 
  OS [0]    : Arch Linux x86
  OS [1]    : Windows 10 Pro 21H1 
```

**System Info**
 * Windows ~ Installed on GPT partition with UEFI. 
 * Linux ~ not installed yet 

**Motherboard Bios Info**

 * F1-17-8-20-Factory Bios (F1) *(old factory version)*
 * B45MDS3H.F61 (F61) **(updated and current bios)**

### Drivers 
1. AMD RX 470 - [AMD Official Site](https://www.amd.com/en/support/graphics/radeon-400-series/radeon-rx-400-series/radeon-rx-470)
2. B450 Chipset - [AMD Official Site](https://www.amd.com/en/support/chipsets/amd-socket-am4/b450)
3. Gigabyte Drivers - [Gigabyte Official Site](https://www.gigabyte.com/bd/Motherboard/B450M-DS3H-V2-rev-10/support#support-dl-driver)

### GPU Settings
**Listed Stable AMD GPU Driver List** <br>
I've faced tons of issues in AMD driver. Like blue screen, dark screen, no display, fps drop, over heating etc. So I have decided to listing a stable driver list, may it help other's to choose the best driver for their devices. 

> Currently using **Adrenalin 2019 Edition 19.12.1 **

| No | Driver Version | Marks                              | Basic Info                                                                      |
|----|----------------|------------------------------------|---------------------------------------------------------------------------------|
|  1 | [19.11.3]()    | :star:                             | Best of older games.                                                            |
|  2 | [19.12.1](https://www.amd.com/en/support/kb/release-notes/rn-rad-win-19-12-1) 	  | :star: :star: :star: :star::star: | Fix for ac origins. **[Best, Stable]** |
| 3 | [20.2.2]()     | :star:                             | Old and **20.4.2** is better then that.                                         |
| 4 | [20.4.2](2)    | :star: :star: :star: :star: :star: | Best and most stable driver I've ever seen.                                     |
| 5 | [20.8.3]()     | :star: :star: :star: :star: :star: | This one is another stable driver and it's replaces **20.4.2** with latest updates. |
| 6 | [20.9.1]()     | :star:                             | **20.11.2** is better then that.                                                    |
| 7 | [20.11.2]()    | :star: :star: :star:               | Recommended and good for latest games, and slightly gave better fps.            |

### Global Settings
![amd_global_settings.jpg](amd_global_settings.jpg)



Farhan Sadik <br>
Square Development Group

