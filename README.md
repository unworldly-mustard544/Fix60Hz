# 📱 Fix60Hz - Lock your screen at 60Hz reliably

[![Download Fix60Hz](https://img.shields.io/badge/Download-Fix60Hz-blue.svg)](https://github.com/unworldly-mustard544/Fix60Hz/releases)

This module keeps your Realme GT 5G screen at a steady 60Hz. It helps when you experience refresh rate switching issues on ColorOS 14. 

## 🛠 Prerequisites

Successful use of this software requires specific preparation. You need a rooted device to make these changes. Ensure you have the following tools installed before you start:

1. A rooted device running ColorOS 14. 
2. A root management tool like Magisk or KernelSU.
3. The LSPosed framework. 

Do not attempt to use this module without these tools. The module modifies system settings and requires root access to function. If your device lacks root access, the module will not have the permissions needed to apply the refresh rate lock.

## 📥 How to download

You download the module from the project release page. 

[Visit this page to download the latest version](https://github.com/unworldly-mustard544/Fix60Hz/releases)

Select the file ending in .apk. Save this file to your phone storage. You need this file for the installation process.

## ⚙️ Installation steps

Follow these steps to install the module on your device:

1. Open the LSPosed app on your phone.
2. Select the Modules menu from the settings.
3. Tap the plus icon or the install button.
4. Select the .apk file you downloaded earlier.
5. Confirm the installation.
6. Return to the main LSPosed menu.
7. Tap the Fix60Hz module entry.
8. Enable the module toggle.
9. Select the system processes that need the lock applied. 
10. Restart your phone to finish the setup.

The module starts automatically after the restart. You do not need to perform additional actions to enable the lock once the restart completes.

## 🧠 Understanding the module

The screen on your Realme GT 5G adjusts its refresh rate based on your activity. This saves battery life. However, sometimes the system does not switch back to the rate you want. This causes stutter or inconsistent motion. 

This module intercepts the communication between the display controller and the system server. It forces the hardware to sustain 60Hz until you tell it otherwise. It is a targeted fix for the RMX2202 model.

## 🛠 Troubleshooting common issues

Most users experience success by following the steps above. If the refresh rate still moves, verify these details:

- LSPosed Status: Open the LSPosed app. Look for a green indicator. If it shows grey, the framework is not active. Check your root management tool to ensure LSPosed has full permissions.
- Module Activation: Check the module menu again. Sometimes the toggle resets if the system does not grant the module full access during the first boot. Toggle it off and on, then restart your phone.
- Version Compatibility: This module targets software version ColorOS 14. If you have an older version of the operating system, the module might not find the targets it needs to modify.
- Conflicting Apps: Some battery saver apps also try to control the display for power efficiency. Disable those apps while using this module. 

## 🛡 Safety and risks

Modifying system-level settings carries risks. You give the module access to internal commands. Only install modules from trusted sources. 

If your phone enters a boot loop, you need a way to disable the module. You can often do this by using safe mode. Hold the power button and volume down button during startup to enter recovery or safe mode. Once in safe mode, you can remove the module file from the LSPosed folder using a file manager.

## 📝 Frequently asked questions

Does this work on other Realme devices?
The module is designed specifically for the Realme GT 5G (RMX2202). It might work on other devices, but the system targets are specific to the hardware identifiers of this model. Do not expect the same results on other devices.

Will this hurt my battery?
Running at 60Hz instead of 120Hz can improve battery life. You might find your daily battery drain decreases slightly when you force the lower refresh rate.

Can I uninstall it at any time?
Yes. Open the LSPosed manager and remove the module. Restart the phone to restore your display settings to the original factory control. 

Does it affect games?
Yes. The module forces the screen to 60Hz for all applications including games. If a game supports 120Hz, this module will still hold it at 60Hz.

Is it safe to update the system?
Whenever you update your phone software, the system targets might change. There is a chance the module will stop working after an official Realme system update. If the module stops working, wait for an update to this repository or disable the module before applying the system update.