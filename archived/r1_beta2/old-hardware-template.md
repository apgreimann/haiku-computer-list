### What is this file?

This is an example of how hardware should be listed on the [Computers compatible with Haiku](https://discuss.haiku-os.org/t/computers-compatible-with-haiku-v3/7640)
thread on the Haiku forum if you opt to submit your hardware manually.

### Notes:

* For category or **form factor**, please list if your computer should be filed under:
All-in-One Desktops, General-purpose laptops/portables, Tablets/Convertibles, Notebooks,
Desktops, (Mobile) Workstations, Servers, Thin Clients, or VMs.
* For **rating**, please choose between 1 and 4, where: 1/4 means Haiku does not work on this machine,
2/4 means Haiku barely works or needs extra options to start, 3/4 means Haiku works with most of the components,
or 4/4 means Haiku works with all (or nearly all) of the components.
* Several detailed options, such as SD drive, graphics, sound, restart, and network status is optional,
and is up to you as the contributor to add or leave out. Please do include your rating, make and model, Haiku
revision, and startup mode, however.

### Example template:

Form factor: (Desktop, laptop, tablet, netbook, server, etc.)

(Make and model)

Rating: (1 being the poorest rating; 4 the best rating)

Version/branch: (Beta or Nightly; if Nightly, please also include the hrev)

Architecture: (i.e. x86, x86_64, sparc, etc.)

Share on GitHub: (Yes/no)

Started from: (Internal/external HD/SSD, USB, network, etc.)

Startup mode: (Legacy CSM/BIOS or UEFI)

Memory: (amount of RAM in system)

CPU: (processor model and speed)

GPU: (graphics card model)

Networking cards: (network cards model)

Sound cards: (audio/sound cards model)

Graphics status: (Graphics work, work only with workaround, or do not work)

Sound status: (Sound works, works only with workaround, or does not work)

Networking status: (Ethernet/WiFi works or does not work/connect)

SD status: (Does/does not work)

Restart status: (Restarts smoothly, restarts only with a mod, does not restart well)

Input devices: (Report if the keyboard, trackpad, or touch works on mobile computers)

Power status: (For mobile computers; does the battery/meter work with Haiku?)

Cam status: (Report if webcams work)

Additional notes: (Anything you’d like the Haiku community to read can go here)

Contributor: (if you wish to add yourself here)

Contribution date: (current date; 5 Feb 2020)

### Sample listing:

Form factor: Mobile Workstation

Leafbox Solstice 2020

Rating 4/4: Haiku works with all (or nearly all) of the components

Version/branch: Haiku Nightly (revision hrev53644)

Architecture: 64-bit x86 (Intel x64/AMD64, etc.)

Share on GitHub: Yes

Started from: USB storage media (using USB 3.0), Internal SSD, Optical media

Startup mode: (U)EFI, but because my computer only supports EFI (64-bit)

Memory: 8 GB

CPU: Intel i5-520M, 3M cache, 2.40 GHz x2, 4 threads

GPU: Intel Integrated Graphics

Networking cards: Broadcom 4312G 802.11b/g WiFi Adapter

Sound cards: Creative Sound Blaster Audigy FX

Graphics status: Graphics work out of the box

Sound status: Sound works

Networking status: Both Ethernet and WiFi cards work

SD status: Works with Haiku

Restart status: Haiku restarts smoothly

Input devices: Both the trackpad and keyboard work

Power status: Haiku detects the battery and reports the battery percentage normally

Cam status: My computer does not have (web)cams	

Additional notes (multi-line): Graphics need to be in Vesa mode on this machine to work properly.		

Contributor: apgreimann

Contribution date: 5 Feb 2020
