# Cartridge Reader for Arduino Mega2560

![image](https://dl.dropboxusercontent.com/s/cqjxdd51n4iiuu2/3d_model.png?dl=1)   

#### Features:  
- Reads SNES roms and reads/writes save games from and to the SNES cartridge  
  Supported cartridge types so far: LoRom, HiRom, ExHiRom, SuperFX, SuperFX2, SDD1, SA1(needs Adafruit Clock Generator)  
- Reads and writes SFC Nintendo Power Flash Cartridges (also known as SF Memory, needs Adafruit Clock Generator for best result)  
- Reads N64 roms and reads/writes save games(4K/16K Eeprom + Sram + all 3 types of Flashram)   
- Reads and writes N64 controller paks and also can test a N64 controller's buttons and thumbstick   
- Reflashes N64 Repros (those with the Max II CPLD and Spansion S29GL256N or Intel 4400L0ZDQ0 flashroms)    
- Reads Game Boy (Color) roms and reads/writes save games   
- Programs custom made Game Boy Color flashcarts   
- Reads Game Boy Advance roms and reads/writes save games(4K Eeprom, 64K Eeprom, Sram/Fram, SST39VF512 512K flash + MX29L010 1M flash)   
- Reads Sega Mega Drive roms and reads/writes save games(Sram/Fram)    
- Programs Flashroms like 29F016, 29F032, 29F033, 29F1610 and 29L3211    

#### Be sure to check the guides in the [Wiki](https://github.com/sanni/cartreader/wiki) too.

[![](https://dl.dropboxusercontent.com/s/950svg0i21syq3j/youtube_preview.jpg?dl=1)](https://www.youtube.com/watch?v=AD_o7J85bCg)   

#### Thanks to:  
   MichlK - ROM-Reader for Super Nintendo   
   Jeff Saltzman - 4-Way Button   
   Wayne and Layne - Video-Game-Shield menu   
   skaman - SNES enhancements and SA1 sram support   
   nocash - Nintendo Power and GBA Eeprom commands and lots of other info   
   crazynation - N64 bus timing   
   hkz/themanbehindthecurtain - N64 flashram commands   
   jago85 - help with N64 stuff   
   Andrew Brown/Peter Den Hartog - N64 controller protocol   
   bryc - mempak   
   Shaun Taylor - N64 controller CRC functions   
   Angus Gratton - CRC32   
   Tamanegi_taro - SA1 fix   
   Snes9x - SuperFX sram fix   
   zzattack - multigame pcb fix  
   Pickle - SDD1 fix   
   insidegadgets - GBCartRead   
   RobinTheHood - GameboyAdvanceRomDumper   
   YamaArashi - GBA flashrom bank switch command    
   
![image](https://dl.dropboxusercontent.com/s/pw0zf6747n9laat/3d_model_2.png?dl=1)   

#### Please join the discussion at: http://forum.arduino.cc/index.php?topic=158974.0   
