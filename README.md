# 🧠 Configuration Marlin personnalisée / Custom Marlin Configuration

## 🇫🇷 Français

### 🖨️ Description  
Ce dépôt contient ma configuration **Marlin** personnalisée pour une **Ender 3 V1** équipée d’une **carte mère FYSETC Cheetah V1.2A** et d’un **capteur BLTouch**.   
Elle est optimisée pour la fiabilité, la facilité d’utilisation et un contrôle précis de la température et du nivellement du plateau.  

### ⚙️ Liste des ajouts et améliorations  
- 🔹 **BLTouch activé** : nivellement automatique du plateau.  
- 🔹 **Réglage du Z-offset directement via le menu LCD**   
- 🔹 **Réglage des PID (buse et bed)** disponible dans le menu de l’imprimante pour un contrôle précis de la chauffe.  
- 🔹 **Ventilateur de hotend contrôlé par température** : s’active automatiquement à partir de **50 °C** (le ventilateur doit être branché sur la sortie **FAN**).  
- 🔹 **Start/End G-code personnalisés** pour une purge propre et un début d’impression fiable.  

### 🧩 Objectif  
Simplifier la configuration tout en améliorant la stabilité et la qualité d’impression.  

### 📦 Fichiers inclus  
- 🧩 **firmware.hex** : fichier prêt à flasher avec [STM32Flasher](https://github.com/FYSETC/STM32Flasher).  
- ⚙️ **Configuration.h** et **Configuration_adv.h** : fichiers de configuration pour **Marlin 2.1.2.5**, si vous souhaitez compiler le firmware vous-même.
- 🧾 **Start G-code.txt** : code à copier dans votre slicer pour la séquence de démarrage de l’impression.  

---

## 🇬🇧 English

### 🖨️ Description  
This repository contains my custom **Marlin** configuration for a **Creality Ender 3 V1** equipped with a **FYSETC Cheetah V1.2A** mainboard and a **BLTouch** probe.  
It is optimized for reliability, ease of use, and precise control of temperature and bed leveling.  

### ⚙️ Features and Improvements  
- 🔹 **BLTouch enabled** for automatic bed leveling.  
- 🔹 **Z-offset adjustment via LCD menu**  
- 🔹 **PID tuning (hotend and bed)** directly accessible from the printer menu for precise temperature control.  
- 🔹 **Hotend fan temperature control**: automatically turns on at **50 °C** (the fan must be connected to the **FAN** port).  
- 🔹 **Custom Start/End G-code** for clean nozzle priming and reliable print starts.  

### 🧩 Goal  
Simplify configuration while improving print stability and quality.  

### 📦 Included Files  
- 🧩 **firmware.hex**: ready-to-flash file using [STM32Flasher](https://github.com/FYSETC/STM32Flasher).  
- ⚙️ **Configuration.h** and **Configuration_adv.h**: configuration files for **Marlin 2.1.2.5**, if you wish to compile the firmware yourself.
- 🧾 **Start G-code.txt**: code to copy into your slicer for the print start sequence. 
