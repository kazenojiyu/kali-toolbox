# Kali toolbox installer

This tool uses Ansible to work.
To install Ansible, look at the [installation guide](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-the-ansible-community-package).

These tools are very usefull for pentesting, CTF and red-teaming.

This project was originally inspired by:
https://github.com/archcloudlabs/kali-up/

# Installation

Launch installation of the whole packages:
```
ansible-playbook launch.yml
```

You can install only parts of the tools by using Ansible tags:
```
ansible-playbook launch.yml --tags "network"
```

Different tags are:
- system
- c2
- reverse
- windows
- linux
- network
- wiki

# System


# C2 Matrix

The C2 Matrix includes lot of tools well known but also propose a laboratory to try these tools.

[C2 Matrix documentation](https://howto.thec2matrix.com/)

List of installed tools:
- [apfell](https://github.com/its-a-feature/apfell.git)
- [caldera](https://github.com/mitre/caldera.git)
- [covenant](https://github.com/cobbr/covenant.git)
- [empire](https://github.com/bc-security/empire.git)
- [ibombshell](https://github.com/elevenpaths/ibombshell.git)
- [koadic](https://github.com/zerosum0x0/koadic.git)
- [merlin](https://github.com/ne0nd0g/merlin.git)
- [nuages](https://github.com/p3nt4/nuages.git)
- [powerhub](https://github.com/adrianvollmer/powerhub.git)
- [silenttrinity](https://github.com/byt3bl33d3r/silenttrinity.git)
- [sliver](https://github.com/bishopfox/sliver.git)
- [trevorc2](https://github.com/trustedsec/trevorc2.git)
- [poshc2](https://github.com/nettitude/poshc2.git)

# Linux tools

## enumeration
- [privilege-escalation-awesome-scripts-suite](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite.git)
- [LinEnum](https://github.com/rebootuser/LinEnum.git)
- [inux-smart-enumeration](https://github.com/diego-treitos/linux-smart-enumeration.git)

## payload_crafting
- [linux-inject](https://github.com/gaffe23/linux-inject.git)
- [libprocesshider](https://github.com/gianlucaborello/libprocesshider.git)

## web
- [gobuster](https://github.com/OJ/gobuster.git)
- [TLS-Attacker](https://github.com/tls-attacker/TLS-Attacker.git)
  

## cred_dumping
- [mimipenguin](https://github.com/huntergregal/mimipenguin.git)
- [LaZagne](https://github.com/AlessandroZ/LaZagne.git)
 

## rootkits
- [Reptile](https://github.com/f0rb1dd3n/Reptile.git)
- [vlany](https://github.com/mempodippy/vlany.git)
- [azazel](https://github.com/chokepoint/azazel.git)
- [Jynx2](https://github.com/chokepoint/Jynx2.git)
- [jynxkit](https://github.com/chokepoint/jynxkit.git)
- [apache-rootkit](https://github.com/ChristianPapathanasiou/apache-rootkit.git)
- [suterusu](https://github.com/mncoppola/suterusu.git)
- [rooty](https://github.com/jermeyyy/rooty.git)
- [Diamorphine](https://github.com/m0nad/Diamorphine.git)

# Windows tools
- [BloodHound](https://github.com/BloodHoundAD/BloodHound.git)
- [BloodHound.py](https://github.com/fox-it/BloodHound.py)
- [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec.git)
- [unicorn](https://github.com/trustedsec/unicorn.git)
- [evil-(winrm]https://github.com/Hackplayers/evil-winrm.git)
- [PowerSploit](https://github.com/PowerShellMafia/PowerSploit.git)
- [KeeThief](https://github.com/GhostPack/KeeThief.git)
- [Seatbelt](https://github.com/GhostPack/Seatbelt.git)
- [SharpUp](https://github.com/GhostPack/SharpUp.git)
- [SafetyKatz](https://github.com/GhostPack/SafetyKatz.git)
- [SharpDump](https://github.com/GhostPack/SharpDump.git)
- [SharpWMI](https://github.com/GhostPack/SharpWMI.git)
- [Rubeus](https://github.com/GhostPack/Rubeus.git)
- [SharpDPAPI](https://github.com/GhostPack/SharpDPAPI.git)
- [Lockless](https://github.com/GhostPack/Lockless.git)
- [SharpRoast](https://github.com/GhostPack/SharpRoast.git)
- [PSAmsi](https://github.com/cobbr/PSAmsi.git)
- [Limelighter](https://github.com/Tylous/Limelighter.git)
- [nishang](https://github.com/samratashok/nishang.git)
- [kerbrute](https://github.com/ropnop/kerbrute.git)
- [ActiveReign](https://github.com/m8r0wn/ActiveReign.git)
- [powercat](https://github.com/besimorhino/powercat.git)
- [SysinternalsSuite](https://download.sysinternals.com/files/SysinternalsSuite.zip)
- [mimikatz_trunk](https://github.com/gentilkiwi/mimikatz/releases/download/2.2.0-20200918-fix/mimikatz_trunk.zip)

## enumeration
- [privilege-escalation-awesome-scripts-suite](https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite.git)
- [wesng](https://github.com/bitsadmin/wesng.git)
- [windows-privesc-check](https://github.com/pentestmonkey/windows-privesc-check.git)


# Reverse engineering
- [idafree70_linux](https://out7.hex-rays.com/files/idafree70_linux.run)
- [ghidra_9.2.3](https://ghidra-sre.org/ghidra_9.2.3_PUBLIC_20210325.zip)
- [Cutter-v2.0.2](https://github.com/rizinorg/cutter/releases/download/v2.0.2/Cutter-v2.0.2-x64.Linux.AppImage)
- [capstone](https://github.com/aquynh/capstone.git)
- [unicorn](https://github.com/unicorn-engine/unicorn.git)
- [keystone-engine](https://github.com/keystone-engine/keystone.git)
- [ropper](https://github.com/sashs/Ropper.git)
- [pwntools](https://github.com/Gallopsled/pwntools.git)
- [gef](https://github.com/hugsy/gef.git)

# Network
- [impacket](https://github.com/SecureAuthCorp/impacket.git)
- [smtp-user-enum](https://github.com/pentestmonkey/smtp-user-enum.git)
- [ftp-user-enum](https://github.com/pentestmonkey/ftp-user-enum.git)
- [finger-user-enum](https://github.com/pentestmonkey/finger-user-enum.git)
- [rsh-grind](https://github.com/pentestmonkey/rsh-grind.git)
- [windapsearch](https://github.com/ropnop/windapsearch.git)

# Wiki
- [hacktricks](https://github.com/carlospolop/hacktricks.git)
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings.git)
- [Active-Directory-Exploitation-Cheat-Sheet](https://github.com/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet.git)