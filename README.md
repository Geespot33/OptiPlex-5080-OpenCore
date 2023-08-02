#Not working yet
# OptiPlex 5080

## Configuration

| Specifications      | Detail                       |
| ------------------- | ---------------------------- |
| CPU                 | Intel(R) Core(TM) i5-10500   |
| Integrated Graphics | Intel UHD Graphics 630       |
| Sound Card          | Realtek ALC3246              |
| Ethernet Controller | Intel i219-LM                |

## MacOS Versions Supported:

- macOS Ventura
- macOS Monterey
- macOS Big Sur
- macOS Catalina

#### Change by Geespot33 2023-07-22

- Disable IntelBlueToothFirmware, IntelBlueToothInjector, Airportitlwm, RealtekRTL8111Ethernet. Because not using yet
- Remove USBInjectall (Created SSDT-s) USBMap used to for mapping, one of the rear USB2.0 is disabled.


- Updated : 	Opencore	v0.9.3
		AppleALC	v1.7.8
		Lilu		v1.6.6
		VirtualSMC	v1.3.2
		Whatevergreen	v1.6.6
		


#### Change

- Fixed IntelMausi enabled set to `false` in config.plist which disabled the connection in some OptiPlex 5080 models.

## What is Working?

- [x] Native CPU Power Management
- [x] Sleep/Wake
- [x] Intel Graphics
- [x] Hardware Acceleration (1.6GB)
- [x] Audio
- [x] Type-C USB
- [x] Type-C: video and audio
- [x] DisplayPort: video and audio
- [x] USB 3.0
- [x] Brightness
- [x] Built-in mic
- [x] Line-in mic
- [x] Bluetooth Intel
- [x] Intel wireless
- [x] Bootcamp assistant
- [x] iMessage and Facetime (tested in ventura)

## Not working:

- Nothing

## BIOS settings

- [ ] Secure boot enabled
- [ ] Fast Boot
- System Configuration → SATA Operation: AHCI
- [x] VTx in System Options
- [x] Intel virtuallization options

## IMPORTANT

Personnaly I had the best results installing Catalina and then upgrading to Ventura (you can do it without any updates as the kexts and OC are up to date (10/2/2023)


