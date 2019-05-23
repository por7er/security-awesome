# CPU-vulnerability-collections

# 1.papers

<table>
<thead>
<tr>
	<th>paper</th>
	<th>blog</th>
	<th>POC</th>
</tr>
</thead>
<tbody>
<tr>
	<td>
		Meltdown: Reading Kernel Memory from User Space(https://meltdownattack.com/meltdown.pdf)<br/>
		Spectre Attacks: Exploiting Speculative Execution(https://spectreattack.com/spectre.pdf)<br/>(Spectre v1&amp;Spectre v2)</td>
	<td>
		Reading privileged memory with a side-channel(https://googleprojectzero.blogspot.com/2018/01/reading-privileged-memory-with-side.html)<br/>
		性能VS安全？CPU芯片漏洞攻击实战(1) - 破解macOS KASLR篇(https://paper.seebug.org/497/)<br/>
		性能VS安全？CPU芯片漏洞攻击实战(2) - Meltdown获取Linux内核数据(https://paper.seebug.org/499/)<br/>
		Into the Implementation of Spectre(https://www.fortinet.com/blog/threat-research/into-the-implementation-of-spectre.html)</td>
	<td>
		https://github.com/paboldin/meltdown-exploit<br/>
		https://github.com/Eugnis/spectre-attack</td>
</tr>
<tr>
	<td>
		Speculative Buffer Overflows: Attacks and Defenses(https://arxiv.org/pdf/1807.03757.pdf)<br/>
		(Spectre v1.1&amp;Spectre v1.2)
	</td>
	<td></td>
	<td></td>
</tr>
<tr>
	<td></td>
	<td>
		https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-3640<br/>
		(Spectre v3a)
	</td>
	<td></td>
</tr>
<tr>
	<td></td>
	<td>
		Issue 1528: speculative execution, variant 4: speculative store bypass(https://bugs.chromium.org/p/project-zero/issues/detail?id=1528)<br/> 
		Analysis and mitigation of speculative store bypass (CVE-2018-3639)(https://blogs.technet.microsoft.com/srd/2018/05/21/analysis-and-mitigation-of-speculative-store-bypass-cve-2018-3639/)<br/>
		(Spectre v4)
	</td>
	<td>provided in the blog</td>
</tr>
<tr>
	<td>Port Contention for Fun and Profit(https://eprint.iacr.org/2018/1060.pdf)</td>
	<td></td>
	<td>https://github.com/bbbrumley/portsmash</td>
</tr>
<tr>
	<td>
		NetSpectre: Read Arbitrary Memory over Network(https://arxiv.org/pdf/1807.10535.pdf)<br/>
		NetSpectre: A Truly Remote Spectre Variant(https://i.blackhat.com/asia-19/Thu-March-28/bh-asia-Schwarz-NetSpectre-A-Truly-Remote-Spectre-Variant.pdf)
	</td>
	<td></td>
	<td></td>
</tr>
<tr>
	<td>ret2spec: Speculative Execution Using Return Stack Buffers(https://arxiv.org/pdf/1807.10364.pdf)</td>
	<td></td>
	<td></td>
</tr>
<tr>
	<td>Spectre Returns! Speculation Attacks using the Return Stack Buffer(https://arxiv.org/pdf/1807.07940.pdf)</td>
	<td></td>
	<td></td>
</tr>
<tr>
	<td>LazyFP: Leaking FPU Register State using Microarchitectural Side-Channels(https://arxiv.org/pdf/1806.07480.pdf)</td>
	<td>Intel LazyFP vulnerability: Exploiting lazy FPU state switching(https://blog.cyberus-technology.de/posts/2018-06-06-intel-lazyfp-vulnerability.html)</td>
	<td></td>
</tr>
<tr>
	<td>BranchScope: A New Side-Channel Attack on Directional Branch Predictor(http://www.cs.ucr.edu/~nael/pubs/asplos18.pdf)</td>
	<td></td>
	<td></td>
</tr>
<tr>
	<td>SgxPectre Attacks: Stealing Intel Secrets from SGX Enclaves via Speculative Execution(https://arxiv.org/pdf/1802.09085.pdf)</td>
	<td></td>
	<td>https://github.com/osusecLab/SgxPectre</td>
</tr>
<tr>
	<td>ExSpectre: Hiding Malware in Speculative Execution(https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_02B-5_Wampler_paper.pdf)</td>
	<td></td>
	<td></td>
</tr>
<tr>
	<td>Translation Leak-aside Buffer: Defeating Cache Side-channel Protections with TLB Attacks(https://www.vusec.net/wp-content/uploads/2018/07/tlbleed-author-preprint.pdf)</td>
	<td></td>
	<td></td>
</tr>
<tr>
	<td>Spectre is here to stay: An analysis of side-channels and speculative execution(https://arxiv.org/pdf/1902.05178.pdf)</td>
	<td></td>
	<td></td>
</tr>
<tr>
	<td>MeltdownPrime and SpectrePrime: Automatically-Synthesized Attacks Exploiting Invalidation-Based Coherence Protocols(https://arxiv.org/pdf/1802.03802.pdf)</td>
	<td></td>
	<td>provided in the paper</td>
</tr>
<tr>
	<td>A Systematic Evaluation of Transient Execution Attacks and Defenses(https://arxiv.org/pdf/1811.05441.pdf)</td>
	<td></td>
	<td></td>
</tr>
<tr>
	<td></td>
	<td>System Management Mode Speculative Execution Attacks(https://blog.eclypsium.com/2018/05/17/system-management-mode-speculative-execution-attacks/)</td>
	<td></td>
</tr>
<tr>
	<td>
		FORESHADOW: Extracting the Keys to the Intel SGX Kingdom with Transient Out-of-Order Execution(https://foreshadowattack.eu/foreshadow.pdf)<br/>
		Foreshadow-NG: Breaking the Virtual Memory Abstraction with Transient Out-of-Order Execution(https://foreshadowattack.eu/foreshadow-NG.pdf)
	</td>
	<td>Analysis and mitigation of L1 Terminal Fault (L1TF)(https://blogs.technet.microsoft.com/srd/2018/08/14/analysis-and-mitigation-of-l1-terminal-fault-l1tf/)</td>
	<td>https://github.com/gregvish/l1tf-poc</td>
</tr>
<tr>
	<td>SPOILER: Speculative Load Hazards Boost Rowhammer and Cache Attacks(https://arxiv.org/pdf/1903.00446.pdf)</td>
	<td></td>
	<td></td>
</tr>
<tr>
	<td>SMoTherSpectre: exploiting speculative execution through port contention(https://arxiv.org/pdf/1903.01843.pdf)</td>
	<td>SMoTherSpectre: transient execution attacks through port contention(http://nebelwelt.net/blog/20190306-SMoTherSpectre.html)</td>
	<td>https://github.com/HexHive/SMoTherSpectre</td>
</tr>
<tr>
	<td>ZombieLoad: Cross-Privilege-Boundary Data Sampling(https://zombieloadattack.com/zombieload.pdf)</td>
	<td>ZombieLoad: Cross Privilege-Boundary Data Leakage(https://www.cyberus-technology.de/posts/2019-05-14-zombieload.html)</td>
	<td>https://github.com/IAIK/ZombieLoad</td>
</tr>	
<tr>
	<td>RIDL: Rogue In-Flight Data Load(https://mdsattacks.com/files/ridl.pdf)</td>
	<td></td>
	<td></td>
</tr>	
<tr>
	<td>Fallout: Reading Kernel Writes From User Space(https://mdsattacks.com/files/fallout.pdf)</td>
	<td></td>
	<td></td>
</tr>	
<tr>
	<td>Store-to-Leak Forwarding: Leaking Data on Meltdown-resistant CPUs(https://cpu.fail/store_to_leak_forwarding.pdf)</td>
	<td></td>
	<td></td>
</tr>	
</tbody>
</table>

# 2.check tool

https://github.com/vusec/ridl

https://github.com/ionescu007/SpecuCheck

https://github.com/speed47/spectre-meltdown-checker

# 3.patch analysis

## 3.1.KPTI(Kernel Page Table Isolation)

KPTI补丁分析(https://mp.weixin.qq.com/s/kQaZnqjbdxz6HS8ljLp3zw)

## 3.2.KVAS(Kernel Virtual Address Shadow)

简单看了一下微软新出的内核页表隔离补丁(https://bbs.pediy.com/thread-223805.htm)

KVA Shadow: Mitigating Meltdown on Windows(https://blogs.technet.microsoft.com/srd/2018/03/23/kva-shadow-mitigating-meltdown-on-windows/)

A Deep Dive Analysis of Microsoft’s Kernel Virtual Address Shadow Feature(https://www.fortinet.com/blog/threat-research/a-deep-dive-analysis-of-microsoft-s-kernel-virtual-address-shadow-feature.html)

## 3.3.Retpoline(return trampoline)

Retpoline: The Anti sectre type 2 mitigation in windows(https://www.youtube.com/watch?v=ZfxXjDQRpsU)

**pdf:https://www.slideshare.net/MSbluehat/bluehat-v18-retpoline-the-antispectre-type-2-mitigation-in-windows**

Retpoline: a software construct for preventing branch-target-injection(https://support.google.com/faqs/answer/7625886)

Mitigating Spectre variant 2 with Retpoline on Windows(https://techcommunity.microsoft.com/t5/Windows-Kernel-Internals/Mitigating-Spectre-variant-2-with-Retpoline-on-Windows/ba-p/295618)

## 3.4.others

Spectre mitigations in MSVC(https://blogs.msdn.microsoft.com/vcblog/2018/01/15/spectre-mitigations-in-msvc/)

Mitigating speculative execution side channel hardware vulnerabilities(https://blogs.technet.microsoft.com/srd/2018/03/15/mitigating-speculative-execution-side-channel-hardware-vulnerabilities/)

# 4.others

https://software.intel.com/security-software-guidance

Exploiting CVE-2018-1038 - Total Meltdown(https://blog.xpnsec.com/total-meltdown-cve-2018-1038/)

Issue 1711: Linux: eBPF Spectre v1 mitigation is insufficient(https://bugs.chromium.org/p/project-zero/issues/detail?id=1711)

(some notes about this by me:CVE-2018-3639/CVE-2019-7308—Spectre攻击linux内核ebpf的分析(https://xz.aliyun.com/t/4230))

Oh No! KPTI DefeatedUnauthorized Data Leakage is Still Possible(https://i.blackhat.com/asia-19/Fri-March-29/bh-asia-Cheng-Oh-No-KPTI-Defeated-Unauthorized-Data-Leakage-is-Still-Possible.pdf)

Detecting Attacks that Exploit Meltdown and Spectre with Performance Counters(https://blog.trendmicro.com/trendlabs-security-intelligence/detecting-attacks-that-exploit-meltdown-and-spectre-with-performance-counters/)
