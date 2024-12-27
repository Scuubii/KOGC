# SOFTWARE / POST-SETUP

You're finall here...


# This will run through software and operating systems



The first part of optimizng an operating system is... choosing it, yeah even in 2024, you can use other operating systems.

Do I really think any of you are going to use Linux. Not really, but hey, I love it so I'll go over it VERY briefly.



Do you game on your system? 

Yes > use Windows
No I like to do actual work > Use Linux (Arch / a district of Arch)


Moving on swiftly from that rant, now that you chose Windows (wow...) you have to decide which windows version.

We have a few choices and I'll go through them:

1. Windows 10
 - This as basic as it goes, can't really go wrong with it, classic windows, comes pretty bloated.

2. Windows 10 LTSC
 - Better than Windows 10 while still keeping functionality and security updates, I can recommend this.

2. Windows 11 (23H2)
 - Basically the same thing as Windows 10 but with a newer scheduler, stock is very bloated but can run anything without compatibility problems.

3. Windows 11 LTSC
 - Not a bad choice if you need the newer scheduler but don't want the bloat that comes in with stock Windows 11

4. Windows Server 2022
 - You probably haven't heard of this, and from the name you don't really know how this applies to you, well, this isn't JUST for servers, the intended use case.. sure
but I've used this for gaming and it's great if you can get over the compatibility uses, Server 2022 doesn't support mosT NICs by default and might need some light driver modding to install
some drivers, this all being said it comes with almost 0 bloatware out of the box and is more hassle free to install once you know what you're doing. Can be heavily customized (Note: It can't run Valornat, FACEIT, etc)

5. Windows Server 2025
 - This is newer and more untable then Server 2022, I can't really recommend this yet as I haven't tested it extensively, if you want a Server install stick to Server 2022.

6. Winodws 11 24H2
 - This is the newest version of Windows and still has some bugs to iron out, I'd suggest installing Windows 11 23H2 instead of this.

7. Custom ISOs
 - Stay away from these, there are some gems in the community but most of these are absolutely NOT good, not to mention the inherti security risk of installing an ISO that someone else made intead of Microsoft.
Custom ISOs do nothing that you can't do youself on your own Windows install.


Once you chose your favorite ISO and booted into it (I won't go into how to install Windows, use Google), the only thing that matters in the Windows install page is to set your Region to English (world) intead of whatever it is.
After you've done this you can press intall and let Windows do it's thing. Once it restarts a few times you should be in the post-install screen, don't set a password, turn off any permissions if it prompts you (Win 11), DON'T LOG IN TO A MICROSOFT ACCOUNT.
Once again let it do it's thing and you should be on the Desktop, congratulations! You now have a fully functional Windows install, now time to make it less functional...


First things first sort everything out, activate windows (whatever method you choose), set it to dark mode, now you should be able to actuall see stuff

I'll take the software stuff from most important to least, don't forget there's always more to do what I won't go over in a guide like this.

1. UNINSTALL Windows Defender (probably the most useful thing you can do), use a tool to do this, I won't link any due to obvious reasons, this shouldn't be done by beginners.
2. Switch your power plan to Ultimate Performance (powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61)
3. Go through the Windows settings and disable privacy stuff, storage sense, HAGS, game mode, power saving, etc.
4. Use an uninstaller like [Appxpackagemanger](https://github.com/valleyofdoom/AppxPackagesManager) SHOUTOUT TO AMIT / VALLEY OF DOOM <3
5. Disable Mouse accel, set all your mouse / keyboard settings in Windows to what you want them
6. Disable windows updates using regedit (stop the service)
7. Optionally you can also stop service "Sysmain"
8. In device manager you can disable all unused devices / ports (please don't disable something if you don't know what it does)

At this point you have a perfectly working Windows install that's decent, if you want to stop here you can, go ahead install your games and enjoy.... or keep going I guess...

More advanced stuff, this won't be a list and more like a ramble:


An AMAZING guide is [Amit's PC Tuning Guide](https://github.com/valleyofdoom/PC-Tuning)

Disable all power savings in device manager or use this command in Poweshell

'''
Get-WmiObject MSPower_DeviceEnable -Namespace root\wmi | ForEach-Object { $_.enable = $false; $_.psbase.put(); }
'''
