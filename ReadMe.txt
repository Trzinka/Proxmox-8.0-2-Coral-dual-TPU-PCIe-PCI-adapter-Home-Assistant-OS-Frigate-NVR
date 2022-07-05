Before I start explaining the installation process, let me first say 
- that I absolutely need a Windows environment because I know the system better than a 
- Linux environment, which is a COMPLETE UNKNOWN TO ME!
----------------------------------------------------------------------------------------
What ways have I tried to get the PCI adapter pass and I FAILED !

#1 Oracle VirtualBox + Extension Pack + Home Assistant OS on Windows 10 pro
#2 VMware Workstation Pro + Tools + Home Assistant OS on Windows 10 pro
#3 Windows Server 2019 + Home Assistant OS on Server VM
#4 Oracle VirtualBox + Extension Pack + Home Assistant OS on Windows Server 2019
#5 VMware Workstation Pro + Tools + Home Assistant OS on Windows Server 2019

ALL FAILED!!!
----------------------------------------------------------------------------------------

After that I just listened to the advice from discord and installed Proxmox with two VMs.

#1 VM is Windows as a file sharing system and some programs that I am more familiar with
   in the Windows environment.
#2 VM is Home Assistant OS + Add ons Samba share (of course other add-ons are installed)!

*****************************************************************************************

1.) Installing Proxmox is not an atomic science. To get started, watch the video:
    https://www.youtube.com/watch?v=u8E3-Zy9NvI&ab_channel=LearnLinuxTV
