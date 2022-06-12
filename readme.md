# **My keys remapping setup**
This repository shows my shortcuts setup to get more productivity.

### **Go to**
- [Version Record](./version-record.json)

### **OS support**
- Windows 10, 11
- macOS

### **Packages requirement**
- [Brew](https://github.com/chinhchin/Brew-setup.git)
- [Fish Shell](https://github.com/chinhchin/Fish-Shell-setup.git)

### **Contents**

---

## **1. My key remapping and usage**
### **1.1 Keys remmapping**
- Map **\<Caps Lock\>** to **\<Left Ctrl\>**
- Map **\<Ctrl - h\>** to **\<Left\>**
- Map **\<Ctrl - j\>** to **\<Down\>**
- Map **\<Ctrl - k\>** to **\<Up\>**
- Map **\<Ctrl - l\>** to **\<Right\>**

### **1.2 Usage**
1. To reduce the distance ctrl is pressed in if the hand is placed on the keyboard.
2. To be able to move the cursor without leaving if the hand is placed on the keyboard
![hand](./readme-assets/Keys%20remapping/hand.png)

## **2. Windows keys remapping setup**
### **2.1 Sharpkey**
1. Download and install [Sharpkey](https://www.randyrants.com/sharpkeys394.msi).
2. Set setting to this.

### **2.2 Powertoy keyboard**
1. Download and install [Microsoft PowerToys](https://apps.microsoft.com/store/detail/microsoft-powertoys/XP89DCGQ3K6VLD).
2. Open powertoy by press "**Window**" logo key and type "*PowerToys*", press "**Enter**" and then click at power toy logo at taskbar ![PowerToys](./readme-assets/Windows/PowerToys.png)
3. At "**Keyboard Manager**" pane, set "**Remap a shortcut**" to this ![Remap a shortcut](./readme-assets/Windows/PowerToys-2.png)

## **3. macOS keys remapping setup**
### **3.1 Download and install [Karabiner application](https://karabiner-elements.pqrs.org)**

### **3.2 config**
1. At "**Simple modifications**" pane, press "*Add item*" button, set "**From key**" to "*caps_lock*" and set "**To key**" to "*left_control*"
![Simple modification](./readme-assets/macOS/simple-modification.png)
2. Add complex modification to assets by move "**complex_modifications**" folder to your "**~/Downloads**" directory and type this command to your terminal
```
cp ~/Downloads/complex_modifications/* ~/.config/karabiner/assets/complex_modification/
```
3. At "**Complex modifications**" pane, press "**Add rule**" button press "**Enable**" button at "*Left ctrl + hjkl to arrow keys Vim*" and "*change left_control+; to escape*".
![Complex modification](./readme-assets/macOS/complex-modification.png)
