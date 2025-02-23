# Oma Linux

##Summary -Raportin kirjoittaminen
How should you write a raport
- Repetetive
- Punctual
- Easy to read
- Sources
- Bad mistakes

  ## a) Asenna linux
  before we make a new virtualbox lets download some stuff. 
  [downloads](https://cdimage.debian.org/debian-cd/current-live/amd64/iso-hybrid/). From here we can find the iso image we want to dowload. the correct one is debian version and amd64
  after its completed we can make a new virtualbox and remember to select "expert install" for more advanced settings
  In virtualbox Manager press new virtual box, then you should have this kind of page opened up
![Näyttökuva 2025-02-23 200157](https://github.com/user-attachments/assets/f103a584-2dce-4057-a0ec-d3ba5a88ed54)
- for name you can write for example"Linux(your name)
- for ISO image now select the existing iso image disk that we just downloaded
- type: Linux
- suntype: oracle Linux
- version 64-bit
- check skip imattemded install because it will give some problems
- memory: atleast 2000MB but 4000MB is better
- select "create virtual hard disk now"
- VDI (virtual disk image) atleast 20GB
- dynamically allocated if you need in the future more memory or if you use less it will adapt

  ## Setting up Linux
  select the created machine and press settings and go to storage
  ![Näyttökuva 2025-02-23 201342](https://github.com/user-attachments/assets/97e6cd2b-c4d9-454a-b981-087b266abd91)
Mine is already ready so yours should look a bit different. Where it says "empty" click "Controller IDE" then press the disk image and choose "choose a disk file and select the downloaded Linux-debian-iso

## Start
now we are ready to start... so click start
choose install linux and select the correct language and keybord, timezone etc...
then press "Erase disk and install Linux". The disk will be empty but just in case there is something that we dont want

after creating your user and password we are ready to dowload

## After dowload
it is recommended to use these commands first
- sudo apt update - updates the package infornation, retrieving the latest versions from the software repositories
- sudo apt upgrade -y - upgrades all installed packages to their latest availavble versions
