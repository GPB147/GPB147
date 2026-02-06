```python
GPB147_RoadMap = 
{
	"0 Personal": 
		
		"""0 Funding proccess:

			0 Learning and making proofs = [2 Years]

			1 Hiring in remote small EU companies by crypto payment = [4 Years]

			2 Consulting = [4 Years]

			3 Making own company = [x Years]

		1 Important = [In my area repudation is more important than money]

		2 Requirements = [Time(2Y), Laptop, Internet, Focuse(Empty mind), Food]

		3 Reward = [Power(Social security, Freedome,...)]

		4 Who will I become:

			0 ID:

				0 Short = [Remote firmware / boot-level security researcher]

				1 Long = [Computer start, Trust(is, broke, proves by codes)]

			1 Benefits = [This area just going to evolve, Not full AI automated, Hiring guarantee(High demand and low supply), Remote, High power in society, Knowing and not programming, Earning money in %85-95 top of every jobs in world]

			2 Day routine:

				0 Long:

					0 Recive = [firmware image, device, boot log, or a research question like "Can this system be persistent below the OS?"]

					1 Analyze = [UEFI modules, boot phases, Secure Boot flow, trust boundaries]

					2 Reason = [Who is trusted here?, What happens if this is writable?, What executes before what?]

					3 Build small POCs = [a malicious DXE driver, a persistence mechanism, a boot-time hook]

					4 Explain = [writeups, reports, GitHub READMEs, sometimes internal company docs]

				1 Short = [Read, Modify, Test, Explain]]"""
		
	"1 Knowing" = 
	"""{
		0 Level 0:

			0 English
		
			1 Python:

				0 Books = [Automate the Boring Stuff with Python (2nd Edition)]

				1 Must to learn = [Write scripts without fear, Automate analysis, Read others’ Python]

				2 Don't learn = [Advanced Python internals, Data science, Web frameworks]

			2 Linux + Terminal: 

				0 Books = [Linux Command Line and Shell Scripting Bible (5th Edition) + Linux Basics for Hackers]

				1 Must to learn = [Bash, POSIX just for understanding, Live in terminal, Debug, script, build, flash, analyze]

				2 Don't learn = [PowerShell, zsh tricks, fish, fancy shells, Desktop Linux theory, Server administration depth, know Linux, filesystem theory, customize or beautify, treat directories as static, Learn hundreds of commands]

				3 Commands:

					0 Leanrn it = [inspect, trace, automate, build, debug]

					1 Ignore it = [customize, decorate, replace thinking]

		1 Level 1:

			0 C programming:

				0 Books = [The C Programming Language (2nd Edition)]

				1 Most to learn = [Pointers are natural, Read kernel & firmware C, Understand memory bugs]

				2 Don't learn = [Modern C++ depth, STL, Application‑level patterns]

			1 Computer Architecture & Memory:

				0 Books = [Computer Organization and Design MIPS Edition 6th]

				1 Must to learn = [Stack / heap / registers, Privilege levels, Boot trust chain]

				2 Don't learn = [Quantitative CPU optimization, HPC topics]

			2 Assembly(x86, ARM, x86_64):

				0 Books = [The Art of Assembly Language (2nd Edition)]

				1 Must to learn = [Read disassembly without fear, Translate C ↔ ASM, Understand calling conventions]

				2 Don't learn = [Writing large ASM programs, Micro‑optimizations]

		2 Level 2:

			0 Networking:

				0 Books = [Computer Networking: A Top-Down Approach (8th Edition)]

				1 Must to learn = [Understand packet flow, Understand packet flow, Recognize malicious traffic, Support reverse engineering & malware analysis]

				2 Tools = [Wireshark, Wireshark]

				3 Stop at = [Application layer (light), Application layer (light), Transport layer (TCP/UDP)]

				4 Don't learn = [Wireless deep dive, SDN, Advanced congestion control, Cloud networking, Network programming depth] 

			1 Operating System Internals(OS Internet):

				0 Books = [Windows Internals (7th Edition) + Operating Systems: Three Easy Pieces]

				1 Must to learn = [User vs kernel boundary, Drivers, Boot chain OS ↔ firmware]

				2 Don't learn = [Scheduler theory depth, Filesystem internals obsession]



			2 Reverse Engineering:

				0 Books = [Practical Reverse Engineering (latest) + Reversing: Secrets of RE (2nd Edition)]

				1 Most to learn = [Reconstruct logic from binaries, Track data flow not instructions, Handle stripped binaries]

				2 Tools = [Ghidra (primary), GDB / WinDbg (support)]

				3 Don't learn = [Crackme culture, Obfuscation contests, GUI‑heavy reversing]

		3 Level 3:

			0 Malware(user/kernel/rootkits):

				0 Books = [Practical Malware Analysis (latest) + Rootkits: Subverting the Windows Kernel (2nd Edition)]

				1 Must to learn = [Persistence, Stealth, Hooks, Trust abuse]

				2 Don't learn = [Web malware, Ransomware economics, Botnets]

			1 Firmware / BIOS / UEFI:

				0 Books = [The Firmware Handbook (Gary Koob) + UEFI Specification (official)]

				1 Must to learn = [Know what each component does, Know where trust is assumed, Know how it breaks, Know how to abuse it]

				2 Tools = [CHIPSEC, UEFITool, TianoCore, coreboot]

				3 Topics to MASTER = [Boot phases: SEC / PEI / DXE, SPI flash, PE/COFF, UEFI protocols, Secure Boot, Firmware persistence]

				3 Don't learn = [Full motherboard design, Electrical engineering, BIOS vendor marketing docs]

			2 Growth:

				0 Career = [The Cybersecurity Career Guide (2nd Edition)]

				1 Hiring in my area:

					0 They connect to you or you connect to they

					1 They care about proofs more than academic degree or certifications

					2 Eu is the best location for my area

					3 Crypto is the safest payment for me in small Eu companies

				2 Roadmap:

					0 Github:

						0 Writeups:

							0 Means = [Underestnding Concepts]

							1 Use = [README, Wiki, docs/Documentation]

						1 POC:

							0 Means = [Proof Of Concepts]

							1 Use = [Coding]

						2 Open source contributions:

							0 Means = [Doing Concepts]

							1 Focus = [Niche, quality not quantity]

							2 Steps = [Read, Build, Use, Observe friction, Small contribution, PR, Repeat]

							3 Projects:

								0 CHIPSEC = [Hardware/firmware security testing]
		
								1 EDK II(TianoCore) = [UEFI firmware]
	
								2 coreboot = [Open-source BIOS/firmware]
	
								3 UEFITool = [UEFI image analysis]
	
								4 Ghidra = [Reverse engineering plugins/scripts]

								5 Linux kernel tooling/doc = [Small bug fixes or docs]			
}"""	

	"2 Learning Process":

		"""0 2 Mounths = [English, Python] = [Done]
		
		1 1 Mounths = [English, Linux+Shell] = [Done]
		
		2 1 Mounth = [English, C] = [Working]
		
		3 1 Mounth = [English, Computer Architecture & Memory] = [...]
		
		4 1 Mounth = [English, Assembly(x86, ARM, x86_64)] = [...]

		5 1 Mounth = [English, Networking] = [...]

		6 1 Mounth = [English, Operating System Internals(OS Internet)] = [...]

		7 1 Mounth = [English, Reverse Engineering] = [...]

		8 1 Mounth = [English, Malware(user/kernel/rootkits)] = [...]

		9 4 Mounths = [English, Firmware / BIOS / UEFI] = [...]

		10 1 Year = [English, Growth] = [...]

		11 Roadmap = [Knowing trust concepts(Not programming), Done, Go to next step, Knowing deeper trust concepts, done, ...]"""

	"3 AI(ML) Helper":

		"""0 Roadmap:

			0 Ask = [Giving data]

			1 Customized = [Receive result] 

			2 Learn = [More data] 

			3 Confusing = [Error]

			4 Ask = [Giving data]

			5 Customized = [Receive result]

			6 Learn = [More data]

			7 Completed = [Completed healthy data] 

			8 Go to next step = [Next subject]"""
}
```


<a href="https://t.me/GPB147"><img width="50px" height="50px" align="center" src="https://github.com/sineme333/learn/blob/main/icons8-telegram-logo-64.png?raw=true" /></a>
<a href="https://t.me/Sineme333"><img width="50px" height="50px" align="center" src="https://github.com/sineme333/learn/blob/main/icons8-telegram-logo-64.png?raw=true" /></a>
<a href="https://www.linkedin.com/in/Sineme333"><img width="50px" height="50px" align="center" src="https://github.com/sineme333/learn/blob/main/icons8-linkedin-logo-64.png?raw=true" /></a>


