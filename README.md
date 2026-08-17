README — Odyssey Tool
======================

Version: 2.1
Build: Full — all features enabled

REQUIREMENTS
  - Windows 10/11 x64
  - Run as Administrator
  - For kernel features: load km_driver2.sys via kdmapper first

USAGE
  1. Load driver (optional, for kernel tabs): run launch.bat
  2. Double-click Odyssey.exe and allow UAC
  3. Overlay opens — use tabs at the top to navigate

TABS
  PROCESSES   View all running processes, search by name, kill any process
  DRIVERS     Enumerate all loaded kernel drivers with base address + size
  SECURITY    Malware scanner, miner killer, DNS monitor (live), host blocklist
  TOOLS       Junk cleaner, network booster, telemetry blocker, DNS changer
  DUMP        Read process memory and dump to file (requires driver)
  EXPLOITS    HWID cleaner — removes hardware traces from game and AC logs
  KCP         Ring-0 primitives: KASLR bypass, token privilege escalation, DSE probe
  KTERM       Embedded kernel command terminal — type /cmds to list all 145+ commands
  EDGE        Microsoft Edge Odyssey mod — custom NTP and branding

NOTES
  - Overlay is transparent and click-through when not focused
  - DNS Monitor: Security tab >> DNS MONITOR >> START — live cache, flags miner domains red
  - KTERM supports kernel debug, memory, process, driver, and registry commands
  - Kernel tabs (DUMP, KCP) show errors gracefully if driver is not loaded
