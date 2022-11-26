# PetHouse

<a target="_blank" href="https://github.com/Sh1n3zZ/PetHouse"><img src="https://img.shields.io/github/stars/Sh1n3zZ/PetHouse" /></a> 
<a target="_blank" href="https://github.com/Sh1n3zZ/PetHouse"><img src="https://img.shields.io/github/last-commit/Sh1n3zZ/PetHouse" /></a>
<a target="_blank" href="https://github.com/Sh1n3zZ/PetHouse"><img src="https://img.shields.io/github/v/release/Sh1n3zZ/PetHouse" />
[![GitHub Sponsors](https://img.shields.io/github/sponsors/Sh1n3zZ?label=GitHub%20Sponsors)](https://github.com/sponsors/Sh1n3zZ)

<div align="center" width="100%">
    <img src="./public/icon.png" width="128" alt="" />
</div>

This is a pet rescue project based on Mind+ is called PetHouse.

<img src="./public/DemoPic.jpg" width="700" alt="" />

## ⭐ Previews

### APP / WebSite
<p align="center">
<img src="./public/APP.png" height="350"/>
<img src="./public/WebSite.png" height="350"/>
</p>

### Appearance / WebCodes
<p align="center">
<img src="./public/Appearance.jpg" height="350"/>
<img src="./public/WebCodes.png" height="350"/>
</p>

## ⭐ Features

* It provides a temporary shelter for stray pets, so that pets can get their own food and water resources, reduce human and material resources, and prevent pets from getting sick and having bad stomachs due to eating bad things.
* Identify the type of pet through AI intelligent camera and feed it back to the master controller, who will give a judgment on opening the corresponding steering gear. When the pet does not arrive, turn on the RGB light band to simulate ultraviolet light to disinfect the pet water dispenser. When the pet arrives, turn off the ultraviolet light to prevent the pet from harming the pet.
* The adjustable power supply and solar panel can supply power simultaneously, which can ensure the normal operation of the pet house while ensuring clean energy and environmental protection.
* The water level information of the water storage tank is obtained through the water level sensor, and the water level information is pushed to the MQTT cloud platform through the MQTT sensor. Then, the information is obtained from the MQTT cloud platform using jQuery and other plug-ins, and then displayed on our mobile phones through the API interface callback using Web or APP information.
* The current ambient light brightness is detected through a photosensitive sensor. When the ambient light is too low, the light filling strip is opened to fill the light.
* The water level information of the feeding tank is obtained through the water level sensor. When the water level of the feeding tank is insufficient, water is pumped from the water storage tank to the feeding tank to ensure that the pet has enough water to drink at all times.
* Use Mind+ visual/graphical programming language to make secondary changes simpler and easier.

## 🔧 How to Use

### 💪🏻 Arduino Project Part

- [Download Release](https://github.com/Sh1n3zZ/PetHouse/releases) and Open it with Mind+.

### 🐳 Web Project Part

- [Download Release](https://github.com/Sh1n3zZ/PetHouse/releases) .
1.Open ../WebPages/index.html
2.Jump to line 24
3.Change "Your iot.dfrobot.com.cn API Port." to "Your API Port"（You can obtain this API interface from iot.ddrobot.com.cn）


## 🆙 How to Update

Please come here and install the latest release.

## 🆕 What's Next?

Better UI & Less BUG.

---I am a line---

That's all tkx for read~!
Have a good day!
If you love this project, please consider giving me a ⭐.
