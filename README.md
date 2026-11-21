# GhostStrats Multi Tool
## GhostStrats Multi Tool — The Evolution of GS USB Runner

**Free Windows Desktop Cybersecurity, Privacy, Scripting, Intelligence, and Preparedness Tools**

**GhostStrats | Safety is an Illusion.**

---

## How It Started

GS Multi Tool is the evolution of **GS USB Runner**.

What originally started as a software-based HID scripting tool has grown into something much bigger.

In the beginning, GS USB Runner was designed around the idea of making software-based HID scripting more accessible. Over time, I continued developing it, adding new capabilities, utilities, learning resources, and custom tools until it evolved into an entire collection of applications.

Then GitHub suspended my account.

I could have let that setback discourage me, but instead, I decided to take everything I had learned and push the project further.

**Instead of being bitter, I chose to become better.**

Rather than simply rebuilding GS USB Runner the way it was, I decided to rethink the entire platform.

The result is **GhostStrats Multi Tool**, a dedicated Windows desktop application that brings together the tools, features, and capabilities I have been developing for the community.

This new version represents a major step forward.

Instead of requiring a USB flash drive, everything is organized inside a proper Windows application with a dedicated installer, desktop shortcuts, application management, an uninstaller, and an improved user interface.

Running the application directly from a computer's internal storage has also provided noticeable performance improvements compared with running the entire collection from a flash drive.

The software has been designed to feel more professional, remain easier to maintain, and provide a more consistent experience.

Although this new installation system may help reduce some of the issues associated with portable executables, no software can guarantee that antivirus products will never flag an unfamiliar application.

Most importantly, my original goal has not changed.

**I want to provide free, useful tools to the community.**

Whether you are interested in cybersecurity, scripting, networking, privacy, OSINT, emergency preparedness, or simply learning something new, I hope this software provides something useful.

There is no paid subscription required to use the GhostStrats tools included in this release.

Eventually, I would like to make the entire GhostStrats Multi Tool available for Linux. For now, the main application is designed for Windows 10 and Windows 11.

GS Local Chat already has a separate Linux Mint edition that can communicate with the Windows version.

This project will continue to evolve through development, testing, community feedback, and new ideas.

Thank you to everyone who has supported GhostStrats, tested previous versions, reported problems, and helped turn a simple HID tool into what it is today.

**Welcome to GhostStrats Multi Tool.**

*Safety is an Illusion.*

---

# What Is GhostStrats Multi Tool?

GhostStrats Multi Tool is a Windows desktop software platform that combines several cybersecurity, privacy, intelligence, automation, and educational utilities into one organized application.

Instead of downloading and managing numerous individual programs, users can access the available GhostStrats tools through a centralized dashboard.

The application uses a combination of Go-powered software engines, Windows utilities, local web interfaces, and custom GS scripting features.

The current desktop package includes **14 Custom Tools**, along with the built-in scripting and monitoring system.

### Main Features

- Main Go Engine and HID Go Engine
- GS Script Editor
- GS HID Script Builder
- GS Script Guide
- Standalone Windows executable creation
- Quick Toolbar
- Quick Launch
- Custom Tools library
- Live System Monitor
- Local storage and hardware information
- Windows system diagnostics
- GS Local Chat
- Privacy and cybersecurity education tools
- Open-source intelligence research utilities
- Offline emergency-preparedness resources
- Customizable GhostStrats themes
- Windows desktop installer and uninstaller

The application uses a black, charcoal, and deep-purple futuristic command-center interface built around the GhostStrats branding.

---

# System Requirements

### Supported Operating Systems

- Windows 10 — 64-bit
- Windows 11 — 64-bit

### Recommended

- A modern Intel or AMD 64-bit processor
- At least 8 GB of RAM
- Internal SSD storage
- Microsoft Edge, Google Chrome, or another compatible modern browser
- Available disk space for the installer, extracted companion tools, scripts, and saved files

Some utilities require Windows administrator permissions or compatible Wi-Fi/Bluetooth hardware.

