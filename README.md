# MacOS OpenCore for Intel i3 10th Generation Desktop with AMD Radeon RX 570 4 GB

## Introduction
For the past few months, I've been working on getting macOS to run on my Intel desktop PC using OpenCore as the bootloader. It was a bit of a challenge at first. I spent a ton of time researching and experimenting with various settings. I had to use the integrated graphics card, the Intel UHD Graphics 630, because I still don’t have a dedicated GPU.

Once I got the system up and running, I quickly found out that the integrated graphics card couldn't handle some of the more demanding applications that I needed to use. So, I decided to upgrade to the AMD Radeon RX 570 4 GB, which worked like a charm with my setup. However, getting it to work required a bit more tweaking to make sure my system used the dedicated graphics card instead of the integrated one.

After many more hours of tweaking and testing, I finally had a fully functional system that could handle everything I needed. It definitely wasn't easy or quick, but I learned a lot along the way and am pretty stoked with what I was able to accomplish.


## OpenCore
- Version 0.8.8 

- **Guide Followed:** Dortania's MacOS OpenCore Install Guide[^dortania]

## macOS Version
- Monterey

## Hardware
**CPU:** Intel Core i3-10105

**GPU:** AMD Radeon RX 570 4G

**RAM:** 2 x 8 GB Kingston 2666 MHz

**Motherboard:** MSI B460M-A Pro

**Audio Codec:** `layout-id = 11`

**Ethernet Card:** Realtek PCIe GBe Family Controller (using RTL8111 kext)

**Wifi/BT Card:** N/A


## Working and Not Working
- Everything works *except for iMessage*.

## Appreciation
As a lurker, a huge thanks to r/Hackintosh subreddit[^hackintosh] and the Hackintosh Paradise Discord[^discord] server for their invaluable insights with the project, especially for the guides provided by the subreddit and the experiences shared by other users.

##### Footnote

[^dortania]: https://dortania.github.io/OpenCore-Install-Guide/
[^hackintosh]: https://www.reddit.com/r/hackintosh/
[^discord]: https://discord.com/invite/Wxam8aH
