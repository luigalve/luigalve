<!--
**luigalve/luigalve** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!-- Profile README. Everything in [brackets] is a placeholder to fill in.
     This file lives in a public repo named EXACTLY the same as your username.
     That is what makes it render on your profile page.
     House style: no em dashes, no emoji, no badges. -->


# Hi, I'm Luis

IT support technician. CompTIA A+ and Google IT Support certified.<br>
<sub>Currently preparing for the Azure Administrator exam (AZ-104).</sub>
<br>
<br>

I learn by building. <br>
Everything below runs on hardware I set up, broke, and fixed myself,<br>
and nearly all of it is administered remotely.<br>

<sub>_This GitHub exists to share the tools I build while studying and show my work in public._</sub>

<!-- Optional: a two-line Spanish version of the intro can go here. -->

## One Step at a Time Apps

**Interactive runbooks for completed IT projects** <br>
The apps put a single **step** on screen, broken into a short list of checkable **actions**, so the task in front of you always feels doable.
<br>


_Tick the **actions**, complete the **step**, and watch it turn green!_<br>
<sub>Built for anyone who has ever gotten lost or overwhelmed halfway through a long guide.</sub>



### [Install Proxmox on an Old PC](https://luigalve.github.io/proxmox-old-pc/)

This first 7-step walkthrough takes an older BIOS-only desktop out of retirement and turns it into a running Proxmox server, including every way the hardware fought back and every fix that worked. 
One toggle switches the whole guide between older BIOS machines and newer UEFI ones, so both paths are covered.

**[Try it live](https://luigalve.github.io/proxmox-old-pc/)** &middot; [View the source](https://github.com/luigalve/proxmox-old-pc/blob/main/index.html) &middot; [Take the full guide as one file](https://github.com/luigalve/proxmox-old-pc/blob/main/docs/full-walkthrough.md)

*Skills: teaching and curriculum design, Proxmox virtualization, Legacy BIOS & UEFI Configuration, Bootloader Mechanics, Checksum Integrity Verification, Network Interface Configuration, Web-Based Hypervisor Management*
<br>
<br>

### [Build Your Own Walkthrough App](https://luigalve.github.io/build-your-own-walkthrough/)

This 11-step course teaches someone with zero coding experience to plan, hand-build, and publish a walkthrough app like the one above for their own project: HTML, CSS, JSON, and JavaScript, one card at a time, ending with their app live on GitHub Pages. Every bug in its troubleshooting panels happened for real while building it.

**[Try it live](https://luigalve.github.io/build-your-own-walkthrough/)** &middot; [View the source](https://github.com/luigalve/build-your-own-walkthrough/blob/main/index.html) &middot; [Take the full guide as one file](https://github.com/luigalve/build-your-own-walkthrough/blob/main/docs/full-walkthrough.md)


*Skills: teaching and curriculum design, HTML/CSS, JavaScript, JSON, Python docs automation, GitHub Pages*

## How these projects work

Each app is one self-contained HTML file: it runs offline with a double-click, needs no installs, and serves two audiences at once. Hands-on mode walks a learner through the project step by step; Just Browsing lets a recruiter read everything in two minutes. The app's data block is the single source of truth, and the Python scripts in each repo generate the Markdown documentation straight from it, so the docs can never drift from the app. Change the data, rerun the script, done.

## On the bench

Each project below is queued to become a walkthrough app like the ones above. Links go live as they publish.

### Windows Server Home Lab

A complete small-business network built on one repurposed desktop: a domain controller managing user accounts and security policies, automatic updates, shared storage, remote desktops, and a live sync to Microsoft's cloud identity service. More than ten server roles, all configured by hand. If a small office needs it, this lab has a working version of it.

[Documentation]([repo link, coming soon])

*Skills: Active Directory, DNS, DHCP, Group Policy, certificates (AD CS), Entra Connect, Azure Arc, RDS, DFS, WSUS, Proxmox virtualization*

### Home Network Security

A standard home router turned into a segmented, monitored network. Smart-home gadgets and guest devices are walled off on their own network segments, ads and trackers are blocked before they ever load, and chosen devices route all traffic through an encrypted VPN tunnel that cuts the connection if the tunnel drops. Published as a reference architecture with sanitized configs.

[Documentation]([repo link, coming soon])

*Skills: VLAN segmentation, firewall rules, DNS filtering, WireGuard VPN, router firmware (Asuswrt-Merlin)*

### Excel Column Aggregator

A desktop tool born from a real workflow problem: a manufacturing quality-inspection team needed measurement columns pulled out of many Excel workbooks into one master file, by hand, every time. I researched the libraries, built the fix in two weeks, and shipped it as a single executable. It has run in daily production since, with zero support tickets. This repo is the generic version: pick your own columns, point it at your own files.

[Download the app]([release link, coming soon]) &middot; [Source]([repo link, coming soon])

*Skills: Python, tkinter, data handling, packaging (PyInstaller), requirements gathering*

### AZ-104 Quick Reference

A single-file web page that turns all 38 Azure services on the AZ-104 exam into a searchable, filterable cheat sheet, including the exact PowerShell and CLI commands an administrator actually types. Built for my own studying. Works offline. Free to anyone else preparing.

[Use it live]([GitHub Pages link, coming soon]) &middot; [Source]([repo link, coming soon])

*Skills: HTML, CSS, JavaScript, Azure administration, technical writing*

### 3D Printer From Salvage (in progress)

Building a working 3D printer out of stepper motors harvested from dead office printers, driven by a five-dollar ESP32 microcontroller. Slow, cheap, and very educational.

[Build log]([repo link, coming soon])

*Skills: electronics, microcontrollers, hardware troubleshooting*

## Certifications

- CompTIA A+
- Google IT Support Professional Certificate
- Microsoft Certified: Azure Administrator (AZ-104): in progress

## Contact

[LinkedIn]([profile link]) &middot; [email]
