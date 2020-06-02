## Advanced Windows exploit development resources

Some resources, links, books, and papers related to mostly Windows Internals and anything Windows kernel related. Mostly talks and videos that I enjoyed watching. 

**These are all resources that I have personally used and gone through**

## Windows Rootkits

**Talks / video recordings**

- [11 part playlist -  Rootkits: What they are, and how to find them](https://www.youtube.com/watch?v=ewNo_poX7bA&list=PLF58FB7BCB20ED11A)
- [Hooking Nirvana](https://www.youtube.com/watch?v=pHyWyH804xE)
- [Alex Ionescu - Advancing the State of UEFI Bootkits](https://www.youtube.com/watch?v=dpG97TBR3Ys)
- [BlueHat v18 || Return of the kernel rootkit malware (on windows 10)](https://youtu.be/qVIxFfXpyNc)
- [Numchecker: A System Approach for Kernel Rootkit Detection](https://www.youtube.com/watch?v=TgMsMwsfoQ0)
- [DEF CON 26  - Ring 0 Ring 2 Rootkits Bypassing Defenses](https://www.youtube.com/watch?v=7AEMxaZhdLU)
- [Black Hat Windows 2001 - Kernel Mode Rootkits](https://www.youtube.com/watch?v=99Znv6tgYS0)
- [Black Hat Windows 2004 - DKOM (Direct Kernel Object Manipulation)](https://www.youtube.com/watch?v=1Ie20b5IGgY)
- [RTFM SigSegv1 - From corrupted memory dump to rootkit detection](https://www.youtube.com/watch?v=hlhM_q3ZHfQ)

**Articles / papers**

- [Dissecting Turla Rootkit Malware Using Dynamic Analysis](https://www.lastline.com/labsblog/dissecting-turla-rootkit-malware-using-dynamic-analysis/)
- [A quick insight into the Driver Signature Enforcement](https://j00ru.vexillium.org/2010/06/insight-into-the-driver-signature-enforcement/)
- [WINDOWS DRIVER SIGNING BYPASS BY DERUSB](http://www.sekoia.fr/blog/windows-driver-signing-bypass-by-derusbi/)
- [A Basic Windows DKOM Rootkit](https://blog.landhb.dev/posts/v9eRa/a-basic-windows-dkom-rootkit-pt-1/)


## Advanced Windows debugging

**Talks / video recordings**

- [Hacking Livestream #28: Windows Kernel Debugging Part I](https://www.youtube.com/watch?v=s5gOW-N9AAo)
- [Hacking Livestream #29: Windows Kernel Debugging Part II](https://www.youtube.com/watch?v=4Xo_FAx6P0A)
- [Hacking Livestream #30: Windows Kernel Debugging Part III](https://www.youtube.com/watch?v=7zTtVYjjquA)
- [WinDbg Basics for Malware Analysis](https://www.youtube.com/watch?v=QuFJpH3My7A)
- [Windows Debugging and Troubleshooting](https://www.youtube.com/watch?v=2rGS5fYGtJ4) 
- [CNIT 126 10: Kernel Debugging with WinDbg](https://www.youtube.com/watch?v=8sVZsxoCpSc)
- [Windows Kernel Debugging Part I](https://www.youtube.com/watch?v=s5gOW-N9AAo)

**Articles / papers**

- [Getting Started with WinDbg - kernelmode](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/getting-started-with-windbg--kernel-mode-)

## 0days - malware stuff

**Talks / video recordings**

- [Kernel Mode Threats and Practical Defenses](https://www.youtube.com/watch?v=BBJgKuXzfwc)
- [Selling 0-Days to Governments and Offensive Security Companies](https://www.youtube.com/watch?v=ZDHHGZlEfsQ)

**Articles / papers**

## Video game cheating (kernel mode stuff sometimes)

**Talks / video recordings**

- [Unveiling the Underground World of Anti-Cheats](https://www.youtube.com/watch?v=yJHyHU5UjTg)

**Articles / papers**

- [Driver aka Kernel Mode cheating](https://www.unknowncheats.me/forum/anti-cheat-bypass/271733-driver-aka-kernel-mode.html)

## VM / sandbox escape 

**Talks / video recordings**

- [Vulnerability Exploitation In Docker Container Environments](https://www.youtube.com/watch?v=77-jaeUKH7c)
- [Modern Exploitation of the SVGA Device for Guest-to-Host Escapes](https://www.youtube.com/watch?v=Y-G2WJ2cBKE)
- [REcon 2014 - Breaking Out of VirtualBox through 3D Acceleration](https://www.youtube.com/watch?v=i29bAx6W1uI)
- [36C3 - The Great Escape of ESXi](https://www.youtube.com/watch?v=XHDwsvywX50)
- [BlueHat v18 || Straight outta VMware](https://www.youtube.com/watch?v=o36N5wi_ZFs)

**Articles / papers**

- [Windows Sandbox Attack Surface Analysis](https://googleprojectzero.blogspot.com/2015/11/windows-sandbox-attack-surface-analysis.html)

## Anything that contains win32k.sys

**Talks / video recordings**

- [BlackHat 2011 - Kernel Attacks Through User-Mode Callbacks](https://www.youtube.com/watch?v=EkGDSqpfzgg)

**Articles / papers**

- [One Bit To Rule A System: Analyzing CVE-2016-7255 Exploit In The Wild](https://blog.trendmicro.com/trendlabs-security-intelligence/one-bit-rule-system-analyzing-cve-2016-7255-exploit-wild/)
- [Reverse Engineering the Win32k Type Isolation Mitigation](https://blog.quarkslab.com/reverse-engineering-the-win32k-type-isolation-mitigation.html)
- [A new exploit for zero-day vulnerability CVE-2018-8589](https://securelist.com/a-new-exploit-for-zero-day-vulnerability-cve-2018-8589/88845/)
- [Detecting and mitigating elevation-of-privilege exploit for CVE-2017-0005](https://www.microsoft.com/security/blog/2017/03/27/detecting-and-mitigating-elevation-of-privilege-exploit-for-cve-2017-0005/)
- [Exploring CVE-2015-1701 — A Win32k Elevation of Privilege Vulnerability Used in Targeted Attacks
](https://blog.trendmicro.com/trendlabs-security-intelligence/exploring-cve-2015-1701-a-win32k-elevation-of-privilege-vulnerability-used-in-targeted-attacks/)
- [Exploiting the win32k!xxxEnableWndSBArrows use-after-free](https://www.nccgroup.trust/globalassets/our-research/uk/blog-post/2015-07-07_-_exploiting_cve_2015_0057.pdf)
- [New zero-day vulnerability CVE-2019-0859 in win32k.sys](https://securelist.com/new-win32k-zero-day-cve-2019-0859/90435/)
- [Windows zero‑day CVE‑2019‑1132 exploited in targeted attacks](https://www.welivesecurity.com/2019/07/10/windows-zero-day-cve-2019-1132-exploit/)
- [Windows Kernel Local Denial-of-Service #1: win32k!NtUserThunkedMenuItemInfo](https://j00ru.vexillium.org/2017/02/windows-kernel-local-denial-of-service-1/)
- [Windows Kernel Local Denial-of-Service #2: win32k!NtDCompositionBeginFrame](https://j00ru.vexillium.org/2017/02/windows-kernel-local-denial-of-service-2/)
- [Windows Kernel Local Denial-of-Service #4: nt!NtAccessCheck and family](https://j00ru.vexillium.org/2017/04/windows-kernel-local-denial-of-service-4/)
- [Windows Kernel Local Denial-of-Service #5: win32k!NtGdiGetDIBitsInternal](https://j00ru.vexillium.org/2017/04/windows-kernel-local-denial-of-service-5/)
- [Windows win32k.sys menus and some “close, but no cigar” bugs](https://j00ru.vexillium.org/2013/09/windows-win32k-sys-menus-and-some-close-but-no-cigar-bugs/)

## Windows kernel mitigations

**Talks / video recordings**

- [BlueHat v18 || Hardening hyper-v through offensive security research](https://www.youtube.com/watch?v=8RCH0vFxWT4)
- [BYPASS CONTROL FLOW GUARD COMPREHENSIVELY - this is cfg not kCFG](https://www.blackhat.com/docs/us-15/materials/us-15-Zhang-Bypass-Control-Flow-Guard-Comprehensively-wp.pdf)
- [BlueHat v18 || Mitigation Bypass: The Past, Present, and Future](https://www.youtube.com/watch?v=WsoFmN3oDw8)
- [Windows Offender Reverse Engineering Windows Defender's Antivirus Emulator](https://www.youtube.com/watch?v=LvW68czaEGs)
- [Windows 10 Mitigation Improvements (really good talk)](https://www.youtube.com/watch?v=gCu2GQd0GSE)
- [Overview of Windows 10 Requirements for TPM, HVCI and SecureBoot](https://www.youtube.com/watch?v=v149T7p4XLA)
- [Examining the Guardians of Windows 10 Security - Chuanda Ding](https://www.youtube.com/watch?v=a0AB76YNMlQ)
- [Analysis of the Attack Surface of Windows 10 Virtualization-Based Security](https://www.youtube.com/watch?v=_646Gmr_uo0)
- [A Dive in to Hyper-V Architecture & Vulnerabilities](https://www.youtube.com/watch?v=2bK_rC81_Eo)
- [the last kaslr leak](https://www.youtube.com/watch?v=PTnuwchEci0)
- [BlueHat v18 || A mitigation for kernel toctou vulnerabilities](https://www.youtube.com/watch?v=YGkhK55jitE)
- [REcon 2013 - I got 99 problems but a kernel pointer ain't one ](https://www.youtube.com/watch?v=5HbmpPBKVFg)
- [SMEP: What is it, and how to beat it on Windows](https://j00ru.vexillium.org/2011/06/smep-what-is-it-and-how-to-beat-it-on-windows/)

**Articles / papers**

- [Hardening Windows 10 with zero-day exploit mitigations](https://www.microsoft.com/security/blog/2017/01/13/hardening-windows-10-with-zero-day-exploit-mitigations/)
- [SMEP: What is it, and how to beat it on Windows](https://j00ru.vexillium.org/2011/06/smep-what-is-it-and-how-to-beat-it-on-windows/)
- [TAKING WINDOWS 10 KERNEL EXPLOITATION TO THE NEXT LEVEL](https://www.blackhat.com/docs/us-17/wednesday/us-17-Schenk-Taking-Windows-10-Kernel-Exploitation-To-The-Next-Level%E2%80%93Leveraging-Write-What-Where-Vulnerabilities-In-Creators-Update-wp.pdf)
- (Devlopment of a new Windows 10 KASLR bypass - in one winDBG command)[https://www.offensive-security.com/vulndev/development-of-a-new-windows-10-kaslr-bypass-in-one-windbg-command/]

## Windows kernel exploitation

**Talks / video recordings**

- [REcon 2015 - This Time Font hunt you down in 4 bytes](https://www.youtube.com/watch?v=uvy5BF1Nlio)
- [Exploiting a Windows 10 PagedPool off-by-one overflow (WCTF 2018)](https://j00ru.vexillium.org/2018/07/exploiting-a-windows-10-pagedpool-off-by-one/)
- [Windows kernel exploitation techniques - Adrien Garin - LSE Week 2016](https://www.youtube.com/watch?v=f8hTwFpRphU)
- [Hackingz Ze Komputerz - Exploiting CAPCOM.SYS - Part 1](https://www.youtube.com/watch?v=pJZjWXxUEl4)
- [Hackingz Ze Komputerz - Exploiting CAPCOM.SYS - Part 2](https://www.youtube.com/watch?v=UGWqq5kTiso)
- [The 3 Way06 Practical Windows Kernel Exploitation](https://www.youtube.com/watch?v=hUCmV7uT29I)
- [Reverse Engineering and Bug Hunting on KMDF Drivers](https://www.youtube.com/watch?v=puNkbSTQtXY)
- [Binary Exploit Mitigation and Bypass History - not just kernel ](https://vimeo.com/379935124) 
- [Morten Schenk - Taking Windows 10 Kernel Exploitation to the next level](https://www.youtube.com/watch?v=Gu_5kkErQ6Y)
- [REcon 2015 - Reverse Engineering Windows AFD.sys](https://www.youtube.com/watch?v=2sPNUpfTJ5A)
- [Windows Kernel Graphics Driver Attack Surface](https://www.youtube.com/watch?v=uzPTyXQ1Oys)
- [Understanding TOCTTOU in the Windows Kernel Font Scaler Engine](https://www.youtube.com/watch?v=61K3kqTRbzU)
- [Black Hat USA 2013 - Smashing The Font Scaler Engine in Windows Kernel](https://www.youtube.com/watch?v=efgoislKd8Q)

**Articles / papers**

- [Windows Drivers are True’ly Tricky](https://googleprojectzero.blogspot.com/2015/10/windows-drivers-are-truely-tricky.html)
- [Taking apart a double zero-day sample discovered in joint hunt with ESET](https://www.microsoft.com/security/blog/2018/07/02/taking-apart-a-double-zero-day-sample-discovered-in-joint-hunt-with-eset/)
- [Sharks in the Pool :: Mixed Object Exploitation in the Windows Kernel Pool](https://srcincite.io/blog/2017/09/06/sharks-in-the-pool-mixed-object-exploitation-in-the-windows-kernel-pool.html)
- [Kernel Pool Overflow Exploitation in Real World: Windows 10](https://www.gatewatcher.com/en/news/blog/kernel-pool-overflow-exploitation-in-real-world-windows-10)
- [Kernel Pool Overflow Exploitation in Real World - Windows 7](https://www.gatewatcher.com/en/news/blog/kernel-pool-overflow-exploitation-in-real-world-windows-7)
- [Kernel Pool Exploitation on Windows 7](https://www.exploit-db.com/docs/english/16032-kernel-pool-exploitation-on-windows-7.pdf)
- [Easy local Windows Kernel exploitation](https://media.blackhat.com/bh-us-12/Briefings/Cerrudo/BH_US_12_Cerrudo_Windows_Kernel_WP.pdf)
- [Exploiting CVE-2014-4113](https://labs.f-secure.com/assets/BlogFiles/mwri-lab-exploiting-cve-2014-4113.pdf)
- [Pwn2Own 2014 - AFD.sys Dangling Pointer Vulnerability](https://www.siberas.de/papers/Pwn2Own_2014_AFD.sys_privilege_escalation.pdf)
- [Symantec Endpoint protection 0day](https://www.offensive-security.com/vulndev/symantec-endpoint-protection-0day/)

## Windows kernel GDI exploitation

**Talks / video recordings**

- [Abusing GDI for ring0 exploit primitives Evolution](https://www.youtube.com/watch?v=ruuVkTuNUSc)
- [Demystifying Windows Kernel Exploitation by Abusing GDI Objects](https://www.youtube.com/watch?v=2chDv_wTymc)
- [CommSec D1 - The Life & Death of Kernel Object Abuse](https://www.youtube.com/watch?v=_u7d9kLdi0c)
- [Kernel Object Abuse by Type Isolation](https://www.youtube.com/watch?v=kOV-Y9HcJWM)

**Articles / papers**

- [Zero-day exploit (CVE-2018-8453) used in targeted attacks](https://securelist.com/cve-2018-8453-used-in-targeted-attacks/88151/)
- [The zero-day exploits of Operation WizardOpium](https://securelist.com/the-zero-day-exploits-of-operation-wizardopium/97086/)
- [Windows 0-day exploit CVE-2019-1458 used in Operation WizardOpium](https://securelist.com/windows-0-day-exploit-cve-2019-1458-used-in-operation-wizardopium/95432/)
- [Abusing GDI Objects for ring0 Primitives Revolution](https://sensepost.com/blog/2017/abusing-gdi-objects-for-ring0-primitives-revolution/)
- [A Tale Of Bitmaps: Leaking GDI Objects Post Windows 10 Anniversary Edition](https://labs.f-secure.com/archive/a-tale-of-bitmaps/)

## Windows kernel driver development

**Talks / video recordings**

- [Windows Kernel Programming - 14 part playlist](https://youtu.be/XUlbYRFFYf0)
- [Windows Driver Development - 19 part playlist](https://youtu.be/T5VtaP-wtkk)
- [Developing Kernel Drivers with Modern C++ - Pavel Yosifovich](https://www.youtube.com/watch?v=AsSMKL5vaXw)

## Windows internals

**Talks / video recordings**

- [Windows Internals](https://www.youtube.com/watch?v=vz15OqiYYXo)
- [Windows 10 Segment Heap Internals](https://www.youtube.com/watch?v=hetZx78SQ_A)
- [Windows Kernel Vulnerability Research and Exploitation - Gilad Bakas](https://www.youtube.com/watch?v=aRZ5Wi-NWXs)
- [NIC 5th Anniversary - Windows 10 internals](https://youtu.be/ffYiIUOUAUs)
- [Black Hat USA 2012 - Windows 8 Heap Intervals](https://www.youtube.com/watch?v=XxlzK0CLFN0)

## Fuzzing

**Talks / video recordings**

- [Windows Kernel Vulnerability Research and Exploitation](https://www.youtube.com/watch?v=aRZ5Wi-NWXs)
- [Bugs on the Windshield: Fuzzing the Windows Kernel](https://www.youtube.com/watch?v=-BkjkimINC8)
- [Windows Kernel Fuzzing for Intermediate Learners ](https://www.youtube.com/watch?v=wnNyPcerjJo)
- [Windows Kernel Fuzzing For Beginners - Ben Nagy](https://www.youtube.com/watch?v=FY-33TUKlqY)
- [Disobey 2018 - Building Windows Kernel fuzzer ](https://www.youtube.com/watch?v=mpXQvto4Vy4)
- [For The Win: The Art Of The Windows Kernel Fuzzing ](https://www.youtube.com/watch?v=9FPuKfwucsw)
- [RECON 2019 - Vectorized Emulation Putting it all together](https://www.youtube.com/watch?v=x4LPhwbTs9E)

**Articles / papers**

- [A year of Windows kernel font fuzzing #1: the results](https://googleprojectzero.blogspot.com/2016/06/a-year-of-windows-kernel-font-fuzzing-1_27.html)
- [A year of Windows kernel font fuzzing #2: the techniques](https://googleprojectzero.blogspot.com/2016/07/a-year-of-windows-kernel-font-fuzzing-2.html)

## Favorite books of mine

- Windows Internals, Part 1 (Pavel Yosifovich, and some others)
- Windows 10 System Programming, Part 1 (Pavel Yosifovich)
- Windows 10 System Programming, Part 2 (Pavel Yosifovich)
- Windows Kernel Programming (Pavel Yosifovich)
- Rootkits: Subverting the Windows Kernel 
- The Rootkit Arsenal
- Intel® 64 and IA-32 Architectures Software Developer Manuals
