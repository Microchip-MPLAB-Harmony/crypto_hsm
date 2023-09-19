![Microchip logo](https://raw.githubusercontent.com/wiki/Microchip-MPLAB-Harmony/Microchip-MPLAB-Harmony.github.io/images/microchip_logo.png)
![Harmony logo small](https://raw.githubusercontent.com/wiki/Microchip-MPLAB-Harmony/Microchip-MPLAB-Harmony.github.io/images/microchip_mplab_harmony_logo_small.png)

# Microchip MPLAB® Harmony 3 Release Notes
## Crypto HSM  Release v1.0.0
### New Features
- **New features and enhancements**
	- Initial Release of the Microchip HSM Firmware Source
	- Cryptographic Algorithms
		- AES modes:
			- ECB
			- CBC
			- CTR
			- GCM
		- Hashing:
			- MD5
			- SHA-1
			- SHA-2-224
			- SHA-2-256
			- SHA-2-384
			- SHA-2-512
		- HMAC Support for SHA-2 algorithms
		- ECC Curve Support
			- p192
			- p256
			- p384
			- p521
		- EcDSA - For Supported Curves
		- EcDH - For Supported Curves
	- Key Creation Support
		- TRNG to create valid keys for supported curves
		- TRNG to create AES keys
	- Internal (key) Storage:
		- RAW keys (used for HMAC)
		- AES Keys (for supported modes)
		- ECC Keys (for supported curves)
	- Secure Boot Support
		- Meta Data version 1 support
		- ECC signed images / Meta Data
		- Hashed image support
	- Sleep Mode Support (Busy Bit is clearned while not processing, M0 core is in WFI state)
	- Driver Support:
		- Mailbox
		- Auxillery Interface
		- External DMA
		- Flash
		- CSM
		- Crypto
		

### Known Issues
- None

### Development Tools
- [MPLAB® X IDE v6.15 ](https://www.microchip.com/mplab/mplab-x-ide)
- [MPLAB® XC32 C/C++ Compiler v4.30](https://www.microchip.com/mplab/compilers)
- MPLAB® X IDE plug-ins:
    - MPLAB® Code Configurator v5.3
	