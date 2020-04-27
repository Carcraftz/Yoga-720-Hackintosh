# Yoga-720-Hackintosh
13" Yoga 720 Hackintosh

I was looking for a laptop, and I found this beauty on ebay for $500. Decided to hackintosh it, and it's currently running Mojave. 

System Specs:
i7 7500U
16GB Ram
1TB NVME SSD
4K Display

Pull requests are encouraged!

![proofimage](https://cdn.discordapp.com/attachments/694281749198274590/694568013352927312/unknown.png)
Working:

Wifi/Bluetooth (after replacing stock wifi card with a DW1560)

Airdrop

Continuity

iMessage

App Store

Keyboard, touch screen, trackpad and pen

Undervolt w/ throttlestop (-100 CPU, -100 GPU, -100 CPU Cache)-> READ UPDATE

USB Port and USBC Port

Webcam

Sleep

Not Working:

Thunderbolt Port

Fingerprint reader

Native Wifi/Bluetooth with the stock intel chip. You need to replace it with a DW1560. Follow this guide: 
https://www.ifixit.com/Guide/Lenovo+Yoga+720+Wireless+Adapter+Replacement/102473


Note: Replace Serial Number and Board Serial Number under SMBIOS, and MLB under Rtvariables with a new generated serial. 
![example](https://cdn.discordapp.com/attachments/694281749198274590/694564651144314960/unknown.png)


Update: I was previously on a -100 -100 -100 CPU Undervolt w/ throttlestop. However, I was having some issues with final cut export and tensorflow. I narrowed the issue down to the Undervolt. I'm currently on a -50 -50 -50 and my system is currently stable when doing these tasks. I may have to do a little bit of testing to determine a stable undervolt for my system.

ADDITIONALLY: When I update this guide for the next macOS (I don't think Catalina is stable enough in general for me to update), I will likely move over from Clover to Opencore, now that laptops seem to have more support. This guide is currently for Mojave.
