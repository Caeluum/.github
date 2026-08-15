<p align="center">
  <img src="./assets/caelum-logo.png" width="150" alt="Caelum logo" />
</p>

<p align="center">
  <img src="./assets/caelum-wallpaper.png" width="100%" alt="Caelum — open-source operating systems" />
</p>

<h1 align="center">Caelum</h1>

<p align="center">
  <strong>Building fast, stable, and thoughtfully designed open-source operating systems.</strong>
</p>

<p align="center">
  Born in Brazil. Built in the open. Powered by Linux.
</p>

<p align="center">
  <a href="https://github.com/Caeluum/velaris">
    <img src="https://img.shields.io/badge/Featured-Velaris-4f46e5?style=for-the-badge&logo=linux&logoColor=white" alt="Velaris" />
  </a>
  <a href="https://github.com/Caeluum">
    <img src="https://img.shields.io/badge/Open%20Source-Always-111827?style=for-the-badge&logo=github&logoColor=white" alt="Open source" />
  </a>
  <img src="https://img.shields.io/badge/Base-Arch%20Linux-1793d1?style=for-the-badge&logo=archlinux&logoColor=white" alt="Arch Linux" />
  <img src="https://img.shields.io/badge/Desktop-KDE%20Plasma-1d99f3?style=for-the-badge&logo=kde&logoColor=white" alt="KDE Plasma" />
</p>

---

## About Caelum

**Caelum** is an open-source organization focused on creating Linux operating
systems that feel responsive, reliable, and welcoming from the first boot.
Our work brings together Arch Linux, modern desktop technologies, careful
performance tuning, automated builds, and a strong visual identity.

We believe a fast system should also be predictable. Every optimization should
have a purpose, every default should be understandable, and every release
should be reproducible.

## What we build

Our projects cover the complete operating-system experience:

- Linux distribution profiles and installation media;
- desktop environments, themes, branding, and first-boot experiences;
- performance and memory-management defaults;
- installers, boot flows, recovery paths, and hardware compatibility;
- automated validation, ISO builds, release engineering, and documentation.

## Featured project — Velaris

<table>
  <tr>
    <td width="68%" valign="top">
      <h3>Velaris</h3>
      <p>
        An Arch Linux-based distribution built for responsive desktop use,
        gaming, and everyday reliability. Velaris combines KDE Plasma 6 with
        the CachyOS kernel, a focused package set, safe performance tuning,
        and a custom Calamares installation experience.
      </p>
      <p>
        <a href="https://github.com/Caeluum/velaris"><strong>View repository →</strong></a>
        &nbsp;•&nbsp;
        <a href="https://github.com/Caeluum/velaris/releases"><strong>Downloads →</strong></a>
      </p>
    </td>
    <td width="32%" valign="top">
      <strong>Foundation</strong><br />Arch Linux<br /><br />
      <strong>Desktop</strong><br />KDE Plasma 6<br /><br />
      <strong>Kernel</strong><br />linux-cachyos<br /><br />
      <strong>Installer</strong><br />Calamares
    </td>
  </tr>
</table>

### Velaris highlights

- **Responsive by design:** CachyOS kernel, BORE, LTO, ZRAM, GameMode,
  `irqbalance`, `earlyoom`, and Ananicy C++.
- **Modern desktop:** KDE Plasma 6 with Wayland as the primary session and X11
  available for compatibility.
- **Clean installation:** a Velaris-specific Calamares configuration keeps the
  installed system separate from the live environment.
- **Reliable package management:** Arch Linux and CachyOS keyrings are prepared
  and validated inside the final image.
- **Reproducible releases:** automated profile validation and ISO builds run
  through GitHub Actions.
- **Consistent identity:** custom wallpapers, icons, Plymouth, Fastfetch, and
  installer branding.

## Our teams

Caelum is organized around focused areas that work together on each release.

| Team | Focus |
|---|---|
| **Core OS & Release Engineering** | Distribution architecture, package selection, ISO profiles, versioning, and release coordination. |
| **Kernel & Performance** | Kernel integration, scheduling, memory behavior, storage tuning, thermals, and measurable performance improvements. |
| **Desktop & Design** | KDE Plasma defaults, accessibility, themes, wallpapers, branding, and the complete user experience. |
| **Installer & Hardware** | Calamares, bootloaders, firmware support, graphics, networking, audio, and installation reliability. |
| **Infrastructure & Automation** | GitHub Actions, build runners, artifact delivery, validation, reproducibility, and project tooling. |
| **Quality & Community** | Testing, bug reports, documentation, contributor support, translations, and release feedback. |

## Engineering principles

### Performance with evidence

We prefer targeted, measurable improvements over aggressive global tweaks.
Fast boot times and low memory usage matter, but never at the cost of broken
graphics, audio, networking, or package integrity.

### Stability as a feature

Safe defaults, graceful behavior under memory pressure, signed repositories,
clear recovery options, and clean upgrades are part of the product—not
afterthoughts.

### Open development

Source code, build definitions, decisions, known limitations, and validation
steps belong in public repositories whenever possible.

### Design with purpose

Visual identity should make the system feel cohesive without hiding how Linux
works. Beauty, clarity, and performance can coexist.

## Technology

<p>
  <img src="https://skillicons.dev/icons?i=linux,arch,bash,python,docker,github,git,qt" alt="Caelum technology stack" />
</p>

| Area | Technologies |
|---|---|
| Distribution | Arch Linux, Archiso, Pacman, systemd |
| Desktop | KDE Plasma, Qt, Wayland, X11 |
| Installation | Calamares, GRUB, Plymouth |
| Audio & network | PipeWire, NetworkManager |
| Automation | GitHub Actions, Docker, self-hosted Linux runners |
| Tooling | Bash, Python, YAML, Git |

## Current direction

- Continue hardening the Velaris installation and first-boot experience.
- Expand testing across virtual machines and real AMD, Intel, and NVIDIA
  hardware.
- Improve release delivery, checksums, documentation, and issue templates.
- Build reusable Caelum components for future distributions and system tools.
- Grow an open contributor community around performance, stability, and design.

## Contributing

Contributions are welcome across engineering, testing, design, documentation,
and translation.

1. Explore the project repositories and their documentation.
2. Check existing issues before opening a new report.
3. Describe your hardware, expected behavior, and reproduction steps clearly.
4. Keep pull requests focused and include the validation you performed.
5. Be respectful, patient, and constructive with other contributors.

For Velaris bugs and suggestions, use the
[Velaris issue tracker](https://github.com/Caeluum/velaris/issues).

## Community standards

Caelum is committed to an inclusive, curious, and technically honest project
environment. We welcome beginners and experienced contributors alike. Good
questions, careful testing, helpful documentation, and thoughtful design are
all meaningful contributions.

## Project status

Velaris is currently in **Beta**. It is suitable for testing and development,
but users should keep backups and test installation media in a virtual machine
or secondary system before using it on important hardware.

---

<p align="center">
  <img src="./assets/caelum-logo.png" width="72" alt="Caelum" />
</p>

<p align="center">
  <strong>Caelum</strong><br />
  Open systems. Clear purpose. Better experiences.
</p>

<p align="center">
  <a href="https://github.com/Caeluum">GitHub</a>
  ·
  <a href="https://github.com/Caeluum/velaris">Velaris</a>
  ·
  <a href="https://github.com/Caeluum/velaris/issues">Issues</a>
</p>
