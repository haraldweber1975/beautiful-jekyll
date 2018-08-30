---
layout: post
published: true
title: Review of Solus Linux 3
subtitle: Best in class Desktop Linux OS I've ever used
date: '2018-08-28'
image: /img/solus-logo.jpg
tags:
  - review
bigimg:
  - /img/solus_people.png: For you!
---
No matter if you're a Linux fanbox or a newbie: If you want to try out a new desktop oriented Linux distribution that even beats the great [Elementary OS][Elementary], continue to read my review of [Solus Linux][Solus].

* TOC
{:toc}

## 1. Installing Linux for fun
Installing a Linux distribution is sort of a hobby for me. Recently I discovered a very nice project about a _desktop oriented_ Linux distribution which is **not** based on Ubuntu / Debain / Slackware: [The Solus Project][Solus].  
You can find a lot of detailled information about this distribution on [Distrowatch]
They also maintain a list of Operating systems by popularity (based on distrowatch site-hits).
As of July 29th 2018 Solus ranked on **place 6 on their list** (considering data of the last 12 month).

## 2. My requirements
I always ask myself: Is it suitable for _my parents_?  
They are 70+ and total computer noobs. In other words - to OS needs to be parent-proof :smiling_imp:

### 2.1 rolling release - install once, upgrade forever
Every OS has its lifetime and after Windows XP reached the end of its live I installed [Elementary] on their PC as they didn't want to pay for a copy of Windows 7/8/10...
Now after approx 4 years it's time to install a new version of Elementary. Unfortunately it's not possible to do an in-line upgrade. Fresh install... time consuming and I need to ensure that every Icon / File / Link is available in the new OS.

{: .box-note}
In Solus you will not face this issue as it is a rolling-release Operating System.  
**Install once - upgrade forever**

### 2.2 Remote support
With Elementary I was always strugling with a proper 1-click remote-support solution. This is available in Solus through the 3rd-Party apps: **Anydesk**

### 2.3 Minimal maintenance through end-user
Wishfull thinking... Updates should be installable with least possible end-user involvement. Solus is doing a good job in notifying you about available updates.

## 3. Installation
Solus comes in 3 editions. Budgie, Mate, Gnome - I have chosen the "Budgie" edition simply 'cause I have the impression this is where the developers put most effort in
Next you need to decide how to install.

### 3.1 Install on VirtualBox
Start with VirtualBox if you just want to do a **test-drive**.
It's usually the easiest way to test-drive [Solus]
As usual somebody already created a [Youtube video] (https://www.youtube.com/watch?v=8UgduvZQVpY) for this.

### 3.2 Install on bare-metal
If you have spare notebook / PC, this is the recommended way. Solus in native speed without the overhead of virtualisation.

### 3.3 Install on top of an existing OS (Dual/Multi boot)
There's an ilustrated howto avaliable on [Wikihow](https://www.wikihow.com/Install-Solus).
I don't like the idea of having 2 OS on the same machine.  
It's just a matter of time till one of the OS is killing the bootloader - Especially if you have Windows installed as primary/secondary OS.  
Better use a Virtualisation system like Virtualbox.

### 3.4 The Installer
As all modern Linux Operating systems [Solus] comes with a graphical installer. [Solus] will boot into a live system and you can start the installer from a desktop link.
The Installer will ask you some basic questions like language settings, timezone, etc... No issues at all.

After a couple of minutes the system boots and you can login with the user-account you created during setup.

## 4. First Impression after booting into your new system
It is starting fast - really fast!
And it looks beautiful.
![Solus Budgie Desktop]({{site.baseurl}}/img/solus_budgie.png)


### 4.1 Unclulttered desktop, well structure menu
coming soon

### 4.2 Appstore (Software Center)
coming soon

## 5. Software
Solus comes with a vast number of already pre-installed applications

### 5.1 pre-installed Applications
- **Libre office** which will cover all your "office" needs like writing, presenting, calculating and drawing 
- **Archive Manager** to handle ZIP archives
- **Firefox or WEB** to browser the web
- **Thunderbird** for emails
- **Image Viewer** to view images (surprise surprise)
- **Rhythmbox** to listen to your music
- **Files** to manage your files (another surprising name)
- **Videos** to view ... guess what
You can either use the graphical **Software Center** or the command line tool **eopkg**

### 5.2 Recommended additional software
I installed additional applications to make the system even more suitable for my needs.
- **Albert** to quickly search applications, basic math and quick translations without leaving the keyboard
- **Geary** a beautiful and minimal email client (The default email client on Elementary OS)
- **Opera** to browse the web with style, adblocker, optional free-of-charge vpn
- **Dropbox** online storage with easy sharing options
- **Enpass** to manage the 174 passwords I have
- **Skype** to do cross-platform text and video chats
- **Steam** for gaming
- **AnyDesk** to manage a machine remotely
- **Etcher** the easiest tool to write ISO images on USB thumb drives
- **Oracle Virtualbox** and **Virtualbox Extensions** to run virtual machines on linux (this will not make sense if you're already running Solus on a virtual machine.
- **gthumb Image Viewer** enables you to view images and do basic adjustments (crop / resize / colour, etc...)

### 5.3 SNAP support (similar to .EXE files on Windows)
The SNAP system (by Utuntu) provides the possibility to run applications without the need to install all required dependencies on your main system.

### 5.4 Docker to the help for power-users
Compared to Ubuntu the package repositiry of Solus does not include a lot of "Server software" like Squid, Nextcloud, Apache...
For the majority of end-users it's simply not required. Therefore I appreciate the approach of Solus to NOT integrate as many services as possible. There are other Linux distributions for that.

I was playing around with [Docker] by accident and guess what - it's also available on Solus.
My way to install a "Service" on Solus is simply utilizing Docker / Docker-Compose. Works great and keeps your system clean and lean (no need to install a huge number of dependencies on your Desktop PC).

## 6. Resume
I like [Solus] so much - I even installed the OS bare-metal on an older notebook (with a SSD drive) and didn't regret it. The next linux distribution I'll install on my parent's PC will be Solus of course.

_**THANK YOU @SOLUS TEAM FOR YOUR INCREDIBLE WORK!!**_

[Elementary]: https://elementary.io
[Solus]: https://solus-project.com
[Distrowatch]: https://distrowatch.com/table.php?distribution=solus
[Ubuntu]: https//www.ubuntu.com
[Docker]: https://www.docker.com
