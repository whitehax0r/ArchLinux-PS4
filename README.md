 👋 Hi, I’m @whitehax0r
- 👀 I’m interested to share my little knowledge to this greatest community, my native language is Spanish but also speak English.
- 🌱 I’m currently learning cybersecurity as part of the red team those are more focused to attack and break the matrix xD.
- 💞️ I’m looking to collaborate on PS4 linux community and other interest stuff.
- 📫 How to reach me at the end of this file.
<!---
whitehax0r/whitehax0r is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

First Github project, proudly made by a latino catracho 🤠

# ArchLinux-PS4

This is a compiled and updated Arch linux with some minor personal changes more related to GUI to look better and included emulators.

# Features

- Parallel Downloads enabled.
- PS4 repository enabled.
- LightDM with autologin enabled window manager.
- Neofetch - Show general information about this system.
- Latest PS4 Drivers from oficial repo.
- XFCE - Desktop Environment.
- Steam - The ultimate destination for playing, discussing, and creating games.
- ExFat file system support.
- Bluez - For bluetooth pairing PS4 controller.
- Blueberry - GUI compatible with XFCE/GTK.
- Duckstation - Best PSX emulator.
- Dolphin emulator - Nintengo Wii and Gamecube emulator.
- Nano - Text editor.
- Chromium - Web browser.
- Powerlevel10k - ZSH terminal.
- PCSX2 - Playstation 2 emulator with vulkan support.
- Yabaouze - Sega Dreamcast emulator.
- Hacknerdfonts - For icons inside ZSH and customized fonts for terminal.
- RetroArch - Multiplatform emulator.
- Minecraft Java - Because is fun. :pick:
- LSD - Powered LS bassically.
- BAT - Powered CAT bassically.
- VLC - Video player.
- Spotify - Music player.
- Yay - Yet another yogurt. Pacman wrapper and AUR helper written in go.
- Zip - Compress files to zip files.
- Unzip - Uncompress zip files.
- P7zip - Commandline 7zip support for Linux.
- Htop - See process and other stuff.

# My PS4 Hardware

- PS4 Slim
- Firmware 9.00
- Model CUH-2115B.
- SouthBridge Baikal.

## If you have same PS4 hardware as me you can use these files from below:

- [bootargs.txt](https://github.com/whitehax0r/ArchLinux-PS4/blob/4add3a72d25dcfabff433283606b9ce30762d4d9/bootargs.txt) MD5 >__C84AD779CE76762C04CBF80E420E324D__
- [initramfs.cpio.gz](https://github.com/whitehax0r/ArchLinux-PS4/blob/4add3a72d25dcfabff433283606b9ce30762d4d9/initramfs.cpio.gz) MD5 >__951549B1DEB59DAE3ADA8038461BADD2__
- [bzImage](https://github.com/whitehax0r/ArchLinux-PS4/blob/4add3a72d25dcfabff433283606b9ce30762d4d9/bzImage) MD5 >__B8BDDA64FDED673D1FD8017C2A4B4122__
- [arch.tar.xz](https://mega.nz/file/6ro0mZqb#uzVI3PjhxZ7m5hk4EC2AxCIg5B8h87mqEuvUEzo20Oo) MD5 >__7A997C14B2FAD0C839107A07C69FC312__

# Preparing your USB 3.0 Device for ArchLinux-PS4

:warning: Highly recommeded to use a USE A >=16GB USB 3.0 Device :warning:

- Format the USB 3.0 Device to Fat32 filesystem.
- Copy and paste the bzImage, the initramfs.cpio.gz, bootargs.txt and arch.tar.xz files to the root of the USB 3.0 Device.
- :warning: If you use the same initramfs.cpio.gz from my Github, this one is created by Nazky, the name of this OS should be arch.tar.xz :warning:
- :warning: __If you use the initramfs.cpio.gz from psxita team, you should rename this file arch.tar.xz to psxitarch.tar.xz__ :warning:
- The total of 4 files should be on the root of your USB 3.0 Device bzImage, the initramfs.cpio.gz, bootargs.txt and arch.tar.xz or psxitarch.tar.xz.
- Open the PS4 web browser and first jailbreak your PS4 with Al-Azif [host](https://cthugha.exploit.menu/#PS4%20(9.00))follow the instructions on the website.
- Launch the 1GB Linux payload using the one of your trust host but I recommend to you to use this [one](https://sleirsgoevy.github.io/900-host/)from [Sleirsgoevy](https://github.com/sleirsgoevy) because this one detects the bootargs.txt file to avoid black screen issues. __I tried with other host but did not detect the bootargs.txt file.__

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
- When you are on the rescushell type the following commands:
>__exec install-psxitarch.sh__
- :warning: If you use the initramfs.cpio.gz from Nazky type the following commands: :warning:
>__exec install-arch.sh__
- When the installation is done ArchLinux-PS4 is going to boot automatically, if not type the following command:
>__exec start-psxitarch.sh__
-  :warning: If you use the initramfs.cpio.gz from Nazky type the following commands: :warning:
>__exec start-arch.sh__
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

# TODO LIST

- RPCS3 emulator - PS3 emulator. (You can try with the AppImage in their [website.](https://rpcs3.net/download))
- ProtonDB play windows games on linux.
- Nothing more, you tell me.

# KNOW ISSUES

Not sure why but every time you boot in to linux, you have to set your current time and date, just type the following commands on terminal as root: 

>__# timedatectl set-time "yyyy-MM-dd hh:mm:ss"__

For example:

>__# timedatectl set-time "2022-02-19 13:13:54"__

Not sure why but every time you boot in to linux, you have to set to unpair and pair again your PS4 controller in every boot.

# Social Medias

- You can follow me on [Twitter](https://twitter.com/razr2312)
- You can follow me on [YouTube](https://www.youtube.com/user/allank2312/videos)

![esta es una imagen](https://github.com/whitehax0r/ArchLinux-PS4/blob/353059a5bbb0a7f161ade53a56e374a6398d7c6a/Flag.png)

<!---
This information wouldn't be possible and I have to thanks to @Nazky @SpecterDev @failoverfl0w @theflow @chendochap @AlAzzif, etc.
--->


