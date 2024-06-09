# intel_hackintosh
This is a repo for the config.plist for an Intel Hacktintosh running on macOS Big Sur 11.4. Use as you will for your purposes or as a good baseline. Personal info such as ROM/Serial Number among others have been stripped out. Generate using SMBIOS tool from CorpNewt


**Dell XPS 8940 Special Edition Prebuilt**
|Part |Specs|
|-----------------|---------------------|
|CPU 	|i5-10400|
|GPU 	|UHD 630 (RTX 3060Ti disabled with bootarg)|
|OpenCore |	0.6.9 (Don't feel like updating until i have to or unless some big improvement comes about)|
|Wifi-Card |	Dell DW1820A (swapped out Intel AX wifi chip for airdrop and had to do some spoofing to get it working as technically support got dropped with Big Sur)|
|Audio |	ALC898 (had to apply a IRQ Conflict fix to get this working and running through all the layout-ids of which a couple worked)|
|Ethernet |	Realtek Gigabit Controller|