An internet connection is needed for tools that retrieve current online information. Offline utilities and local features can operate without internet access where supported.

**The full GhostStrats Multi Tool is currently Windows-only.**

---

# Downloading and Installing

The application is distributed as a Windows installer rather than a USB-based launcher.

### Main Installer

`GhostStrats-Multi-Tool-Desktop-Installer-Latest.exe`

### Source Files

`GhostStrats-Multi-Tool-Desktop-Source-Latest.zip`

Download the latest installer from the project's official release or download location.

### Installation Instructions

1. Download the Windows installer.
2. Close any previous running versions of GhostStrats Multi Tool.
3. Run the installer.
4. Follow the installation wizard.
5. Select the installation directory.
6. Choose whether to create a desktop shortcut.
7. Complete the installation.
8. Launch GhostStrats Multi Tool from the desktop or Windows Start Menu.

The installer registers the application with Windows so it can be managed through the normal installed-applications interface.

### Default Installation Location

`%LOCALAPPDATA%\Programs\GhostStrats\Multi Tool`

### Application Workspace

`%LOCALAPPDATA%\GhostStrats\MultiTool`

The workspace stores application files such as scripts, settings, themes, locally prepared tools, and logs as required.

### Uninstalling

Open:

**Windows Settings → Apps → Installed apps**

Find GhostStrats Multi Tool and select **Uninstall**.

You can also use:

**Control Panel → Programs and Features**

The uninstaller is designed to remove the installed application without automatically deleting your saved workspace.

### Windows Security Notice

The installer is currently unsigned.

Windows Defender SmartScreen or other antivirus products may display warnings associated with an unfamiliar publisher or executable.

A proper installer does not guarantee that security products will trust every bundled program.

Verify the installer source and checksum before use. Never disable security protections simply to bypass an unexpected warning.

---

# Understanding the Go Engines

One of the important foundations of GhostStrats Multi Tool is its use of the **Go programming language**.

Go is a compiled programming language that can create efficient standalone applications.

GhostStrats Multi Tool uses Go-based components to coordinate the application, manage compatible tools, provide local services, and support scripting-related functionality.

The application incorporates two primary engine components.

## Main Go Engine

The Main Go Engine is responsible for much of the core application functionality.

It coordinates communication between the Windows application and the local dashboard interface.

Its responsibilities include supporting:

- Local application services
- Tool launching and process coordination
- Script execution requests
- Application resource management
- Dashboard communication
- Local APIs and service responses
- Supported system information requests

When you launch GhostStrats Multi Tool, the main application starts the necessary services and makes the dashboard available through your browser.

Although the interface is displayed in a browser, the main application itself is running locally on your Windows computer.

This does not require the dashboard to be hosted on a public website.

## HID Go Engine

The HID Go Engine supports the HID scripting and automation features inherited from the original GS USB Runner project.

HID stands for Human Interface Device.

Examples of HID devices include keyboards and mice.

The HID-related scripting tools are designed to help users learn about keyboard input automation, scripted commands, and supported execution methods.

The HID engine works alongside the main application, providing functionality for supported scripting tasks.

**Scripts should only be executed on computers you own or are explicitly authorized to use.**

---

# System Monitor — Engines and Storage

GhostStrats Multi Tool includes a live monitoring dashboard showing available hardware information and system performance.

## Hardware Identification

The System Monitor attempts to identify:

- Laptop or desktop form factor
- Computer manufacturer
- Device model
- Processor
- Windows operating system

A futuristic hardware visualization displays the detected computer type, including GhostStrats branding.

## Main Go Engine Monitoring

Displays available information about the primary application engine, including its status, CPU usage, and memory consumption.

## HID Go Engine Monitoring

Displays the HID engine's reported status and resource readings when available.

The HID engine may appear in standby when not in use.

## CPU Monitoring

Shows system CPU utilization and recent performance samples.

## RAM Monitoring

Displays current system memory consumption and available memory figures.

## Local Storage

Shows information about the Windows storage volume containing the GhostStrats workspace, including:

