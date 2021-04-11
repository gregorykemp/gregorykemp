# Gregory Kemp Resume
A design verification generalist with management success.
* Over twenty years of industry experience in design verification of x86 and Power processors, chipsets, software infrastructure and EDA tools. 
* Demonstrated ability to lead projects and teams to achieve challenging goals on schedule. 
* Ability to invent new methodologies and manage process to address problems, cut development costs, and reduce engineer effort.

## Skills and Expertise
* UVM test bench and environment development with SystemVerilog.and Specman/e.
* CPU design and verification.
* Test plan development and execution.
* Coverage-driven directed-random testing.
* Formal verification with JasperGold.
* Emulation based verification.
* Job automation with Perl, shell scripts, and Python.

## Professional Experience
### Hardware Development Engineer, IBM, Austin, Texas (Oct. 2018 - present)
* Power 10 processor development:
    * Debug of floating-point and vector execution unit tests, on RTL, filing defects as needed.
    * Debug of emulator tests, covering all core functionality, filing defects as needed.
    * Verification of error injection, error detection, and error recovery functionality across whole core. Developed content to enable behaviors. Ran test content on emulation, and also enabled parallel work on RTL models. Worked with exerciser teams to adjust test content when necessary. 
    * Verification of on-die performance monitors. Automated job flow so test content could run on the emulator and self-check.
* Power 9 processor development:
    * Coverage analysis of OpenCAPI interface, identifying gaps in test content and model behavior.
    * Debug of regression failures, filing defects as needed.

### Design Verification Consultant, Correct Designs, Austin, Texas (June 2016 - Oct. 2018)
* Working under contract on automotive SoC for autonomous vehicles:
    * Developed testbench infrastructure in C to enable simulation test content to run unmodified on Synopsys ZeBu emulation platform.
    * Wrote test content to qualify embedded software on emulator.
* Working under contract to verify a high-speed networking IP block. 
    * Developed UVM test bench in System Verilog to exercise transmission pipeline. Integrated an existing C++ reference model to scoreboard unit output.
    * Wrote extensive assertions to catch bugs before data mismatch at outputs.
* Working under contract with a medical device manufacturer verifying an implantable device.
    * Developed UVM test bench in Specman/e to verify an encryption engine. Qualified a reference model against standard. Added sequences to exercise unit behavior and coverage points to close the effort.
    * Applied UVM in Specman/e to verify a DSP engine. Added monitors to collect unit inputs and outputs. Developed models to predict unit output and correlate lossy compression output.

### Senior Staff Engineer, Atom CPU Development Group, Intel, Austin, Texas (Jan. 2010 - May 2016)
* Led teams (8 to 15 engineers) to complete design verification on arithmetic execution units and the memory subsystem across 5 generations of Atom CPUs. Drove acceptance, test planning, test bench development, and test writing for assigned areas. Arithmetic units had zero escapes to silicon. No coherency bugs escaped to lab.
* Served as team's leading Specman expert, guiding test bench development and architecture. Led team's effort to migrate towards UVM and SystemVerilog test benches.
* Developed FV environment able to compile entire Atom CPU core in JasperGold engine and prove assertions embedded in the design.  Developed regression automation to detect new counterexamples.
* Collaborated to develop functional coverage methodology using SV coverage constructs that greatly reduced the effort required close the DV effort, saving $2.5M in engineer development costs. 

### Staff Engineer, Atom and SoC Development Group, Intel, Austin, Texas (Jan. 2005 to Jan. 2010)
* Medfield Power and Mixed-Signal (MSV) Team Leader: (Sept. 2008 - Jan. 2010) 
    * Led a 14-person team across two concurrent projects when new SoC project needed power-management validation while base project was still in active development. Managed staffing and schedule issues.
    * Developed new MSV methodology to address Lincroft lab escapes, developed test plan and contributed significant test content (primarily PLLs). Coordinated MSV activities at several U.S. and India sites. 
*  Lincroft Power and DFT Validation Team Leader: (Jan. 2007 - May 2009) 
    * Led 11-member team, split between US and Malaysia, to successfully execute an aggressive project schedule of new Atom SoC chip. Invented methodology to validate new system-level power-management features. 

### Earlier Career Highlights:
* Led a team to verify uncore functionality of first Atom microprocessor. Delivered functional uncore logic and DFT features ahead of schedule. No significant escapes to silicon; no coherency bugs escaped.
* As Tejas Project team member, assigned area was functional ahead of planned tape-out. Designed entire scoreboarding infrastructure for out-of-order cluster from scratch using Specman.
* Multiple design verification and team-lead roles on Pentium II and Pentium III projects, using random testing and functional coverage to prove correctness and find bugs.

## Education and Publications
* Master of Science in Computer Engineering
    * Clemson University, Computer Systems Architecture
* Bachelor of Science in Electrical Engineering
    * Rose-Hulman Institute of Technology, Digital Systems Design
* "PEWs: A Decentralized Dynamic Scheduler for Instruction-Level Parallelism," with Dr. Manoj Franklin. Proceedings of the International Conference on Parallel Processing (ICPP), Vol. I, pp. 239-246, 1996. 

## Honors and Awards, Intel Corporation
* Division Recognition Award, for outstanding leadership enabling a timely Medfield A0 tape-out.
* Division Recognition Award, for my part in enabling Lincroft's power management features.
* Division Recognition Award, for recoding Silverthorne's chipset behavioral model into synthesizable Verilog, enabling platform emulation.


