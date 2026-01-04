# NSP Auto Installer Maker

A tool to create custom installer NSP files for Nintendo Switch, supporting retro game ROMs and homebrew applications.

## ✨ Features
- Create forwarder NSPs for homebrew applications
- Build installer packages for RetroArch game ROMs
- Customizable application metadata (name, publisher, version)
- Random or manual Title ID generation
- Icon support (256x256 JPG)
- Automatic folder inclusion for SD card content

## 📖 How to Use

### 1️⃣ **Forwarder Tab**

**Step 1: Title ID**
Generate random Title IDs or fill them in manually

**Step 2: Icon**
Select a custom icon (must be a 256x256 .JPG file)
*Note: The same icon will be automatically loaded for the installer*

**Step 3: Application Type**
Choose the type:
- Homebrew
- RetroarchRom

**Step 4: Application Details**
Fill in:
- Name
- Publisher
- Version

**Step 5: Target Paths**
**For Homebrew:**
Set the folder name and the .nro file name
⚠️ Attention: Enter the exact file name

**For RetroArch ROM:**
Set the core.nro name and the ROM name
⚠️ Attention: Enter the exact file name

---

### 2️⃣ **Installer Tab**

**Step 1: Include Folders**
Add the folders to be copied to the SD card in the "Folders to include" field

**Step 2: Title ID (Installer)**
If you generated a random Title ID earlier, this field will be auto-filled
❗ Important: The installer Title ID must be different from the forwarder's Title ID

**Step 3: Installer Details**
Fill in as you wish:
- Name:
- Publisher:
- Version:

---

### 3️⃣ **Build Tab**

**Step 1: Output Folder**
Choose the destination folder to generate the .NSP file
⚠️ Note: If left in the TEMP folder, the file will be deleted when the application is closed

**Step 2: Build**
Click the Build button
Done! ✅

---

## ⚠️ **Disclaimer**
This tool is for educational and personal use only. Users are responsible for complying with local laws and respecting intellectual property rights. The developers are not responsible for any misuse of this software.

**FREEWARE AND NOT FOR COMMERCIAL USE!!!**