- Drive letter
- Total capacity
- Used storage
- Available space
- Storage utilization percentage

Storage figures describe the Windows volume, not just the size of GhostStrats Multi Tool itself.

## Status Indicators

The dashboard can show statuses such as:

**ONLINE** — The relevant component is reporting normally.

**STANDBY** — A component is available but may not currently be running an active operation.

**OFFLINE** — The requested service or measurement is not currently available.

**UNKNOWN** — The dashboard cannot confirm the component's current status.

An offline indicator does not automatically mean your computer has malfunctioned.

---

# GS Scripting Language

The GS scripting language is one of the original foundations of the GhostStrats project.

It is designed to provide a readable, command-based method of scripting supported keyboard and Windows actions.

Instead of requiring users to write a complete program in a traditional programming language, GS scripting uses simpler commands and instructions.

The built-in **GS Script Guide** documents the supported syntax.

## Example GS Script

This simple example opens the Windows Run dialog and types a message without executing it:

`# Opens Windows Run and types a message`

`PRESS WINDOWS + R`

`WAIT 1200 MILLISECONDS`

`TYPE "Hello from GhostStrats Multi Tool"`

### Understanding the Commands

**PRESS** — Sends a supported keyboard key or combination.

**WAIT** — Pauses script execution for the specified duration.

**TYPE** — Types the specified text.

The purpose of the scripting system is to make basic automation concepts more approachable and allow users to experiment within an authorized environment.

---

# GS Script Editor

The GS Script Editor is the main environment for creating, editing, reviewing, saving, and executing GS scripts.

### Main Features

- Script editing
- Syntax highlighting
- Built-in examples
- Script saving
- Script execution
- Stop controls
- Command reference
- Standalone Windows executable creation

## Creating a Script

1. Open GS Script Editor.
2. Select a new script or load an existing one.
3. Write your commands.
4. Review the script using the GS Script Guide.
5. Save your script.
6. Execute it when you are ready.

Use the **Stop** button to interrupt supported running execution.

## Creating a Standalone Executable

GhostStrats Multi Tool also allows supported GS scripts to be converted into standalone Windows executable files.

This allows a saved script to be distributed or run separately from the main editing interface.

### How to Create an EXE

1. Open the GS Script Editor.
2. Write or load your script.
3. Select **Create Executable**.
4. Enter the desired executable filename.
5. Select **Prepare Executable**.
6. Allow the application to build and validate the executable.
7. Once it reports that the executable is ready, click **Save Executable**.
8. Choose the destination folder in the save window.
9. Save the completed `.exe` file.

You can save the executable to your Desktop, Documents folder, or another available location.

### Saving to a USB Flash Drive

To save a script executable to a flash drive:

1. Connect your flash drive.
2. Prepare the executable.
3. Select Save Executable.
4. In the save window, open **This PC**.
5. Select your flash drive.
6. Save the executable.

The flash drive is simply the destination for the file.

**The executable does not automatically run when the flash drive is inserted.**

It must be deliberately opened by the user.

Review scripts before sharing or executing them.

---

# GS HID Script Builder

The GS HID Script Builder provides additional tools for creating and learning about HID-style scripting.

It is intended to help users understand how keyboard automation commands are structured and how supported script formats can be converted.

Depending on the selected workflow, available features include:

- HID script creation
- Script previews
- Supported command conversions
- DuckyScript-related learning features
- Script editing
- Explicit execution controls

Nothing should execute simply because a user opens the builder.

Users should review the generated instructions before running any script.

---

# Quick Toolbar

The Quick Toolbar provides convenient access to frequently used tools.

Instead of repeatedly navigating through the complete Custom Tools library, you can keep preferred tools and shortcuts within reach.

The toolbar works alongside the main desktop dashboard.

## Quick Launch

Quick Launch provides access to supported script examples and frequently used actions.

Select an example to run it deliberately through the appropriate script engine.

Some examples may require additional confirmation when they could change the system or interrupt a running session.

---

# Custom Tools — Complete Library

