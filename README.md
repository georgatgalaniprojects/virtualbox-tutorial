# Virtualbox Tutorial

A Tutorial On How To Install Windows In Virtualbox On Mac OS X

Requirements:

* Virtualbox

  Either the newest Version available from [Virtualbox](https://www.virtualbox.org/wiki/Downloads)
  or
  the newest version as of this writing [VirtualBox-7.0.12 (Intel)](https://download.virtualbox.org/virtualbox/7.0.12/VirtualBox-7.0.12-159484-OSX.dmg)

* Windows license, either as an .iso file or on a phyisical media like an usb stick.

    You can download a Windows 10 iso here 
    [Windows 10](https://www.microsoft.com/de-de/software-download/windows10ISO)
    
    or a Windows 11 iso here 
    [Windows 11](https://www.microsoft.com/de-de/software-download/windows11)


Step 1. 

Run the Virtualbox installer.
After the installation you will need to restart your Mac. 

Step 2.

Run Virtualbox. Choose File -> New.

![Bildschirmfoto 2023-10-26 um 15 03 15](https://github.com/georgatgalaniprojects/virtualbox-tutorial/assets/48205769/77ffba99-d2d4-4670-bc34-84e4856d9a08)

Step 3. 

Give your new Virtual Machine a name, choose your iso, type Windows and the Windows version depending on what Version of Windows your iso is.

![Bildschirmfoto 2023-10-26 um 15 03 50](https://github.com/georgatgalaniprojects/virtualbox-tutorial/assets/48205769/3f0faffa-e22d-4c7b-9902-739e3855775b)

Step 4. 

Next you have to reserve a certain amount of RAM to the VM. For Windows 10 or higher I would recommend at least 4Gb or better 8Gb as a minimum. 
You can also decide on the number of cores you want to make available to the VM. 
The EFI Option you can leave checked. 

Stepe 5.

Next you can choose the amount of harddisk to be available to the VM. I recommend at least 20gb. More is better, because it is difficult to adjust the disk space later.

Step 6. 

Now you should have a good starting point for tweaking the VM. One last important configuration is changing the networking from NAT to briged. 
Select the Vm. Go to Change -> Networking  and select briged from the network adapater settings. 

Step 7.

Start the VM. The Windows Installation should start automatically. After you have finished the Windows installation, one last recommended Step is to install the **gust additions** from Devices -> Insert Guest Additions. This will give the VM much better performance and a lot of extra features. 

![Bildschirmfoto 2023-10-26 um 15 27 28](https://github.com/georgatgalaniprojects/virtualbox-tutorial/assets/48205769/95c657ec-c669-4f29-9834-51f5bef90a51)


