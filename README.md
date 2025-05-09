# Pro Audio Linux Machine
I created this guide to assist with commissioning a new OS installation for a Linux-based Pro Audio machine.

For this project, I chose Debian 12 (Bookworm) with the KDE Plasma desktop environment. There are many Linux distributions available, but I selected this one for several key reasons:

<li>Stability and Security: Debian 12 is a stable operating system known for its reliability and robust performance—essential qualities for a Pro Audio workstation. It also provides access to a vast software repository.</li>

<li>Long-Term Support: Debian 12 is expected to receive updates until at least June 2028, making it a solid choice for long-term projects.</li>

<li>Balanced Software Selection: In my view, Debian 12 comes with just the right number of pre-installed applications—enough to be functional out of the box, without unnecessary bloat.</li>

<li>User-Friendly Desktop Environment: KDE Plasma offers a familiar and intuitive interface, making it a smooth transition for users coming from Windows or macOS.</li><p></p>

Here is the location of the ISO I used to commission my machine:
https://cdimage.debian.org/debian-cd/current-live/amd64/iso-hybrid/debian-live-12.10.0-amd64-kde.iso

I chose the Live version of Debian so I could test my hardware before committing to a full installation. This allowed me to verify that components like Wi-Fi and my audio interface were working properly before installing the OS on my computer’s hard drive.  I would recommend that everyone do this before committing to a new install.  The last thing you want is to be searching for drivers after commissioning a new computer.

This guide is designed so users can follow along using terminal commands to set up their Linux system step by step. Note: Wine and Yabridge are only necessary if you plan to use Windows-based audio plugins. If you prefer to stick exclusively with Linux-native software, you can skip installing these tools.