GhostStrats Multi Tool currently includes **14 Custom Tools** covering networking, privacy, intelligence gathering, preparedness, scripting-related research, and educational simulations.

Open **Custom Tools** from the dashboard to view the available applications.

Compatible browser-based utilities are designed to open in browser tabs. Native Windows applications may open in their own windows.

Some tools include a Stop button for terminating their associated service.

---

## 1. GS Digital Shadow Recon (GS D.S.R)

**Category: Offline Analysis / Wireless Intelligence**

GS Digital Shadow Recon is designed to analyze previously collected wireless observations.

Its primary purpose is to help identify patterns within recorded Wi-Fi, Bluetooth, and GPS information.

Unlike a live wireless scanner, GS D.S.R is designed around **post-collection analysis**.

You first collect data using compatible equipment or logging tools, then import the recording into GS D.S.R for review.

### Features

- Import supported wireless observation records
- Analyze Wi-Fi and Bluetooth detections
- Review recorded GPS routes
- Identify repeatedly observed devices
- Examine possible co-travel patterns
- Review suspicious or unusual observations
- Examine category hints for wireless devices
- Review possible vehicle, tracker, drone, camera, and audio-device indicators
- Clear an analysis session using Burn Session

### How to Use

Open GS D.S.R from Custom Tools and import a compatible recording.

The application analyzes the available information and presents observations for review.

You can inspect flagged entries to understand why they were highlighted.

**Important:** A flagged wireless device is not proof that someone is following or monitoring you.

Device names can be misleading or spoofed, identifiers can change, and recorded signal information can be incomplete.

GS D.S.R provides investigative observations and possible patterns, not confirmed device attribution or proof of surveillance.

---

## 2. GS Intel

**Category: Cyber Intelligence / World Intelligence**

GS Intel is an on-demand intelligence briefing application.

It is designed to help users review public information about important events and developments without constantly monitoring numerous individual websites.

Rather than running as an always-on surveillance service, GS Intel retrieves information when the user requests a briefing.

### Features

- Cybersecurity intelligence
- World events and developments
- Public emergency information
- Interactive visual map
- Topic Search
- Official Alerts
- Security vulnerability information
- Public-source intelligence briefings
- Links to original sources
- Demonstration data for testing

### How to Use

1. Launch GS Intel.
2. Select your preferred intelligence category.
3. Generate a briefing.
4. Review the collected results.
5. Use Topic Search to investigate a specific subject.
6. Open original publisher links for additional information.

GS Intel uses supported publicly available sources.

Some capabilities require an internet connection.

**GS Intel is not an official emergency alert receiver, guaranteed real-time warning service, or replacement for government emergency notifications.**

---

## 3. GS Survival / GS Disaster Ready

**Category: Emergency Preparedness / Offline Information**

GS Survival is an emergency-preparedness learning and reference application.

It contains information intended to help individuals prepare for emergencies, understand essential survival concepts, and organize preparedness resources.

The focus is on making useful reference material available even when internet access is unavailable.

### Topics Include

- Power outages and blackouts
- Severe weather
- Communications outages
- Emergency planning
- Drinking-water collection and purification
- Food storage
- Growing food
- Emergency supplies
- Evacuation planning
- Radio communications
- Off-grid communication concepts
- LoRa and Meshtastic
- Nuclear emergency preparedness
- General disaster-response guidance

### How to Use

Launch GS Survival and browse the available categories or use the search function to locate information.

Review the guides before an emergency so you understand which instructions and supplies are relevant to your situation.

Some library material can be expanded using optional saved documents and content packs.

Radio frequency references are educational information, not a live radio receiver.

Always follow current local emergency instructions and official public-safety guidance.

---

## 4. GS Dark Web

**Category: Privacy Education / Online Safety**

GS Dark Web is an educational privacy and resource center.

It introduces users to technologies and software commonly discussed in connection with privacy, anonymous networks, and safer information sharing.

### Topics and Resources

