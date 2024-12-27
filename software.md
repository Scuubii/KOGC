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

For more advanced stuff I can link some other guides that go over specifics in crazy depth:


1. An AMAZING guide is [Amit's PC Tuning Guide](https://github.com/valleyofdoom/PC-Tuning) by Amit, also check his github ValleyOfDoom, great stuff.
2. [BoringBoredom](https://github.com/BoringBoredom/PC-Optimization-Hub/tree/main)
3. [Calypto's Latency Guide](https://docs.google.com/document/d/1c2-lUJq74wuYK1WrA_bIvgb89dUN0sj8-hO3vqmrau4/edit?tab=t.0)
4. Many other guides are available on the internet.

This will also not be the last of My guides or even this specifc guide, I'll add more to this as I feel like . . . This was all written in a single sitting so you can imagine I'm quite tired.


# My way of advanced tinkering

You don't have to do anything that I do, this is only my way of doing stuff, and my opinions on certain parts of Windows.


# Windows Defender

One of my least favorite parts of Windows, personally I uninstall it as soon as I boot in, if you know what you're downloading you're never going to need Defender, also it's one of the biggest game changers when it comes to latency.

# Firewall

This doesn't matter as much but I still prefer disabling it, most modern routers have a Firewall of their own, not to mention your ISP does as well, do you really need to be behind 3 firewalls? not really... All that being said Windows Firewall can be useful if you want to block specific apps from accessing the internet.

# Tweaks... (I hate this word)

I'll take a moment to talk about what people tend to call "tweaks" and "tweakers", if you currently search up this buzz-word in combination with the name of a popular game (Fortnite, Valorant) you'll find hundreds of videos all following the same template, they'll tell you to join their Discord server and in there they link a poorly written batch file that has been bloated with registry keys that don't do ANYTHING, please, please, DON'T RUN ANYTHING LIKE THAT, it's not inherntly dangerous (even though it could be) but it's worse than not doing it, everything can be done by your own 2 hands, in your own Windows install, YOU decide what to do, not a file... (I'm not discouraging the use of small, useful scripst for automation, quite the opposite, I love powershell scripts and batch scripts that have a single use, making your life easier, not total utilities that claim to "tweak" your computer)

I'll also touch on "tweakers" as they like to call themselves, I do not associate with these people, there are absolute gems in the community of said "tweakers" that actually put in work and know what they're talking about, but 99% of them don't have any Computer Science knowledge at all, it's all a huge money grab (that works..). Don't buy any $30 batch files from anyone, it's not worth it, it's not going to do anything.


# Power savings 

I'm guessing you know by now that these have no place in a real-time system, power savings are absolutely everywhere, from inside the hardware itself to your BIOS and of course your windows install, I won't go over each individual setting, you're free to look for yourself, anything "dynamic" or "efficient" should be turned off, I'll link a power plan and such in the Releases of this GitHub.


