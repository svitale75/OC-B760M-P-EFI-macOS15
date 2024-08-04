# An OpenCore (10.0.0) EFI that enables a MSI Pro B760M-P based PC to run macOS 15 Sequoia

**Machine's specs:**
- Motherboard details: MSI PRO B760M-P DDR4 ProSeries Motherboard
- CPU details: Intel Core i5-12400 Desktop Processor 18M Cache, up to 4.40 GHz (Alder Lake)
- GPU details: XFX Radeon RX 480 4GB GDDR5 True OC 1266MHz
- WiFi and Bluetooth: intel 

**Works with:**
- Sequoia 15.0 Beta (24A5298h)

**User's to do:** 
1. Download Sequioia - macOS 15.0 Beta (24A5298h)
2. Download **OpenCore Legacy Patcher**
3. Create mac OS istaller for macOS **Sequoia** to a drive
4. Build and install OpenCore to the same drive
5. Mount the drives **EFI** partition of your instal drive and delete it entirely
6. Download this project's latest **release** and unzip the archive, this will give you a single folder named **EFI**
7. Copy the  **EFI** to the root of your instal drive **EFI partition**
8. Download **OpenCore Configurator** and open **config.plist** from your EFI folder
9. Under **PlattformInfo**, select the DataHub - Generic - PlattformNVRAM. Select **MacPro7,1**
10. Save **config.plist**
11. Download the HeliPort.app from this [repository](https://github.com/OpenIntelWireless/HeliPort) and add it as a login item to show WiFi options on the menu bar
13. Download the RadeonGadget.app from this [repository](https://github.com/ChefKissInc/RadeonSensor) and add it as a login item to show GPU temp on the menu bar
14. After the installation, move the install drive's EFI to your main drive EFI partition
    
**Credits**
- [OpenCore](https://github.com/acidanthera/OpenCorePkg)
- [Acidanthera](https://github.com/acidanthera)
- [OpenCore Legacy Parcher](https://dortania.github.io/OpenCore-Legacy-Patcher/)

**System Info**

<img src="img/info2.png"/>

**Geekbench Results**

<img src="img/001.png" width="100%"/>
<img src="img/002.png" width="100%"/>
<img src="img/003.png" width="100%"/>
<img src="img/005.png" width="100%"/>
<img src="img/006.png" width="100%"/>
