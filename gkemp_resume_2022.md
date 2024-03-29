 # Gregory Kemp Resume
A design verification generalist with management success.
* Over twenty-five years of industry experience in design verification of x86 and Power® processors, 
chipsets, software infrastructure and EDA tools. 
* Demonstrated ability to lead projects and teams to achieve challenging goals on schedule. 
* Ability to invent new methodologies and manage processes to address problems, cut development costs, 
and reduce engineering effort.

## Skills and Expertise
* CPU and SoC design and verification.
* Emulation-based verification.
* Job automation with Python, shell scripts, and Perl.
* Test plan development and execution.
* Coverage-driven directed-random testing.
* UVM test bench and environment development with SystemVerilog and Specman/e.
* Formal verification with JasperGold.

## Professional Experience

### Hardware Development Engineer, IBM, Austin, Texas (Oct. 2018 - present)
* Used proprietary AWAN emulators to verify Power and Z server hardware on several projects. Also verified the exerciser software used to validate hardware in the lab. We found roughly equal numbers of bugs in both hardware and software.
* Triaged regression fails, debugging down to root cause, whether a software or hardware defect. Added triage automation in Python to automatically investigate hung tests. Added assertions in proprietary Bugspray language to triage complex scenarios. Wrote trace tools in Python and C++ to report instruction traces, memory fabric transactions, and traffic to the IO subsystem.
* Closed a content gap by focusing on soft error recovery features, performance monitoring features, and instruction trace features. Worked with exerciser teams to close content gaps.
* Added test content to exercise specific functionality not hit by random testing, primarily in assembly.

### Design Verification Consultant, Correct Designs, Austin, Texas (June 2016 - Oct. 2018)
* Working under contract on automotive SoC for autonomous vehicles:
    * Developed testbench infrastructure in C to enable simulation test content to run unmodified on Synopsys ZeBu emulator. Wrote test content to qualify embedded software on emulator.
* Working under contract to verify a high-speed networking IP block. 
    * Developed UVM test bench in SystemVerilog to exercise transmission pipeline. Integrated an existing C++ reference model to scoreboard unit output.
    * Wrote extensive assertions to catch bugs before data mismatch at outputs.
* Working under contract with a major medical device manufacturer verifying an implantable device.
    * Developed UVM test bench in Specman/e to verify an encryption engine. Qualified a reference model against standard. Added sequences to exercise unit behavior and coverage points to close the effort.
    * Applied UVM in Specman/e to verify a DSP engine. Added monitors to collect unit inputs and outputs. Developed models to predict unit output and correlate lossy compression output.

### Senior Staff Engineer, Atom® CPU Development Group, Intel, Austin, Texas (Jan. 2010 - May 2016)
* Led teams (8 to 15 engineers) to complete design verification on arithmetic execution units and the memory subsystem across 5 generations of Atom® CPUs. Drove acceptance, test planning, test bench development, and test writing for assigned areas. Arithmetic units had zero escapes to silicon. No coherency bugs escaped to lab.
* Served as team's leading Specman expert, guiding test bench development and architecture. Led team's effort to migrate towards UVM and SystemVerilog test benches.
* Developed FV environment able to compile entire Atom® CPU core in JasperGold engine and prove assertions embedded in the design. Developed regression automation to detect new counterexamples.
* Collaborated to develop functional coverage methodology using SV coverage constructs that greatly reduced the effort required close the DV effort, saving $2.5M in engineer development costs. 

### Staff Engineer, Atom® and SoC Development Group, Intel, Austin, Texas (Jan. 2005 to Jan. 2010)
* Medfield Power and Mixed-Signal (MSV) Team Leader: (Sept. 2008 - Jan. 2010) 
    * Led a 14-person team across two concurrent projects when new SoC project needed power-management validation while base project was still in active development. Managed staffing and schedule issues.
    * Developed new MSV methodology to address Lincroft lab escapes, developed test plan and contributed significant test content (primarily PLLs). Coordinated MSV activities at several U.S. and India sites. 

### Earlier Career Highlights:
* Led 11-member team, split between US and Malaysia, to successfully execute an aggressive project schedule of Lincroft Atom® SoC chip. Invented methodology to validate new system-level power-management features. 
* Led a team to verify uncore functionality of first Atom® microprocessor. Delivered functional uncore logic and DFT features ahead of schedule. No significant escapes to silicon; no coherency bugs escaped.
* As Tejas Project team member, assigned area was functional ahead of planned tape-out. Designed entire scoreboarding infrastructure for out-of-order cluster from scratch using Specman.
* Multiple design verification and team-lead roles on Pentium® II and Pentium® III projects, using random testing and functional coverage to prove correctness and find bugs.

## Education and Publications
* Master of Science in Computer Engineering
    * Clemson University, Computer Systems Architecture
* Bachelor of Science in Electrical Engineering
    * Rose-Hulman Institute of Technology, Digital Systems Design
* "PEWs: A Decentralized Dynamic Scheduler for Instruction-Level Parallelism," with Dr. Manoj Franklin. Proceedings of the International Conference on Parallel Processing (ICPP), Vol. I, pp. 239-246, 1996. 

Honors and Awards, Intel Corporation
* Division Recognition Award, for outstanding leadership enabling a timely Medfield A0 tape-out.
* Division Recognition Award, for my part in enabling Lincroft's power management features.
* Division Recognition Award, for recoding Silverthorne's chipset behavioral model into synthesizable Verilog, enabling platform emulation.