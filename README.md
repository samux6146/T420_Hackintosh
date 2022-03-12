The EFI folder of my project witch consists of installing mac os 10.13 high sierra on my Lenovo thinkpad T420. 

I used clover and not opencore for compatibility reasons.

For the install you will nead a usb flash drive with al least 8GB, a copy of the high sierra installer or the high sierra recovery image.

1) Make a bootable mac os usb. You can follow this guide: https://dortania.github.io/OpenCore-Install-Guide/installer-guide/ witch will tell you how to make an installer on windows, mac and linux. 

2) Add the EFI folder. In the guide when they tell you to add the default EFI folder for opencore, you simply ignor it and add my EFI folder.

3) Boot and install the os.

4) Configure the os.

5) Install The EFI on the hard derive. Download the clover Configurator app or the EFI mounter app and mount your efi folder. Delate the original EFI folder and place mine. Close the EFI partition and you can now boot.

6) Last Step: WI-Fi. Download the HeliPort app place it in the application folder and open it. Then go to hold oprion key wen you open helyport and enable "Launch At Login".

7) You are Done Enjoy your Thinkpadintosh!


![About_this_mac](https://user-images.githubusercontent.com/41386727/112048663-f0e23a80-8b4e-11eb-81ec-f0fbac13e26c.png)
