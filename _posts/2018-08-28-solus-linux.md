---
layout: post
published: true
title: Review Solus Linux 3
subtitle: Best in class Desktop Linux OS I've ever used
date: '2018-08-28'
image: /img/solus-logo.jpg
tags:
  - review
---
No matter if you're a linux fanbox or a newbie: If you want to try out a new desktop oriented linux distribution that even beats the great [Elementary OS][Elementary], continue to read my review of [Solus Linux][Solus].

1. Table of contents will appear below
{:toc}

* Installing linux for fun

Installing a linux distribution is sort of a hobby for me. Recently I discovered a very nice project about a _desktop oriented_ linux distribution which is **not** based on Ubuntu / Debain / Slack: [Solus Project][Solus]. 

You can find a lot of detailled information about this distribution on [Distrowatch.com][Distrowatch]
[Distrowatch][Distrowatch] also maintains a list of popularity based on site-hits on distrowatch.
As of July 29th 2018 Solus ranked on **place 6 on their list** (considering data of the last 12 month).


* requirements to the OS

I always ask myself: Is it suitable for my parents?  
They are 70+ and total computer noobs. In other words - to OS need to be noob-proof :)


** rolling release - install once, upgrade forever

Every OS has its lifetime and after Windows XP reached the end of its live I moved my parents on Elementary OS as they didn't want to pay for a copy of Windows 7/8/10...

Now after approx 4 years it's time to install a new version of Elementary. Unfortunately it's not possible to do an in-line upgrade. Fresh install... time consuming and I need to ensure that every Icon / File / Link is available in the new OS.

{: .box-note}
In Solus you will not face this issue as it is a rolling-release Operating System.  
**Install once - upgrade forever**.

** Remote support
With Elementary I was always strugling with a proper 1-click remote-support solution. This is available in Solus through the 3rd-Party apps: **Anydesk**

** Zero maintenance
Wishfull thinking... Updates should be installable with least possible end-user involvement. Solus is doing a good job in notifying you about available updates.

* Installation
Solus comes in 3 editions. Budgie, Mate, Gnome - I have chosen the "Budgie" edition simply 'cause I have the impression this is where the developers put most effort in
Next you need to decide how to install.

** Install on VirtualBox
Start with this if you just want to do a **test-drive**.
It's usually the easiest way to test-drive [Solus]
As usual somebody already created a [Youtube video] (https://www.youtube.com/watch?v=8UgduvZQVpY) for this.

** Install on bare-metal
If you have spare notebook / PC, this is the recommended way. Solus in native speed without the overhead of virtualisation.

** Install on top of an existing OS (Dual/Multi boot)
There's an ilustrated howto avaliable on [Wikihow](https://www.wikihow.com/Install-Solus).
I don't like the idea of having 2 OS on the same machine.  
It's just a matter of time till one of the OS is killing the bootloader - Especially if you have Windows installed as primary/secondary OS.  
Better use a Virtualisation system like Virtualbox.

** The Installer
As all modern Linux Operating systems [Solus] comes with a graphical installer asking you some basic questions like language settings, timezone, etc... No issues at all

After a couple of minutes the system boots and you can login with the user-account you created during setup.

** SNAP support (similar to .EXE files on Windows)

** Docker to the help: Run services like Squid / Nextcloud / nginx / Apache...
If you're using an Ubuntu based system you have access to literaly millians of packages.
For the majority of end-users it's simply too much. Therefore I appreciate the approach of Solus to NOT integrate as many services as possible. There are other Linux distributions for that.

I was playing around with docker by accident and guess what - it's also available on Solus.
My way to install a "Service" on Solus is simply utilizing Docker / Docker-Compose. Works great and keeps your system clean and lean (no need to install a huge number of dependencies on your Desktop PC).


* First Impression
It is starting fast - really fast!

** Clean UI
** Appstore (Software Center)
** Searching
** Updates

* Installing additional software
Solus comes with a **vast number** of installed applications like 
- **Libre office** which will cover all your "office" needs like writing, presenting, calculating and drawing 
- **Archive Manager** to handle ZIP archives
- **Firefox or WEB** to browser the web
- **Thunderbird** for emails
- **Image Viewer** to view images (surprise surprise)
- **Rhythmbox** to listen to your music
- **Files** to manage your files (another surprising name)
- **Videos** to view ... guess what

I installed additional applications to make the system even more suitable for my needs.

- **Alber** to quickly search applications, basic math and quick translations without leaving the keyboard
- **Geary** a beautiful email client (I knew this one from Elementary OS)
- **Opera** to browse the web with style // adblocker // vpn
- **Dropbox** online storage with easy sharing options
- **Enpass** to manage the 174 passwords I have
- **Skype** to do cross-platform text / video chats
- **Steam** for basic gaming (hardware is not suitable for latest 3D Shooters)
- **AnyDesk** to manage machines remotely
- **Etcher** the easiest tool to write ISO images on USB thumb drives
- **Oracle Virtualbox** to run virtual machines on linux
- **gthumb Image Viewer** enables you to not only view, but also crop / resize / optimize pictures


* Resume
I like it so much - I even installed the OS bare-metal on an older notebook (with a SSD drive) and didn't regret it. The next linux distribution I'll install on my parent's PC will be Solus of course.

THANK YOU SOLUS TEAM FOR YOUR INCREDIBLE WORK!!

[Elementary]: http://elementary.io
[Solus]: http://solus-project.com
[Distrowatch]: https://distrowatch.com/table.php?distribution=solus
