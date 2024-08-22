
## KickStarterFiles

## Project Description

## How to Use

- Clone the repository
- Follow the instructions in the DockerFile to build and run the application. 

Installations:
- [ ] VS code
- [ ] Python 
- [ ] Git bash
- [ ] Docker
- [ ] VMware Fusion (in the case of MacOS)
- [ ] Optional installation as needed:
  - [ ]  GPU information	
  - [ ] Get the specs of the VRAM, RAM, and GPU Config into a Txt file.


Information:
- It is now creating a Win11 and Rocky9 VM in VMWare to test their connection. 
- Create a Bridge Network bw after this make a KS file that acts as HTTPS installation part.

References:
- [Link for skipping MS account login while startup](https://www.windowscentral.com/how-set-windows-11-without-microsoft-account)
- [How-to-restart-Network-Interface-or-Network-Adapter-on-Linux-and-Windows-Cloud-Servers](https://www.layerstack.com/resources/tutorials/How-to-restart-Network-Interface-or-Network-Adapter-on-Linux-and-Windows-Cloud-Servers )
- On a Windows 11 laptop, I could ping from the Windows host to the SUSE Linux VM client, but not the reverse. The following fixed it for me. In Windows: Start | Click “Type here to search” | Select “Windows Defender Firewall” | In left panel select “Allow an app or feature through Windows Defender Firewall” | In “Allowed apps and features” scroll down to “Virtual Machine Monitoring.” Select “Change Settings” and enable it for Public and Private (at least for Public).[LINK](https://superuser.com/questions/627208/unable-to-ping-a-windows-machine-from-linux )
