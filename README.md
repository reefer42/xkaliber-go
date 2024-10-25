# xkaliber-go
Legion Go xkaliber OS
https://youtu.be/DncBiXCuKzM?si=fQ5LpOkCE-VviueS PREVIEW
# xkaliber-go
Legion Go xkaliber OS
I created a unique Debian-based OS that I use daily, still with minor bugs due to the Legion Go platform. If you're experienced and want to tackle these remaining issues, feel free to take it on!

Features:

ROCM drivers pre-installed, no need for extra setup

Waydroid and Pop Shop, a non-traditional app store that allows for easy management of your host system

Local DNS Cache Server for improved network speeds and reduced latency

Four optional preinstalled desktops, with Plasma Mobile as the dedicated desktop environment
No TDP support, but I planned to add it - just ran into some issues.

Removed old firmware-amd-graphics and replaced it with the latest Trixie version (still working on fixing flicker)

System-wide keyboard support in Plasma Mobile

Docker installed, but requires manual enablement and permissions setup

## ISO Download Link: https://drive.google.com/file/d/1dpMj3h90YysO0wE-eyOfFe7lG6BNCod2/view?usp=drive_link
## Password: 0000
I'd be happy to continue improving this OS with assistance, but for now, feel free to take it and modify as you see fit!

**DO NOT use scripts from other branches or projects; doing so will break xkaliber.**

https://drive.google.com/file/d/1pmCn6dgDE7JOl8AqzPEI2HHfH9w_qutU/view?usp=sharing
This is the updated image with ROCM and my attempt to replace firmware-amd-graphics with current Trixie version.

To modify the DNS Cache Server, run `sudo nano /etc/dnsmasq.conf`.

## Known Issues:

Legion Go: Mouse cursor flicker when visible

Unknown: Asus Ally (testing required)

Nvidia users: Download and use the xkaliber repo's utility to easily install your drivers

**A Major Comment:** You can always disable the mouse cursor, as the OS is fully touch-friendly with a reliable keyboard. No Maliit on Bazlite!

I'm still working on polishing this OS as solutions come along. Hand-held daemon will be included in future image links.

## Update:
After suggestions from former testers, I've decided to include a full-blown Kali Linux edition, tailored for AMD support and drivers, with focus on gaming (including virtual reality), ROCm, and AI support via ROCm.

Kali Image Beta is now available! It doesn't have the hand-held daemon yet but includes:

Rebuilt kernel 6.8 for GBinder Waydroid and ROCm
Added lib5 and set up prerequisites for Docker Distro Box

No personalized content has been worked in, but the desktop environment and basic functionality do work.

The image is currently uploading and will be available soon.

Kali Image does NOT have flicker on Legion Go!
