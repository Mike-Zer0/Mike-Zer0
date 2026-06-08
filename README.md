## 👋 Hi, I'm Mike-Zer0

**Cyber Security Grad | Linux Performance Alchemist | Metalhead ☕🤘**

I don't just use Linux; I **wrestle it into submission**. I'm building **Proton-Punch**, the first major Linux Performance Optimizer Suite designed to unify GPU/CPU overclocking, kernel parameter tuning, and real-time telemetry for gamers.

### 🔭 I’m currently working on...
- **Proton-Punch** 🥊: Proton Punch 🥊
The Ultimate All-in-One Linux Performance Hub
Proton Punch consolidates fragmented kernel, memory, and hardware tuning tools into a single, cohesive ecosystem. Built for gamers and power users, it unlocks your hardware's true potential without the terminal headache.

🏗️ Split-Agent Architecture
Maximum performance, zero security compromises. Proton Punch isolates high-privilege system tweaks from the user interface:

The Engine (Backend Daemon): A high-performance Rust/C++ daemon running with native root/polkit privileges to safely manage hardware registers, systemd, and the kernel.

The Control Panel (Frontend GUI): A sleek dashboard communicating via secure local sockets/D-Bus. Run it anywhere, completely sandboxed.

📦 Packages: Flatpak, AppImage | pacman (Arch), dnf (Fedora), apt (Ubuntu/Debian)

⚡ Key Features
🎮 Low-Latency & Memory Optimization
Dynamic Tuning: Automated kernel management via bpftune—no manual sysctl guesswork required.

Stutter Elimination: auto-cpufreq + Ananicy-CPP balance CPU scaling and process priorities on the fly.

RAM-Speed Profiles: Profile Sync Daemon (PSD) moves heavy app data to tmpfs to slash disk I/O.

Intelligent Swap: Automatically configures lightning-fast ZRAM pools using zstd or lz4.

🔌 Hardware Tuning & Overclocking Suite
GPU Control: Overclock AMD via sysfs (ppfeaturemask) and NVIDIA via native NVML bindings.

CPU Undervolting: Precision voltage offsets via AMD Curve Optimizer (ryzen_smu) and Intel MSR clamps.

RAM & Cooling: Verify XMP/EXPO ratings via dmidecode and draw custom fan curves mapped straight to hwmon.

🐧 Custom Kernel Manager
One-click installation and tracking for performance kernels like CachyOS and Linux-Zen. The backend automatically updates repository hooks and your bootloader (grub, systemd-boot).

🎬 Graphics Driver & Firmware Control Center
Skip the broken PPAs and terminal chaos. The engine automatically detects your hardware and delivers a flawless, automated graphics stack.

+------------------------------------------------------------+
| [⚡] PROTON PUNCH   |   [DRIVER & FIRMWARE]                |
+------------------------------------------------------------+
|  Detected Hardware: NVIDIA RTX 4070 / AMD Ryzen 7 7800X3D  |
|                                                            |
|  [🟢] NVIDIA Proprietary Driver                             |
|       Current: v580.126                                    |
|       [ Switch to Open-Kernel (DKMS) ] [ Toggle Beta Stream ]|
|                                                            |
|  [🟢] AMD Radeon / Mesa Stack                              |
|       Current: Mesa 26.0.5 (Vulkan 1.3)                    |
|       [ Install Bleeding-Edge Mesa-Git ]                   |
|                                                            |
|  [🟡] Video Acceleration (VA-API / NVDEC)                 |
|       Status: Incomplete hardware decoding codecs detected.|
|       [ Action: Auto-Fix Hardware Codecs ]                 |
+------------------------------------------------------------+
|  [ Action: Check System Firmware (fwupd) ]                  |
+------------------------------------------------------------+
🟢 NVIDIA Suite: Instantly toggle between Stable Production and Beta channels. Autoconfigures /etc/modprobe.d/ for open-source modules and low-latency sync.

🔴 AMD & Mesa Suite: Grab day-one gaming optimizations by linking to bleeding-edge Mesa-Git, and swap between RADV and AMDVLK Vulkan backends on the fly.

🎬 Auto-Fix Codecs: Scans via vainfo/clinfo and patches missing hardware acceleration dependencies (intel-media, nvidia-vaapi) to drop CPU overhead.

🔌 Unified Firmware: Deep fwupd integration to update your motherboard BIOS, SSD controllers, and gaming peripherals right from the dashboard.

### 👯 I’m looking to collaborate on...
- **Proton-Punch**: Specifically seeking **Rust/C++ devs** for kernel-level modules and **Flutter experts** for the UI.
- **Linux Gaming**: Anyone interested in pushing **Proton-GE** patches further for unsupported AAA titles.
- **Security Research**: Collaborative bug bounties and CVE analysis.

### 🤔 I’m looking for help with...
- **GUI Polish**: Making the Proton-Punch dashboard look as good as a **KDE** theme designed by a metal album cover artist.
- **Testing**: Users with diverse GPU architectures (NVIDIA/AMD/Intel) to stress-test the overclocking profiles. 
- **Documentation**: Helping translate technical kernel tweaks into user-friendly guides.

### 💬 Ask me about...
- **Linux Performance**: Squeezing every MHz out of your CPU/GPU. 
- **OSINT & Pentesting**: Python scripts, network forensics, and digital footprint analysis. 
- **Horror Movies**: From classic slashers to modern A24 psychological terror.
- **Coffee**: Dialing in the perfect espresso shot for late-night coding sessions.

### 📫 How to reach me...
- **GitHub**: [@Mike-Zer0](https://github.com/Mike-Zer0)
- **Email**: michaeljg0717@gmail.com


### 😄 Pronouns...
- He/Him | Root/Sudo | Metalhead/Coffee Addict

### ⚡ Fun facts...
- **Alacritty** is the only terminal emulator I trust; everything else is bloat. 
- I once overclocked a GPU so hard it rendered a game in *slow motion* before crashing (worth it for the benchmark).
- My code is 40% Coffee, 30% Metal music, 20% AI-generated "Vibe Code", and 10% actual typing.
- I believe **X11** is a horror movie that never ended, which is why I live on **Wayland**.
- Sales & Marketing pays the bills, but **Kernel Tweaking** pays the soul.   
