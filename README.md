<div align="center">
<p align="center">
  <img src="docs/alphamen.png" alt="Logo_Green_text" width="400px" height="300">
</p>
<p align="center">


<div align="center">
  
# Pegasus-Pro
  
### Pegasus-Pro with Metasploit Integration.

#All Below Content written By Kutty More Content details get By Web 

</div>

#### Complete Automation to get a Meterpreter session in One Click

This tool can automatically __Create__, __Install__, and __Run__ payload on the target device using __Metasploit-Framework__ and __ADB__ to completely hack the Android Device in one click if the device has open ADB port `TCP 5555`.

The goal of this project is to make penetration testing and vulnerability assessment on Android devices easy. Now you don't have to learn commands and arguments, PhoneSploit Pro does it for you. Using this tool, you can test the security of your Android devices easily.

> [!TIP]
> __Pegasus Pro__ can also be used as a complete ADB Toolkit to perform various operations on Android devices over Wi-Fi as well as USB. 

# Screenshots

![Screenshot Page 1](docs/Pegasus-Pro.png)

## Authentication Required ⚡🎯

### Auth Token Get by Admin Contact via 👇🏻

* Access Via Admin Approval So Contact To Insta & WhatsApp 🧑🏻‍💻⚡

[![Instagram DM](https://img.shields.io/badge/INSTAGRAM-DM-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/dark_cyber.in/)
[![WhatsApp Chat](https://img.shields.io/badge/WHATSAPP-MESSAGE-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/17012645961)


* Once Entered The Auth Token Then Access The Tool🔥🎯


![Screenshot Page 2](docs/Pegasus-Pro(1).png)

![Screenshot Page 3](docs/Pegasus-Pro(2).png)

![Screenshot Page 4](docs/Pegasus-Pro(3).png)

# Features 
## v1.0

* Connect device using ADB remotely.
* List connected devices.
* Disconnect all devices.
* Access connected device shell.
* Stop ADB Server.
* Take screenshot and pull it to computer automatically.
* Screen Record target device screen for a specified time and automatically pull it to computer.
* Download file/folder from target device.
* Send file/folder from computer to target device.
* Run an app.
* Install an APK file from computer to target device.
* Uninstall an app.
* List all installed apps in target device.
* Restart/Reboot the target device to `System`, `Recovery`, `Bootloader`, `Fastboot`.
* __Hack Device Completely__ : 
  - Automatically fetch your `IP Address` to set `LHOST`.
  - Automatically create a payload using `msfvenom`, install it, and run it on target device.
  - Then automatically launch and setup __Metasploit-Framework__ to get a `meterpreter` session.
  - Getting a `meterpreter` session means the device is completely hacked using Metasploit-Framework, and you can do anything with it.


## v1.1

* List all files and folders of the target devices.
* Copy all WhatsApp Data to computer.
* Copy all Screenshots to computer.
* Copy all Camera Photos to computer.
* Take screenshots and screen-record anonymously (Automatically delete file from target device).
* Open a link on target device.
* Display an image/photo on target device.
* Play an audio on target device.
* Play a video on target device.
* Get device information.
* Get battery information.
* Use Keycodes to control device remotely.


## v1.2

* Send SMS through target device.
* Unlock device (Automatic screen on, swipe up and password input).
* Lock device.
* Dump all SMS from device to computer.
* Dump all Contacts from device to computer.
* Dump all Call Logs from device to computer.
* Extract APK from an installed app.

## v1.3

* Mirror and Control the target device. 

## v1.4

* Power off the target device. 

## v1.5

* Scan local network for connected devices to get Target IP Address. 

## v1.6

* Record Microphone Audio
* Stream Microphone Audio
* Record Device Audio
* Stream Device Audio

## v.13

* All Above Verion Used In v.13 Version 

# Requirements  
* [`python3`](https://www.python.org/) : Python 3.10 or Newer
* [`pip`](https://pip.pypa.io/en/stable/installation/) : Package installer for Python
* [`adb`](https://developer.android.com/studio/command-line/adb) : Android Debug Bridge (ADB) from `Android SDK Platform Tools`
* [`metasploit-framework`](https://www.metasploit.com/) : Metasploit-Framework (`msfvenom` and `msfconsole`)
* [`scrcpy`](https://github.com/Genymobile/scrcpy) : Scrcpy
* [`nmap`](https://nmap.org/) : Nmap


# Run Pegasus Pro 

__Pegasus Pro__ does not need any installation and runs directly using `python3`

> [!IMPORTANT]
> **Pegasus Pro** requires Python version __1.13 or higher__. Please update Python before running the program.

#### On Linux / macOS :

Make sure all the [required](Contact By Admin & Get Link Or Using GitHub) software are installed.

Open terminal and paste the following commands : 
```
https://github.com/alphamen01-hack/Pegasus-Pro.git
```
```
cd Pegasus-Pro/
```
```
pip install -r requirements.txt
```
```
python3 Pegasus-Pro.v.13.py
```
#### On Windows :

Make sure all the [required](Contact By Admin & Get Link Or Using GitHub) software are installed.


Open terminal and paste the following commands : 
```
https://github.com/alphamen01-hack/Pegasus-Pro.git
```
```
cd Pegasus-Pro/
```
```
pip install -r requirements.txt
```
1. Download and extract latest `platform-tools` from [here](https://developer.android.com/studio/releases/platform-tools.html#downloads).

2. Copy all files from the extracted `platform-tools` or `adb` directory to __Pegasus-Pro__ directory and then run :

```
python Pegasus-Pro.v.13.py
```

# Tutorial


## Setting up Android Phone for the first time

* __Enabling the Developer Options__

1. Open `Settings`.
2. Go to `About Phone`.
3. Find `Build Number`.
4. Tap on `Build Number` 7 times.
5. Enter your pattern, PIN or password to enable the `Developer options` menu.
6. The `Developer options` menu will now appear in your Settings menu.

* __Enabling USB Debugging__

1. Open `Settings`.
2. Go to `System` > `Developer options`.
3. Scroll down and Enable `USB debugging`.

* __Connecting with Computer__

1. Connect your Android device and `adb` host computer to a common Wi-Fi network.
2. Connect the device to the host computer with a USB cable.
3. Open a terminal in the computer and enter the following command :
```
adb devices
```
4. A pop-up will appear in the Android phone when you connect your phone to a new PC for the first time : `Allow USB debugging?`.
5. Click on `Always allow from this computer` check-box and then click `Allow`.
6. Then in the terminal enter the following command :
```
adb tcpip 5555
```
7. Now you can connect the Android Phone with the computer over Wi-Fi using `adb`.
8. Disconnect the USB cable.
9. Go to `Settings` >  `About Phone` > `Status` > `IP address` and note the phone's `IP Address`.
10. Run __Pegasus-Pro__ and select `Connect a device` and enter the target's `IP Address` to connect over Wi-Fi.



## Connecting the Android phone for the next time

1. Connect your Android device and host computer to a common Wi-Fi network.
2. Run __Pegasus-Pro__ and select `Connect a device` and enter the target's `IP Address` to connect over Wi-Fi.


# This tool is tested on

-  ✅ Ubuntu
-  ✅ Linux Mint
-  ✅ Kali Linux
-  ✅ Fedora
-  ✅ Arch Linux
-  ✅ Parrot Security OS
-  ✅ Windows 11
-  ✅ Termux (Android)

> [!NOTE]
> All the new features are primarily tested on **Linux**, thus **Linux** is recommended for running Pegasus Pro.
Some features might not work properly on Windows.

# Installing ADB 

#### ADB on Linux :

Open terminal and paste the following commands :

* __Debian / Ubuntu__
```
sudo apt update
```
```
sudo apt install adb
```

* __Fedora__
```
sudo dnf install adb
```

* __Arch Linux / Manjaro__
```
sudo pacman -Sy android-tools
```

For other Linux Distributions : [Visit this Link](https://developer.android.com/studio/releases/platform-tools#downloads)

#### ADB on macOS :

Open terminal and paste the following command :

```
brew install android-platform-tools
```

or Visit this link : [Click Here](https://developer.android.com/studio/releases/platform-tools.html#downloads)

#### ADB on Windows :

Visit this link : [Click Here](https://developer.android.com/studio/releases/platform-tools.html#downloads)

#### ADB on Termux :
```
pkg update
```
```
pkg install android-tools
```


# Installing Metasploit-Framework 

#### On Linux / macOS :
```
curl https://raw.githubusercontent.com/rapid7/metasploit-omnibus/master/config/templates/metasploit-framework-wrappers/msfupdate.erb > msfinstall && \
  chmod 755 msfinstall && \
  ./msfinstall
 ```
 
or Follow this link : [Click Here](https://docs.metasploit.com/docs/using-metasploit/getting-started/nightly-installers.html#installing-metasploit-on-linux--macos)

or Visit this link : [Click Here](https://www.metasploit.com/download)

#### On Windows :

Visit this link : [Click Here](https://www.metasploit.com/download)

or Follow this link : [Click Here](https://docs.metasploit.com/docs/using-metasploit/getting-started/nightly-installers.html#windows-anti-virus-software-flags-the-contents-of-these-packages)

# Installing scrcpy

Visit the `scrcpy` GitHub page for latest installation instructions : [Click Here](https://github.com/Genymobile/scrcpy#get-the-app)

**On Windows** : Copy all the files from the extracted **scrcpy** folder to **Pegasus-Pro** folder.

> [!IMPORTANT]  
> If `scrcpy` is not available for your Linux distro like **Kali Linux**, then you can either manually install it : [Manual Guide](https://github.com/Genymobile/scrcpy/blob/master/doc/linux.md),
or build it with a few simple steps : [Build Guide](https://github.com/Genymobile/scrcpy/blob/master/doc/build.md#build-scrcpy)

# Installing Nmap

#### Nmap on Linux :

Open terminal and paste the following commands :

* __Debian / Ubuntu__
```
sudo apt update
```
```
sudo apt install nmap
```

* __Fedora__
```
sudo dnf install nmap
```

* __Arch Linux / Manjaro__
```
sudo pacman -Sy nmap
```

For other Linux Distributions : [Visit this Link](https://nmap.org/download.html)

#### Nmap on macOS :

Open terminal and paste the following command :

```
brew install nmap
```

or Visit this link : [Visit this Link](https://nmap.org/download.html)

#### Nmap on Windows :

Download and install the latest stable release : [Click Here](https://nmap.org/download.html#windows)

#### Nmap on Termux :
```
pkg update
```
```
pkg install nmap
```



# Disclaimer

* Pegasus-Pro is a controlled cybersecurity research framework.

## This software is intended ONLY for:

* Cybersecurity education
* Ethical hacking & red-team simulations
* Digital forensics training
* Authorized penetration testing

## 🚫 ZERO TOLERANCE FOR MISUSE

* ❌ Illegal hacking, spying, surveillance, stalking, data theft, or privacy invasion is STRICTLY FORBIDDEN.
* ❌ No authorization = No usage. No excuses.

## ⚖️ USER ASSUMES ALL RESPONSIBILITY

### The developer(s) of Pegasus-Pro:

* Do NOT encourage cybercrime
* Accept ZERO liability for misuse
* Are NOT responsible for damages, losses, or legal consequences

### 👉 YOU alone are accountable for your actions.

## 🔐 AUTHORIZATION IS MANDATORY

### Use Pegasus-Pro ONLY on:

* Systems you own
* Systems with explicit written permission
* Unauthorized use may result in serious legal consequences.

## 🧠 ETHICAL WARNING

### This tool exists to understand, defend, and secure systems — not to harm.

* Ethical hacking starts with permission. Always.

## ✅ ACCEPTANCE NOTICE

* By accessing, installing, or using Pegasus-Pro, you automatically agree to this disclaimer.
* If you do not agree — DO NOT USE THIS SOFTWARE.


# 🔗 Developer
---

<img src="images/avatar.png" width="90" align="left" />

<p align="left">
  <a href="https://kuttythedarkhacker.netlify.app/" target="_blank">
    <img src="https://img.shields.io/badge/Website-About-00e5ff?style=for-the-badge&logo=google-chrome&logoColor=black">
  </a>
  <br>
  <!-- Neon Green Website Button -->
  <a href="https://thedarkdevil.netlify.app/" target="_blank">
    <img src="https://img.shields.io/badge/Website-Visit-00ff6a?style=for-the-badge&logo=google-chrome&logoColor=black">
  </a>
</p>

<br clear="left"/>

---

## ❤️ Support 

Support by following my Instagram page:

<p align="left">
  <a href="https://www.instagram.com/dark_cyber.in?igsh=b2J0b3F4YnBkd2ph" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-Follow-ff2d55?style=for-the-badge&logo=instagram&logoColor=white">
  </a>
</p>

---

© 2025 kutty
