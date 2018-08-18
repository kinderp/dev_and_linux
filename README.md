# open_source_dev_git_and_linux

# Cheatsheet

## SysVinit to Systemd Cheatsheet
* [Fedora](https://fedoraproject.org/wiki/SysVinit_to_Systemd_Cheatsheet)
* [Debian](https://wiki.debian.org/systemd/CheatSheet)
* [openSUSE](https://en.opensuse.org/openSUSE:Cheat_sheet_13.1#Services)

# LF Projects

* Big Data 
  * [odpi](https://www.odpi.org/) [r-consortium](https://www.r-consortium.org/)
* Networking 
  * [opendaylight](https://www.opendaylight.org/) 
  * [opnfv](https://www.opnfv.org/) 
  * [onap](https://www.onap.org/)
* Embedded 
  * [dronecode](https://www.dronecode.org/) 
  * [zephyrproject](https://www.zephyrproject.org/)
* Web Tools 
  * [js foundation](https://js.foundation/)  
  * [nodejs](https://nodejs.org/en/)
* Cloud 
  * [cloudfoundry](https://www.cloudfoundry.org/) 
  * [cloud nnative computing foundation](https://www.cncf.io/) 
  * [open containers initiative](https://www.opencontainers.org/)
* Automative 
  * [automotive](https://www.automotivelinux.org/)
* Security 
  * [the core infrastructure initiative](https://www.coreinfrastructure.org/)
* Blockchain 
  * [hyperledger](https://www.hyperledger.org/)

# [Open Source Guides For The Enterprise](https://www.linuxfoundation.org/resources/open-source-guides/)
Leverage best practices for running an open source program office or starting an open source project in your organization. Developed by The Linux Foundation in partnership with the TODO Group, these resources represent the experience of our staff, projects, and members.

# System Info

* [uname](https://linux.die.net/man/1/uname)
```bash
>uname --help
Usage: uname [OPTION]...
Print certain system information.  With no OPTION, same as -s.

  -a, --all                print all information, in the following order,
                             except omit -p and -i if unknown:
  -s, --kernel-name        print the kernel name
  -n, --nodename           print the network node hostname
  -r, --kernel-release     print the kernel release
  -v, --kernel-version     print the kernel version
  -m, --machine            print the machine hardware name
  -p, --processor          print the processor type (non-portable)
  -i, --hardware-platform  print the hardware platform (non-portable)
  -o, --operating-system   print the operating system
      --help     display this help and exit
      --version  output version information and exit

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Full documentation at: <https://www.gnu.org/software/coreutils/uname>
or available locally via: info '(coreutils) uname invocation'

```

```bash
>uname -a
Linux linux-pnjx 4.12.14-lp150.12.7-default #1 SMP Tue Jul 17 12:08:37 UTC 2018 (4804d19) x86_64 x86_64 x86_64 GNU/Linux
```

```bash
>uname -s
Linux
```

```bash
>name -n
linux-pnjx
```

```bash
>uname -r
4.12.14-lp150.12.7-default
```

```bash
>uname -v
#1 SMP Tue Jul 17 12:08:37 UTC 2018 (4804d19)
```

```bash
>uname -m
x86_64
```

```bash
uname -p
x86_64
```

```bash
>uname -i
x86_64
```
 
```bash
>uname -o
GNU/Linux
```
 


