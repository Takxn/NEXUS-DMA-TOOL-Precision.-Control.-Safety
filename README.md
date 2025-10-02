# NEXUS-DMA-TOOL-Precision.-Control.-Safety
A modern Electron-based desktop tool with a Fluent-inspired dark UI, built for professional DMA workflows: driver management, DNA retrieval, firmware flashing, external device diagnostics, and performance analysis—done safely, transparently, and efficiently.



<img width="1200" height="800" alt="Screenshot 2025-10-02 154319" src="https://github.com/user-attachments/assets/a6bb2cd8-734e-402f-a725-35fb678d7a7f" />


Highlights
•  Clean, focused dark UI with Fluent-inspired visuals
•  End-to-end workflow from drivers to performance testing
•  Read-only Memory Diagnostics for safe inspections
•  External devices support (KMBox Net/B+, Arduino, Teensy, MAKCU)
•  Encrypted preferences (electron-store + keytar)
•  Installer bundles essential tools (PCIeLeech, OpenOCD, driver packages)
•  Multilingual (English/中文) with live switching
•  Clear startup banner indicating Leech vs. Mock mode

What you can do with it
•  Driver Installation
◦  Install CH347/RS232 drivers via PowerShell scripts with real-time progress
◦  Robust error handling and status updates
•  DNA ID Retrieval
◦  Retrieve device DNA ID (e.g., Xilinx/Squirrel) with optional auto-detection
◦  One-click copy to clipboard
•  Firmware Flashing
◦  Flash .bin, .hex, .bit, .mcs via OpenOCD
◦  Auto-detect or select chip type; detailed progress feedback
•  Performance & Speed Tests
◦  Read/Write/Benchmark modes
◦  Speed and duration output with consistent parsing
•  Memory Diagnostics (Read-only)
◦  Throughput, latency, and integrity hash (SHA-256) using PCIeLeech
◦  Safe Mock mode when PCIeLeech isn’t available
•  External Devices (KMBox Net/B+, Arduino, Teensy, MAKCU)
◦  Status checks (connected/driver/firmware)
◦  Device details (VID/PID, COM, FriendlyName, InstanceId)
◦  Safe self-tests (latency/jitter metrics)
◦  Firmware update stub with clear guidance
•  Settings & Comfort
◦  Theme switching (Dark/Light), language persisted
◦  Secure preference storage (encrypted with OS keychain)
◦  Discord Support button in the sidebar

Safety & Transparency
•  Read-only diagnostics: memory operations are inspection-only
•  Mode banner on startup: clearly shows whether using real PCIeLeech (Leech mode) or simulated results (Mock mode)
•  Encrypted configuration: preferences protected via keytar + electron-store
•  No process manipulation: designed for safe, professional workflows

User Experience
•  Intuitive sidebar navigation and clear sectioning
•  Live feedback (progress bars, result badges, structured logs)
•  Fluent-inspired aesthetics with high readability and contrast
•  Detailed device cards with key identifiers

Installer & Distribution
•  Windows installer (NSIS) with dark visual style
•  Bundles tools in extraResources (PCIeLeech, OpenOCD, driver packages)
•  Maximum compression, ready for code signing (optional)
•  Versioned and visible in-app (e.g., v1.0.3)

Who is it for?
•  Embedded/FPGA engineers
•  Hardware bring-up and diagnostics teams
•  Anyone needing reproducible DMA workflows and safe, traceable diagnostics

Modes
•  Leech mode: PCIeLeech detected—real, read-only DMA diagnostics
•  Mock mode: PCIeLeech not found—safe, realistic simulation for development and demos

Support
•  Join the support server from within the app via the Discord button
•  Link: <https://discord.gg/htkJRM9jFw>

