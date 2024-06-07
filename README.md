# Home Lab

My Home lab setup and configuration begins with me purchasing a Geekom Mini11 Air Mini PC to use as a home server.  
![HLfront](https://github.com/emt-py/HomeLab/assets/72234380/1d5cec4f-dfec-4865-9c9d-a80000c75049)

This unit runs off an Intel Celeron 4 core processor N5095, which should be powerful enough as a beginner home lab. Initially, the PC was configured with the Windos 11 OS on a 256GB M.2  SSD and 8GB of DDR4 RAM, but that was quickly replaced with a new 1TB SSD. 
Since the Geekom Mini11 supports dual-channel memory, I upgraded the RAM with two 16GB modules.
![HLinside](https://github.com/emt-py/HomeLab/assets/72234380/8bb4bef8-b257-4013-ad3a-f08083befa01)

With hardware upgrades out of the way, I flashed the Ubuntu Server 24.04 ISO to the new SSD.
![lscpu](https://github.com/emt-py/HomeLab/assets/72234380/db3ad653-8005-40ab-b4b1-853b63cf5c12)
![lshw](https://github.com/emt-py/HomeLab/assets/72234380/8edc1ff5-e8b1-45da-a2bd-e95af2a711c2)
![hostnamectl](https://github.com/emt-py/HomeLab/assets/72234380/590c1285-c2ba-4b74-a0e8-104322bec159)

Next I installed CasaOS by IceWhaleTech using curl command  
[curl -fsSL https://get.casaos.io | sudo bash]

One CasaOS has been installed I was given a local URL that I can open in an internet browser to access the Ubuntu server from my desktop PC
![casahome](https://github.com/emt-py/HomeLab/assets/72234380/35bffb48-6e50-49ee-92c6-7225dc6075e9)

CasaOS acts as a simple personal cloud experience around the Docker ecosystem and the integrated store allows me quick access to multiple apps and programs I can use for future projects.
![casastore](https://github.com/emt-py/HomeLab/assets/72234380/add005c0-9f02-4e3e-9a68-ad141a68bbca)
