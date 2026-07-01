# Raspberry Pi 5 Setup

This guide provides the high-level steps to prepare a Raspberry Pi 5 for development. Follow the linked official documentation for detailed instructions.



## 1. Flash Raspberry Pi OS

Use **[Raspberry Pi Imager](https://www.raspberrypi.com/software/)** to install **Raspberry Pi OS Lite (64-bit)** on a microSD card.

> [!TIP]
> This guide recommends **Raspberry Pi OS Lite (64-bit)** instead of the Desktop edition.
>
> Using the Lite version encourages you to become familiar with the Linux command line and SSH from the start. Nearly all server administration and development on Linux is performed from a terminal, making these skills valuable regardless of your future projects.

Before writing the image, use the **OS Customisation** options to configure:

- Hostname ex: (rpi)
- Username and password [READ Git inmstruction](git_setup.md)
- Enable SSH
- Wi-Fi settings

**Official documentation:**

- https://www.raspberrypi.com/software/
- https://www.raspberrypi.com/documentation/computers/getting-started.html

## 2. Boot the Raspberry Pi

- Insert the microSD card.
- Connect the Raspberry Pi to your network (Ethernet recommended for the initial setup).
- Apply power and wait for the first boot to complete.

## 3. Connect using SSH

After the Raspberry Pi has booted, connect to it using an SSH client from your computer.

> [!TIP]
> Now read the [GIT setup](git_setup.md)

**Official documentation:**

- Raspberry Pi Remote Access (SSH): https://www.raspberrypi.com/documentation/computers/remote-access.html#ssh
- Windows OpenSSH: https://learn.microsoft.com/windows/terminal/tutorials/ssh

## 4. Install Homebrew

Install Homebrew by following the official Linux installation guide.

**Official documentation:**

- https://brew.sh/
- https://docs.brew.sh/Homebrew-on-Linux

## Next Steps

Your Raspberry Pi is now ready for additional software installation and development.