- Tor Browser
- Tails
- OnionShare
- Onion services
- Privacy fundamentals
- Security considerations
- Curated educational resources
- Saved bookmarks and resource links

### How to Use

Open GS Dark Web from Custom Tools.

Read the introductory guidance, browse the educational sections, and choose a resource to learn more.

The application provides explanations and links, but does not automatically anonymize normal browser traffic.

**A standard Chrome or Edge tab cannot access `.onion` services without an appropriate Tor-compatible setup.**

Users are responsible for following applicable laws and avoiding malicious or illegal online resources.

---

## 5. GS Antisensorship

**Category: Internet Privacy / Network Education**

GS Antisensorship helps users understand how internet filtering, censorship, proxies, and VPN technologies work.

It is primarily an educational workbench with optional user-controlled networking functions.

### Features

- Proxy education
- VPN concepts
- Internet filtering explanations
- HTTP and SOCKS proxy information
- Saved proxy profiles
- Optional proxy connection testing
- Setup guidance
- Privacy resources
- Opt-in proxy-browser launching

### How to Use

Open GS Antisensorship and select the topic or tool you want to explore.

You can read the guidance, review available settings, and use supported connection tests where appropriate.

The application does not automatically change your entire computer's proxy configuration.

Some networking features require an active internet connection.

A proxy or VPN cannot restore connectivity when the underlying network is completely unavailable.

---

## 6. GS Crypto Lab

**Category: Cryptography / Encoding / Education**

GS Crypto Lab provides a local environment for learning about common encoding methods, hashing, and cryptographic operations.

### Features

- Base64 encoding and decoding
- Hexadecimal conversion
- URL encoding
- ROT13
- Caesar cipher
- Hashing
- HMAC
- Format inspection
- AES-256-GCM encryption and decryption

### How to Use

1. Launch GS Crypto Lab.
2. Select the desired operation.
3. Enter your test text or supported input.
4. Run the operation.
5. Review the output.

GS Crypto Lab can be useful for students, developers, and anyone interested in understanding cryptographic concepts.

**Encoding is not the same thing as encryption.** Some historical algorithms and transformations are included for educational purposes rather than modern security.

Protect sensitive passwords and keys, and independently verify results before using them for important security decisions.

---

## 7. GS Blackout

**Category: Device Privacy / Windows Controls**

GS Blackout is a Windows privacy utility that can help users disable and restore supported communication and input devices.

### Supported Control Categories

- Wi-Fi
- Bluetooth
- Supported network interfaces
- Cameras
- Microphones

### How to Use

Launch GS Blackout and review the available controls.

Choose the devices or interfaces you want to disable, then deliberately activate the relevant control.

Use the restore controls when you are ready to re-enable them.

**Warning:** Disabling a network interface may immediately disconnect the computer from Wi-Fi, a local network, or a remote session.

Some operations require administrator permissions, supported drivers, or hardware-specific capabilities.

Do not disable devices unless you understand how to restore them.

---

## 8. GS Null Out

**Category: Windows Shutdown / Inactivity Management**

GS Null Out is a Windows utility designed around optional inactivity-based shutdown behavior.

It can help users configure an automatic shutdown after a period of inactivity.

### Features

- Inactivity monitoring
- Countdown display
- Shutdown configuration
- Cancellation controls
- Manual activation
- Supported keyboard shortcut

The shortcut includes tapping **G** and then holding **S** for approximately three seconds when the corresponding feature is enabled.

### How to Use

Launch GS Null Out, review the settings, and enable the monitoring behavior you want.

When activated, the application monitors the configured inactivity conditions and can initiate a shutdown after the relevant countdown.

Save your work before enabling shutdown features.

A real Windows shutdown can close applications and interrupt ongoing tasks.

---

## 9. GS OSINT

**Category: Open-Source Intelligence / Research**

GS OSINT provides tools and references for investigating publicly available information.

OSINT stands for Open-Source Intelligence.

It involves collecting, organizing, and reviewing information from sources that are publicly accessible.

### Features

