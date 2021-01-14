# SerenityEVOS

A (work-in-progress) modification of Andreas Kling's SerenityOS, with the aim of building a modern-looking operating system based on Serenity's Kernel.

## About

SerenityEVOS, short for Serenity EVolved OS is a modification of Serenity OS with modern design in mind. Unlike the original, which focuses on bringing back the '90-ish look of Unix-like OSes, EVolved aims to shoot the OS in the future, with a reworked GUI and user interaction logic.

## Kernel features (from the original repo)

* x86 (32-bit) kernel with pre-emptive multi-threading
* Hardware protections (SMEP, SMAP, UMIP, NX, WP, TSD, ...)
* IPv4 stack with ARP, TCP, UDP and ICMP protocols
* ext2 filesystem
* POSIX signals
* Purgeable memory
* /proc filesystem
* Pseudoterminals (with /dev/pts filesystem)
* Filesystem notifications
* CPU and memory profiling
* SoundBlaster 16 driver
* VMWare/QEMU mouse integration

## System services (from the original repo)

* Launch/session daemon (SystemServer)
* Compositing window server (WindowServer)
* Text console manager (TTYServer)
* DNS client (LookupServer)
* Network protocols server (ProtocolServer)
* Software-mixing sound daemon (AudioServer)
* Desktop notifications (NotificationServer)
* HTTP server (WebServer)
* Telnet server (TelnetServer)
* DHCP client (DHCPClient)

## Libraries (from the original repo)

* C++ templates and containers (AK)
* Event loop and utilities (LibCore)
* 2D graphics library (LibGfx)
* GUI toolkit (LibGUI)
* Cross-process communication library (LibIPC)
* HTML/CSS engine (LibWeb)
* JavaScript engine (LibJS)
* Markdown (LibMarkdown)
* Audio (LibAudio)
* PCI database (LibPCIDB)
* Terminal emulation (LibVT)
* Out-of-process network protocol I/O (LibProtocol)
* Mathematical functions (LibM)
* ELF file handling (LibELF)
* POSIX threading (LibPthread)
* Higher-level threading (LibThread)
* Transport Layer Security (LibTLS)
* HTTP and HTTPS (LibHTTP)

## Userland features (from the original repo)

* Unix-like libc and userland
* Shell with pipes and I/O redirection
* On-line help system (both terminal and GUI variants)
* Web browser (Browser)
* C++ IDE (HackStudio)
* IRC client
* Desktop synthesizer (Piano)
* Various desktop apps & games
* Color themes

## How do I read the documentation?

Man pages are browsable outside of SerenityOS under [Base/usr/share/man](https://github.com/SerenityOS/serenity/tree/master/Base/usr/share/man).

When running SerenityOS you can use `man` for the terminal interface, or `help` for the GUI interface.

## How do I build and run this?

See the [SerenityOS build instructions](https://github.com/SerenityOS/serenity/blob/master/Documentation/BuildInstructions.md)

## Original Author

* **Andreas Kling** - [awesomekling](https://twitter.com/awesomekling)

## Contributors for the base version

* **Robin Burchell** - [rburchell](https://github.com/rburchell)
* **Conrad Pankoff** - [deoxxa](https://github.com/deoxxa)
* **Sergey Bugaev** - [bugaevc](https://github.com/bugaevc)
* **Liav A** - [supercomputer7](https://github.com/supercomputer7)
* **Linus Groh** - [linusg](https://github.com/linusg)
* **Ali Mohammad Pur** - [alimpfard](https://github.com/alimpfard)
* **Shannon Booth** - [shannonbooth](https://github.com/shannonbooth)
* **Hüseyin ASLITÜRK** - [asliturk](https://github.com/asliturk)
* **Matthew Olsson** - [mattco98](https://github.com/mattco98)
* **Nico Weber** - [nico](https://github.com/nico)
* **Brian Gianforcaro** - [bgianfo](https://github.com/bgianfo)
* **Ben Wiederhake** - [BenWiederhake](https://github.com/BenWiederhake)
* **Tom** - [tomuta](https://github.com/tomuta)
* **Paul Scharnofske** - [asynts](https://github.com/asynts)
* **Itamar Shenhar** - [itamar8910](https://github.com/itamar8910)
* **Luke Wilde** - [Lubrsi](https://github.com/Lubrsi)
* **Brendan Coles** - [bcoles](https://github.com/bcoles)
* **Andrew Kaster** - [ADKaster](https://github.com/ADKaster)

(And many more!) The people listed above have landed more than 100 commits in the project. :^)

## License

SerenityEVOS, just like it's base SerenityOS is licensed under a 2-clause BSD license.
