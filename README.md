Dynamic Kernel Tuning: Automates the adjustment of vm.swappiness and memory caches to prioritize real-time application throughput over background disk usage.
Telemetry-Driven Execution: Performs pre-launch hardware checks using raw thermal data from the /sys/ filesystem to ensure system health.
Security Scoping: Securely manages ptrace_scope logic to allow authorized memory interaction within sandboxed environments (Lutris/Flatpak).
Signal Trapping & Restoration: Utilizes Linux signal handlers (trap) to guarantee a "Self-Healing" return to the system baseline during ungraceful shutdowns or user interrupts.
