---
name: Vanessa Garcia
semester: Fall 23
course: cis106
---

# Week Report 3

## Summary of presentation

### Introduction to Linux

**What is an operating system?**
<li>fundamental software of computer</li>
<li>OS enables you to use computer hardware providing basic tools</li>
<li>all of the OS feature relay on kernel</li>

**Aside from a kernel, what other parts make an operating system?**
<li>Command Line Shells-  </li>
<li>Graphical User Interface- </li>
<li>Utility and Productivity Program-</li>
<li>Libraries</li>

**What is a Linux distribution?**
<li>it's a  complete Linux system package</li>
The following make up linux distribution
<li>Linux Kernel = diff distrib. use version</li>
<li>Core Linux Tools = ex: GNU toolset , X windows System DeskTop Env.</li>
<li>Supplemental Software = server apps.user apps.</li>
<li>Startup Script = scripts that differentiate diff distribution,they range from launching dozen of programs at startup to even modify the way desktop environ.behaves</li>
<li>An Installer = diff distribution use diff installer & manage software differently.Key element is package manager a distribution uses.</li>
Two main Linux Distribution are:
<li>Debian - Ubuntum - Pop OS </li>
<li>RedHat - Fedora - Alma Linux </li>

**What is Ubuntu?**
<li>It's a Linux Distribution freely available with both community & professional support</li>
<li>Ununtu Manifesto: should be free, usable by ppl in their local language despite disabilities, customize and alter software</li>

**Define the following terms:** 
<li>Open Source = sw may be distrib for a fee or free.The code is distrib w/ sw</li>
<li>Closed source = sw is not distributed w/ a source code,user is restricted from modifying code</li>


**What are the 4 freedoms defined by the free software foundation?**
<li>Freedom 0 = use SW for any purpose</li>
<li>Freedom 1 = examine the source code & modify it as you see fit</li>
<li>Freedom 2 = redistribute the software </li>
<li>Freedom 3 = redistribute your modified software</li>

### The basic of Virtualization
**What is virtualization?**
<li>creating virtual version of something</li>
<li>Virtualization often used to let multiple OS run on one physical machine at the same time</li>
<li>Virt. allows administrator to divide hardware & create multiple computer inside single physical computer</li>
<li>Old but faster better & cheap hardware</li>
<li>Cloud Computing</li>

**List 3 benefits of virtualization**
<li>Allows run many OS on one machine w/o dual booting</li>
<li>Allows app to be tested before installing them on host machine</li>
<li>Reduce cost by decrease physical hardware must be purchased for network</li>
<li>Offers the ability ti save state of machine at given time & roll it back or forward</li>
<li>It allow programs coded for one type hardware or OS to work on other not designated to work on</li>
<li>Can be used to keep legacy app sandboxed & run past their end of life</li>

**What is a hypervisor?**
<li>software or hardware in charge of creating, managing & running virtual machine</li>
Two Types of Hypervisors:
<li>Type 1 (bare-metal hypervisor)= Runs directly on hardware.It's an OS for physical machine. Better performance than Type 2 b/s there is no host OS & system support virtualization</li> 
<li>Type 2 = is app that runs on top of OS.Most common used in client-side virtualization. Host OS consumes resources & a host OS failure means virtual machine will fail also</li>
<li>All hypervisor fall under two categories:</li>
    <li>client side & server side</li>

**What is virtualbox**
<li>powerful x86 & AMD64/Intel64 virtualization product for enterprise as well as home use, Open source under terms of the GNU General Public Licenser (GPL) version 3 </li>

### Exploring Desktop Environments
**What is a desktop environment? (Provide 3 examples)**
<li>made of a bundle of programs running on top of computer OS which share common GUI or described graphical shell </li>
<li>Desktop Setting = program that allow you to make configuration changes to desktop.</li>
<li>System Tray = special menu, commonly attached to panel. Provide acces to program that allows user to log out,lock screen, notification, shut down or reboot</li>
<li>Widget = provide user info or functionality on desktop.Widget divide into applets, screenlets,desklets</li>

**What is Ubuntu’s default desktop environments?**
<li>GNOME 3 = GNU Network Object Model Environment</li>

**What are the official flavors of Ubuntu?**
</li>Edubuntu is an official flavor of Ubuntu crafted for use in the education world. </li>
<li>Kubuntu unites Ubuntu with KDE and the Plasma desktop, bringing you a full set of applications including productivity, office, email, graphics, photography, and music applications ready to use at startup with extensive additional software installed from not one, but two desktop package managers.</li>
<li>Ubuntu Budgie is modern and fast desktop distribution with great defaults, yet fully customizable.</li>
<li>The Ubuntu Kylin project is tuned to the needs of Chinese users, providing a thoughtful and elegant experience out-of-the-box. The lightweight Ubuntu Kylin User Interface (UKUI) is perfect for older machines, and an ideal introduction to Linux for first-time users.</li>
<li>Xubuntu comes with Xfce, which is a stable, light and configurable desktop environment with a lot of consideration for usability.</li>
<li>Ubuntu MATE is a stable, easy-to-use operating system with a configurable desktop environment. It is ideal for those who want the most out of their computers and prefer a traditional desktop metaphor.Ubuntu MATE makes modern computers fast and old computers usable.</li>
<li>Ubuntu Cinnamon combines Ubuntu with the intuitive Cinnamon desktop. Built upon the legacy of GNOME 2. The hassle free desktop allows for deep personalization options and add-ons for a little extra spice.</li>

### What is a Shell?
**What is Bash?**
<li>program that provide interactive access yo linux system.</li>
<li>Runs as a egular program & is normally started when user logs into terminal</li>

**How do you access the Linux CLI?**
<li>terminal emulator that allows </li>

**What is a console terminal?**
<li>cannot run graphic program</li>
<li>allows to switch to another virtual console w/o losing active session</li>

**What is a terminal emulator?**

<li>program that allows access to Linux CLI</li>

**Provide 3 examples of Linux commands**
<li>Ctrl + L = clear screen</li>
<li>Ctrl +C = terminate command </li>
<li>Ctrl + Z = suspend / stop command </li>

### Managing Software
**Which command is used for updating ubuntu**
<li>sudo apt update; sudo apt upgrade -y </li>

**Which command is used for installing software. Provide an example.**
<li>sudo apt install</li> 
<li>EXAMPLE: sudo apt install screenfetch -y </li>

**Which command is used for removing software. Provide an example.**
<li>sudo apt remove screenfetch -y <li>
<li>EXAMPLE: sudo apt remove screenfetch -y </li>
sudo apt search 

**Which command is used for searching for software. Provide an example.**
<li>apt-cache search 'Name of software'</li>
<li>apt-cache search screenfetch </li>

Define Terms:
**Package**
<li>archives that contain binaries of software, configuration files & info about dependencies.</li>

**Library**
<li>reusable code that can be used by more than one function or program</li>

**Repository**
<li>large collection of software available to download</li>