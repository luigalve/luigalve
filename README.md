<!--
**luigalve/luigalve** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
<p align="center">
  <img src="./assets/capsule-1.svg" alt="" />
</p>

<p align="center">
  <img src="./assets/capsule-2.svg" alt="" />
</p>

<p align="center">
  <img src="./assets/capsule-3.svg" alt="" />
</p>
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

<p align="left">
  <img src="./assets/A-Readme-colorful-01.svg" alt="Hi, I'm Luis" />
  <img src="./assets/B-Readme-slide-01.svg" alt="IT support technician. CompTIA A+ and Google IT Support certified. Currently preparing for the Azure Administrator exam (AZ-104)." />
</p>


I learn by building. 

Everything below runs on hardware I set up, broke, and fixed myself,<br>
and nearly all of it is administered remotely.<br>


<sub>_This GitHub exists to share the tools I build while studying and show my work in public._</sub>


<!-- Optional: a two-line Spanish version of the intro can go here. -->

<br>

## One Step at a Time Apps: Interactive runbooks for completed IT projects


Built for anyone who has ever gotten lost or overwhelmed halfway through a long guide.

Tick the **actions**, complete the **step**, and watch it turn green!<br>


<sub>The apps put a single _**step**_ on screen, broken into a short list of checkable _**actions**_, so the task in front of you always feels doable.</sub>
<br>
<br>



### [Install Proxmox on an Old PC](https://github.com/luigalve/proxmox-old-pc/)

**[Try it live](https://luigalve.github.io/proxmox-old-pc/)** &middot; [View the source](https://github.com/luigalve/proxmox-old-pc/blob/main/index.html) &middot; [Take the full guide as one file](https://github.com/luigalve/proxmox-old-pc/blob/main/docs/full-walkthrough.md)

This first 7-step walkthrough takes an older BIOS-only desktop out of retirement<br>
and turns it into a running Proxmox server, including every way the hardware fought back<br>
and every fix that worked.<br>

One toggle switches the whole guide between older BIOS machines<br>
and newer UEFI ones, so both paths are covered.
<br>
<br>


<sub>_Skills: Teaching and curriculum design, Proxmox virtualization, Legacy BIOS & UEFI Configuration,<br>
Bootloader Mechanics, Checksum Integrity Verification, Network Interface Configuration, Web-Based Hypervisor Management_</sub>
<br>
<br>




### [Build Your Own Walkthrough App](https://github.com/luigalve/build-your-own-walkthrough/)

**[Try it live](https://luigalve.github.io/build-your-own-walkthrough/)** &middot; [View the source](https://github.com/luigalve/build-your-own-walkthrough/blob/main/index.html) &middot; [Take the full guide as one file](https://github.com/luigalve/build-your-own-walkthrough/blob/main/docs/full-walkthrough.md)

This 11-step course teaches someone with zero coding experience to<br>
plan, hand-build, and publish a walkthrough app like the one above for their own project.<br>
HTML, CSS, JSON, and JavaScript, one card at a time, ending with their app live on GitHub Pages.<br> 
Every bug in its troubleshooting panels happened for real while building it.
<br>
<br>


<sub>_Skills: Teaching and curriculum design, HTML/CSS, JavaScript, JSON, Python docs automation, GitHub Pages_</sub>
<br>
<br>
<br>

### **How these projects work**<br>
<sub>Each app is one self-contained HTML file.<br>
It runs as a Github Page and offline without installs.<br>
<br>
Hands-on mode walks a learner through the project step by step.<br>
Just Browsing lets a viewer read everything in a few minutes.<br>
<br>
The app's data block is the single source of truth,<br>
and the Python scripts in each repo generated the Markdown documentation straight from it,<br>
so the docs never differ from the app. Change the data in index.html, rerun the script, done.</sub>
<br>
<br>

---
<br>

## Tools
Free, open source, single-file HTML apps. No dependencies, no install, runs offline and locally.<br>
Download one file and open it in a browser.
<br>
<br>

## Foundry Studio
A visual SVG design studio in a single file. Multi-canvas capsule architecture, shape biting via SVG masks, rotation, and animation presets. I built it to make graphics for my own READMEs after realizing every badge and header service is a dependency that can go down. Anything you make here is a static file in your repo that never breaks.
[Repo link]

_Pick a style, type your text, export. No accounts and no build step._
<br>
<br>


### [DensePack](https://github.com/luigalve/DensePack/)
**[Try it live](https://luigalve.github.io/DensePack/)** &middot; [View the source](https://github.com/luigalve/DensePack/blob/main/index.html)<br>

Converts pasted text into the smallest AI-readable PNG. Configurable fonts, density stats, newline and indentation markers, and a marker clash detector. Built for feeding long documents to vision models without uploading files.

Paste your text, adjust your settings and copy your condensed image.
<br>
<br>

### [AZ-104 Quick Reference](https://github.com/luigalve/az104-reference/)
**[Try it live](https://luigalve.github.io/az104-reference/)** &middot; [View the source and download the file](https://github.com/luigalve/az104-reference/blob/main/index.html)

A single-file web page that turns all 38 Azure services on the AZ-104 exam into a searchable, filterable cheat sheet, including the exact commands an administrator actually types.<br>
Made for my own studying but built to be modified by anyone.<br>
Works offline and free to anyone else preparing.<br>

*Skills: Azure administration, technical writing, documentation*

---
<br>

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
