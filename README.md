## This project is discontinued.
My old Dell Inspiron 17 7778 has broken down over the years trying to get it working on macOS fully. Although there are still some problems with this config, like no sound working at all -- It's still a good config. But unfortanly, I can't use this laptop as my main anymore due to how many issues I got with this laptop.

If you'd like to fork this repo and work on it yourself, please do so. I'll even link the best one in the desc of this repo.

# Dell Inspiron 17 7778 Hackintosh
The EFI I use for my Dell Inspiron 17 7778 Series Hackintosh.

[You can easily download the latest version of this EFI folder by looking in the releases section.](https://github.com/ktg5/Inspiron-7778-Hackintosh-OC/releases)

## Note.
My "custom" EFI is only built for systems running an Dell Inspiron 17 7778 laptop with a Intel i5-6200U, and Intel HD Graphics 520. The reason why I'm talking about this is because in the `config.plist`, some settings may not match your configzation.

Also you'll have to run [CorpNewt's GenSMBIOS application](https://github.com/corpnewt/GenSMBIOS) because all strings in `PlatformInfo/Generic` are all set to blank MAY cause issues when using services like iMessage and other iCloud services on your system.

Any other things you want to change is all up to you, just make sure you know what you're doing.

If you are switching EFIs; I recommend you reinstall macOS as there could be some issues when booting your original installation of macOS if you have one.

## What does and doesn't work.
### Working:
* Networking + WiFi (I don't remember anything I needed to do for this?...).
* AirDrop and other WiFi services on macOS.
* Trackpad.
* Battery information.
* SD Card slot - EPIC!
* iMessage and other iCloud services.
* Bluetooth.
* Sleep/Restart/Shutdown - works with OC!
* HDMI and HDMI sound.
### Not working:
* Built-in audio - None of the layouts on AppleALC for this laptop's audio device work on macOS 10.15+, but it does work on macOS 10.14-???
* Audio port? - Not too sure yet.
* FileVault - who even uses that.
* Touchscreen - The GTX card needs to be disabled so we can run macOS 10.15+.