- Domain research
- IP-related research
- Public-source lookup resources
- Image metadata inspection
- Topic and identity research links
- Investigation notes
- Local case organization
- Source tracking

### How to Use

Open GS OSINT and select the desired research category.

Enter the appropriate public information, review the available results, and document relevant sources.

External research links may open their respective websites.

The tool is intended for lawful research and defensive investigations.

It is not intended to bypass private accounts, unauthorized access restrictions, or other security controls.

---

## 10. GS Spectrum Scanner

**Category: Wireless Networking / Wi-Fi / Bluetooth**

GS Spectrum Scanner is designed to discover and inspect nearby wireless devices and networks using supported Windows hardware.

### Features

- Wi-Fi network discovery
- Bluetooth device discovery
- Available signal information
- Device inspection
- Network and device filtering
- Wireless inventory export

### How to Use

Launch GS Spectrum Scanner and start the relevant discovery function.

Review the detected information and use available filters to organize the results.

Results depend on Windows permissions, installed drivers, adapter capabilities, and the surrounding radio environment.

The scanner may not detect every wireless device or every signal.

Use it only for authorized wireless assessment and learning.

---

## 11. GS Local Chat

**Category: Local Networking / Communication**

GS Local Chat is a lightweight communication application that allows compatible computers to exchange messages over a reachable local network.

It does not require a cloud messaging account or external chat server.

The application supports Windows and has a separate Linux Mint edition.

Its default channel is:

**#general**

All compatible installations share the same room identifier:

`GS-GENERAL-LAN`

### Features

- Local-network communication
- Shared General channel
- Windows and Linux Mint compatibility
- Automatic LAN host discovery
- Join Host by IP
- Browser-based interface
- User-selected callsigns
- Connected-user display
- Clear All Messages
- Temporary in-memory messages

The room code is a public identifier, not a private password.

A matching room code does not automatically connect two independently hosted rooms.

All users must connect to the same host computer.

### Full Setup Guide

See the dedicated GS Local Chat instructions below.

---

## 12. GS Network View

**Category: Network Visualization / Diagnostics**

GS Network View is a bundled network-visualization and diagnostics utility.

It provides a separate environment for examining supported network information.

Launch it from Custom Tools and review the information made available by the application.

Its capabilities may vary depending on Windows configuration and available interfaces.

This is a legacy companion tool, and complete original source coverage is not available for its bundled executable.

---

## 13. GS Ransomware Awareness

**Category: Cybersecurity Education / Simulation**

GS Ransomware Awareness is an educational visual simulation intended to demonstrate how disruptive a ransomware incident can appear.

It is designed for training and awareness rather than performing a real ransomware attack.

### Features

- Visual ransomware-themed demonstration
- Educational warning screens
- Cybersecurity-awareness experience
- Prevention and recovery information

The demonstration does not intentionally encrypt, delete, or lock the user's actual files.

It may display a fullscreen visual experience.

**Press Esc to exit the demonstration.**

Always use simulations in environments where participants understand what is being demonstrated.

---

## 14. GS BSOD Simulator

**Category: Windows Education / Visual Simulation**

GS BSOD Simulator recreates the appearance of Windows blue-screen error displays for demonstrations and educational purposes.

### Features

- Visual blue-screen reproductions
- Classic and custom display styles
- Demonstration environment
- Exit controls

The simulator is not designed to intentionally crash Windows.

**Press Esc to exit.**

---

# GS Local Chat — Complete Windows and Linux Guide

GS Local Chat deserves its own explanation because it can connect multiple computers together through a local network.

The purpose is straightforward:

**Allow computers on the same reachable local network to communicate without relying on an external chat service.**

## What You Need

- Two or more compatible computers
- A shared, reachable local network
- GS Local Chat installed or available on each system
- A modern web browser

Supported networking arrangements may include Wi-Fi, Ethernet, or a compatible phone hotspot.

The computers need to be able to communicate directly across that network.

## Windows Setup

