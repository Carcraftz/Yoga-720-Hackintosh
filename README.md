# Yoga-720-Hackintosh
13" Yoga 720 Hackintosh

I was looking for a laptop, and I found this beauty on ebay for $500. Decided to hackintosh it, and it's currently running Mojave. 

System Specs:
i7 7500U
16GB Ram
1TB NVME SSD
4K Display

Pull requests are encouraged!
![Proof](https://cdn.discordapp.com/attachments/694281749198274590/694567212698173471/unknown.png)
Working:
Wifi/Bluetooth (after replacing stock wifi card with a DW1560)
Airdrop
Continuity
iMessage
App Store
Keyboard, touch screen, trackpad and pen
Undervolt w/ throttlestop (-100 CPU, -100 GPU, -100 CPU Cache)
USB Port and USBC Port
Webcam
Sleep

Not Working:
Thunderbolt Port
Fingerprint reader
Native Wifi/Bluetooth with the stock intel chip. You need to replace it with a DW1560. Follow this guide: https://www.ifixit.com/Guide/Lenovo+Yoga+720+Wireless+Adapter+Replacement/102473


Note: Replace Serial Number and Board Serial Number under SMBIOS, and MLB under Rtvariables with a new generated serial. 
![example](https://cdn.discordapp.com/attachments/694281749198274590/694564651144314960/unknown.png)
