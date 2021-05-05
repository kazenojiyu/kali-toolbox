Inspiration:
https://github.com/archcloudlabs/kali-up/

	
C2 frameworks
- https://github.com/its-a-feature/apfell
- https://github.com/mitre/caldera
- https://github.com/cobbr/covenant
- https://github.com/bc-security/empire.git
- https://github.com/elevenpaths/ibombshell.git
- https://github.com/zerosum0x0/koadic
- https://github.com/ne0nd0g/merlin
- https://github.com/p3nt4/nuages.git
- https://github.com/adrianvollmer/powerhub.git
- https://github.com/byt3bl33d3r/silenttrinity
- https://github.com/bishopfox/sliver
- https://github.com/trustedsec/trevorc2.git
- https://github.com/nettitude/poshc2

pwn_lin_dir
dest: "{{ base_dir+pwn_lin_dir }}/enumeration/
- https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite
- https://github.com/rebootuser/LinEnum
- https://github.com/diego-treitos/linux-smart-enumeration

dest: "{{ base_dir+pwn_lin_dir }}/payload_crafting/
- https://github.com/gaffe23/linux-inject
- https://github.com/gianlucaborello/libprocesshider

dest: "{{ base_dir+pwn_lin_dir }}/web/
- https://github.com/OJ/gobuster
- https://github.com/tls-attacker/TLS-Attacker
  

dest: "{{ base_dir+pwn_lin_dir }}/cred_dumping/
- https://github.com/huntergregal/mimipenguin
- https://github.com/AlessandroZ/LaZagne
 

dest: "{{ base_dir+pwn_lin_dir }}/rootkits/
- https://github.com/f0rb1dd3n/Reptile
- https://github.com/mempodippy/vlany
- https://github.com/chokepoint/azazel
- https://github.com/chokepoint/Jynx2
- https://github.com/chokepoint/jynxkit
- https://github.com/ChristianPapathanasiou/apache-rootkit
- https://github.com/mncoppola/suterusu
- https://github.com/jermeyyy/rooty
- https://github.com/m0nad/Diamorphine

pwn_win_dir
dest: "{{ base_dir+pwn_win_dir }}
- https://github.com/BloodHoundAD/BloodHound
- https://github.com/byt3bl33d3r/CrackMapExec
- https://github.com/trustedsec/unicorn
- https://github.com/Hackplayers/evil-winrm
- https://github.com/PowerShellMafia/PowerSploit.git  
- https://github.com/GhostPack/KeeThief
- https://github.com/GhostPack/Seatbelt
- https://github.com/GhostPack/SharpUp
- https://github.com/GhostPack/SafetyKatz
- https://github.com/GhostPack/SharpDump
- https://github.com/GhostPack/SharpWMI  
- https://github.com/GhostPack/Rubeus
- https://github.com/GhostPack/SharpDPAPI
- https://github.com/GhostPack/Lockless
- https://github.com/GhostPack/SharpRoast
- https://github.com/cobbr/PSAmsi.git
- https://github.com/Tylous/Limelighter


dest: "{{ base_dir+pwn_win_dir }}/references/
    - https://github.com/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet


dest: "{{ base_dir+pwn_win_dir }}"
- https://download.sysinternals.com/files/SysinternalsSuite.zip
- https://github.com/gentilkiwi/mimikatz/releases/download/2.2.0-20200918-fix/mimikatz_trunk.zip

re_dir
dest: "{{ base_dir+re_dir }}"
- https://out7.hex-rays.com/files/idafree70_linux.run
- https://ghidra-sre.org/ghidra_9.2.3_PUBLIC_20210325.zip
- https://github.com/rizinorg/cutter/releases/download/v2.0.2/Cutter-v2.0.2-x64.Linux.AppImage


- capstone 
- unicorn
- keystone-engine
- ropper
- pwntools


url: https://github.com/hugsy/gef/raw/master/scripts/gef.sh 