1. Launch GhostStrats Multi Tool.
2. Open Custom Tools.
3. Find GS Local Chat.
4. Click **Open Chat**.
5. Allow the local chat interface to open in your browser.
6. Enter your preferred callsign.
7. Connect to the General channel.

## Linux Mint Setup

Install the standalone GS Local Chat package for Linux Mint.

Launch the application from your Linux desktop environment.

The Linux version uses the same General room identifier as the Windows version.

## General Channel Settings

**Channel:** `#general`

**Room code:** `GS-GENERAL-LAN`

**Default chat port:** `8765/TCP`

**Discovery port:** `8766/UDP`

The application attempts to discover an existing host on the local network.

If no reachable host is discovered, a computer may start its own General room.

## Connecting Windows to Linux

Suppose Linux is hosting the chat and its local address is:

`172.20.10.7`

On Windows:

1. Open GS Local Chat.
2. Select **Join Host by IP**.
3. Enter `172.20.10.7`.
4. Connect to that host.
5. Enter your callsign.
6. Start messaging.

Alternatively, open the Linux host's LAN address directly in your browser:

`http://172.20.10.7:8765/?key=GS-GENERAL-LAN`

This is an example address. Your computer's actual local IP address may be different.

### Understanding 127.0.0.1

You may see a browser address such as:

`http://127.0.0.1:8765`

That address refers to the computer you are currently using.

It does not automatically refer to the other computer on your network.

If Windows and Linux are both hosting independent rooms, they can both display Connected while showing different messages.

To communicate, one computer must join the other computer's actual LAN address.

## Automatic Host Discovery

GS Local Chat attempts to locate an existing General room automatically.

This can work when the network permits the necessary local discovery traffic.

However, certain routers, firewalls, and phone hotspots may block discovery broadcasts.

When discovery does not work, use **Join Host by IP**.

## Sending Messages

Once connected:

1. Enter your callsign.
2. Type a message.
3. Click Send.
4. Connected participants in the same room receive the message.

## Clearing Messages

GS Local Chat includes a **Clear All Messages** function.

Selecting it prompts for confirmation and clears the current room's shared message history.

Messages are stored in the host application's memory rather than a persistent cloud database.

History is cleared when the host stops. The current implementation also clears room history after the last participant disconnects.

Closing one participant's browser tab does not necessarily erase the conversation while other participants remain connected.

## Privacy and Security

GS Local Chat is intended for trusted local-network communication.

It does not provide end-to-end encryption.

Communication currently uses HTTP.

The universal General room code is not a secret password.

**Do not send passwords, private encryption keys, financial information, or other highly sensitive data through GS Local Chat.**

If you require confidential communication, use a properly secured and encrypted messaging system.

---

# Browser Tabs and Tool Management

GhostStrats Multi Tool uses a unified approach to launching compatible tools.

Browser-based utilities are designed to open as tabs alongside the main dashboard, while supported Windows-native utilities retain their own application windows.

This helps keep the main interface available while switching between tools.

Some applications run their own background processes.

Closing a browser tab does not always stop the underlying process.

Use **Stop**, **Exit**, or the appropriate shutdown action when available.

Some external destinations, privacy browsers, and native utilities may still require separate windows.

---

# Themes and Personalization

GhostStrats Multi Tool uses a dark tactical visual style.

The default design combines:

- Black
- Charcoal gray
- Deep purple
- Holographic-style graphics
- GhostStrats eyes branding
- Live status displays

The application includes theme and appearance options, including community visual themes.

Appearance settings allow supported elements of the desktop interface to be customized.

The dashboard is designed primarily for Windows desktop displays, and appearance can vary with screen resolution and browser zoom.

---

# Application Storage and Saved Files

GhostStrats Multi Tool keeps its working files separate from its installed program files.

### Program Location

`%LOCALAPPDATA%\Programs\GhostStrats\Multi Tool`

### Workspace Location

`%LOCALAPPDATA%\GhostStrats\MultiTool`

The workspace may contain:

- Saved scripts
- Application settings
- Custom themes
- Prepared companion applications
- Local working files
- Logs
- Other application data

