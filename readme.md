# **My keys remapping setup**
This repository shows my key remapping setup to get more productivity.

### **Go to**
- [Versions Recording](./versions.json)

### **OS support**
- Windows
- macOS

### **Contents**
#### [My key remapping and usage](./readme.md#1-my-key-remapping-and-usage)
1. [Keys reamapping](./readme.md#11-keys-remapping)
2. [Usage](./readme.md#12-usage)

#### [Windows keys remapping setup](./readme.md#2-windows-keys-remapping-setup)
1. [Sharpkey](./readme.md#1-sharpkey)
2. [PowerToys keyboard manager](./readme.md#2-powertoys-keyboard-manager)

#### [macOS keys remapping setup](./readme.md#macos-keys-remapping-setup)
1. [Download and install Karabiner-Element](./readme.md#1-download-and-install-karabiner-elementshttpskarabiner-elementspqrsorg)
2. [Conig Karabiner Element](./readme.md#2-config-karabiner-element)

---

## **My key remapping and usage**
### **1. Keys remapping**
- Map **\<Caps Lock\>** to **\<Left Ctrl\>**
- Map **\<Ctrl - h\>** to **\<Left\>**
- Map **\<Ctrl - j\>** to **\<Down\>**
- Map **\<Ctrl - k\>** to **\<Up\>**
- Map **\<Ctrl - l\>** to **\<Right\>**

### **2. Usage**
1. To reduce the distance ctrl is pressed in if the hand is placed on the keyboard.
2. To be able to move the cursor without leaving if the hand is placed on the keyboard
![hand](./readme-assets/Keys%20remapping/hand.png)

## **Windows keys remapping setup**
### **1. Sharpkey**
1. Download and install [Sharpkey](https://www.randyrants.com/sharpkeys394.msi).
2. Set setting to this.
![](./readme-assets/Windows/sharpkey.png)
3. Press "**Write to Registry**" button.
4. Reboot your device.

### **2. PowerToys keyboard manager**
1. Download and install [Microsoft PowerToys](https://apps.microsoft.com/store/detail/microsoft-powertoys/XP89DCGQ3K6VLD).
2. Open powertoy by press "**Window**" logo key and type "*PowerToys*", press "**Enter**" and then click at power toy logo at taskbar ![PowerToys](./readme-assets/Windows/PowerToys.png)
3. At "**Keyboard Manager**" pane, set "**Remap a shortcut**" to this ![Remap a shortcut](./readme-assets/Windows/PowerToys-2.png)

## **macOS keys remapping setup**
### **1. Download and install [Karabiner-Elements](https://karabiner-elements.pqrs.org)**

### **3. Config Karabiner-Element**
1. At "**Simple modifications**" pane, add items *caps_lock* -> *left_control* and *fn* -> *left_command*.
![Simple modification](./readme-assets/macOS/simple-modification.png)
2. Add *achinhchin-vim-key* complex modification to assets by type this command to your terminal.
```
# Clone this repository
git clone https://github.com/chinhchin/Keys-remapping-setup.git ~/Downloads/Keys-remapping-setup/

# Copy folder
cp ~/Downloads/Keys-remapping-setup/achinhchin-vim-key.json ~/.config/karabiner/assets/complex_modifications/
```
3. At "**Complex modifications**" pane, press "**Add rule**" button press "**Enable**" button at "*Left ctrl + hjkl; to arrow keys Vim*".
![Complex modification](./readme-assets/macOS/complex-modification.png)
