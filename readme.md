# Installing WSL
cmd in administrator mode

Microsoft's documentation says you can do this in powershell, but I found it won't install and asks you to install your distro using microsoft store in powershell

    wsl --install

To install a specific wsl distro:

    wsl -- install -d <Distro>

Distros available:

- Ubuntu
- Debian
- kali-linux
- Ubuntu-18.04
- Ubuntu-20.04
- Ubuntu-22.04
- OracleLinux_7_9
- OracleLinux_8_7
- OracleLinux_9_1
- openSUSE-Leap-15.5
- SUSE-Linux-Enterprise-Server-15-SP4
- SUSE-Linux-Enterprise-15-SP5
- openSUSE-Tumbleweed

Example:
>wsl -- install -d Ubuntu


# Configuring WSL
Enter new UNIX username
Enter new UNIX password

That's it!


# Helpful commands
Check wsl version:

    wsl -l -v

Update WSL:

    wsl.exe --update