The installer and uninstaller are designed to preserve this workspace during normal updates and removal.

Back up important files before making major changes or reinstalling.

---

# Troubleshooting

## Dashboard Shows Offline

An offline indicator may mean the local application service has not started, has disconnected, or is temporarily unavailable.

Close the running application and reopen it.

If the problem continues, inspect Logs and the desktop startup diagnostic file.

## Application Says Already Running

A previous application process may still be closing.

Allow it to exit before launching another copy.

Avoid running multiple instances of the same local service unnecessarily.

## GS Script Executable Does Not Work

Verify that Prepare Executable completed successfully.

Check that the saved EXE is not empty.

Test with a harmless example script before using more complex instructions.

## GS Local Chat Does Not Connect

Check that both devices are on the same reachable network.

Confirm which computer is hosting the room.

Use Join Host by IP if automatic discovery fails.

Check host firewall permissions on a trusted network.

## Windows and Linux Show Different Messages

The two machines may be hosting independent rooms.

Use the actual LAN address of one host to connect the other computer.

Both must use the same host to share a conversation.

## A Tool Opens in the Wrong Window

Compatible browser-based tools are designed to open through the unified tab launcher.

Some native or specialized tools may still open their own Windows interfaces.

## Old Interface Appears After Updating

Close all running instances.

Reopen the application from the updated desktop shortcut.

Refresh the browser with **Ctrl + Shift + R** if necessary.

If the chat is hosted by Linux, update the Linux host to change the interface served to connected clients.

---

# Source Code and Development

The GhostStrats Multi Tool source package contains available application code and development resources.

These include:

- Go-based desktop launcher source
- Windows support files
- Dashboard HTML, CSS, and JavaScript
- UI assets
- Available companion-tool source trees
- Installer source
- Uninstaller source
- Windows build scripts

### Building From Source

The current development package uses Go 1.23 or newer and requires Python 3 with NumPy for parts of the Windows packaging process.

The source ZIP includes a Windows build script.

Users downloading the finished Windows installer do not need to install Go or Python.

### Important Source Transparency

Some older GhostStrats tools and engine components remain distributed as precompiled executables because matching original source is not available in the current package.

Related source trees are available for several companion tools, but not every included binary has been proven reproducible from those sources.

The release should not be described as completely independently audited or fully source-reproducible.

Source availability also does not automatically establish a software redistribution or modification license.

Applicable licensing terms should be published separately.

---

# Responsible Use

GhostStrats Multi Tool is intended for educational, defensive, research, privacy, and preparedness purposes.

Some utilities demonstrate cybersecurity scenarios.

Other tools can make real changes to a Windows computer, including network-device controls and shutdown actions.

Use these capabilities carefully.

Wireless observations, intelligence results, and public-source information may be incomplete or inaccurate.

GhostStrats Multi Tool is not a certified forensic system, guaranteed threat detector, or replacement for official emergency services.

**Operate only on systems you own or are authorized to test.**

Users are responsible for complying with applicable laws and respecting the privacy and security of others.

---

# Future Development

GhostStrats Multi Tool started as a software-based HID utility and has grown into an entire desktop toolkit.

I plan to keep improving its reliability, interface, tool integration, and documentation.

A complete Linux desktop edition remains a future goal.

In the meantime, I want to continue improving the Windows application and making the included tools more useful and accessible.

Community feedback is an important part of this project.

If you find a bug, identify something that could work better, or have an idea for a new educational feature, your feedback is appreciated.

---

# Final Words

GS USB Runner was the beginning.

GhostStrats Multi Tool is the next chapter.

What began as a small HID scripting project eventually became something much larger, and despite the setbacks along the way, I am proud of how far it has come.

I wanted to create something useful, make it available for free, and give something back to the people who have supported the project.

If even one of these tools helps somebody learn a new skill, understand a cybersecurity concept, prepare for an emergency, or build something of their own, then the work has been worth it.

Thank you for being part of the GhostStrats community.

**GhostStrats**

**Safety is an Illusion.**
