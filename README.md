# Rust Server Tutorial
Tutorials for admins/staff in arab rust.

##### Table of Contents  
[How to update server vanilla/modded](#headers)  
[How to wipe server vanilla/modded](#headers) 
<a name="headers"/>
## How to update server vanilla/modded
Updating server will not affect the server data unless it was patch from force wipe. I recommand checking/updating before every wipe, We will assume for now that force wipe just came out and we will update the server.
### Vanilla
Locate the `start.bat` located at `C:\Users\Administrator\Desktop\rust\server`. This will execute any updates *VANILLA* then start the server.
![startserver](https://user-images.githubusercontent.com/51522724/109436435-f6110580-7a38-11eb-8988-136a89c6d05c.JPG)

### Modded
First make sure you update vanilla side then update moddded. in moddded you need to grab files from [umod](https://umod.org/games/rust) website and click on download. Drag files from the .zip file to `C:\Users\Administrator\Desktop\rust\server`. You will be asked to overwriting files press OK. Once its done start the server and to verify type in console(once it starts) `plugins` and it should show all plugins installed.
## How to wipe server vanilla/modded

### Map, player, and blueprints wipe
shutdown the server and go to `C:\Users\Administrator\Desktop\rust\server\server\server1`. Delete the highlighted data files, if you wanna do bp wipe only then delete everying except `player.blueprints`
![delete files](https://user-images.githubusercontent.com/51522724/109436840-0629e480-7a3b-11eb-8604-9d666b2bbc87.JPG)


### Modded wipe
Deleting modded data such as home location, player currency, or backpack inventory is important for a wipe. All modded data can be found at `C:\Users\Administrator\Desktop\rust\server\oxide\data` and not all data should be deleted some are needed. So lets say we wanna delete home teleportation so we would delete `NTeleportationHome.json`.
![teleporthome](https://user-images.githubusercontent.com/51522724/109436946-bef02380-7a3b-11eb-8ad4-51a8ec0177e8.JPG)

