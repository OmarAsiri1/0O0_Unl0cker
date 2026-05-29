0O0_Unl0cker
0O0_Unl0cker is a high-performance, automated toolkit designed for iOS forensics and device management. It leverages the checkm8 exploit to provide full control over vulnerable iOS devices, from DFU entry to PongoOS injection and data extraction.
Features:

- 🚀 Automated Workflow: Seamless transition from normal mode to DFU and PongoOS injection.
- 📂 Data Extraction: Reliable extraction of DCIM (photos) and critical file system data.
- 🔑 Passcode Utilities: Advanced commands for passcode-related operations (where supported).
- 🛠 Native Performance: Optimized for macOS with low-level hardware interaction.
- 🖥 Modular Design: Built for efficiency and ease of use.
Getting Started
Download the latest version directly from our Releases Page.
  # Getting Started!
1. Prepare your environment:
Ensure you have the necessary dependencies installed:
```bash
brew install libusb
```
2. Navigate To The Directory: 
```bash
cd ~/0O0_Unl0cker
```
3. Make it executable:
```bash
chmod +x unl0cker
```
4. See Avilable Options
```bash
./unl0cker --help
```

# Quick Commands
- Trigger the exploit and boot PongoOS:
```bash
./unl0cker --exploit
```

- Dump photos to a specific directory (After Booting PongoOS):
```bash
./unl0cker --dump-photos --path ~/Desktop/iPhone_Photos
```

- Disclaimer
This tool is strictly for educational and authorized security research purposes only. The developer assumes no liability for any misuse or data loss. Ensure you have proper authorization before performing operations on any device.
License
Distributed under the MIT License. See ⁠LICENSE⁠ for more information.
