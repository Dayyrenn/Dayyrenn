<div align="center">

# Hi, I'm [YOUR_NAME] 👋

**Developer · Game Server Tools · Android**

Based in Indonesia 🇮🇩 · Building tools for SA-MP / open.mp, including [OmpHub](https://github.com/[GITHUB_USERNAME]/OmpHub)

[![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.com/users/[YOUR_DISCORD_ID])
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:[YOUR_EMAIL])
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/[YOUR_INSTAGRAM])
![Profile views](https://komarev.com/ghpvc/?username=[GITHUB_USERNAME]&style=flat-square&color=blue)

</div>

---

## About me

- 💻 Intermediate developer working with **CSS, Java, TypeScript, and Python**
- 🎮 Into the **SA-MP / open.mp** world: gamemodes, servers, and the tools around them
- 🌱 Currently learning: [WHAT_YOU_ARE_LEARNING]
- 💬 Ask me about: Python, Java, TypeScript, CSS, and SA-MP / open.mp

## Skills

| Language | Level |
|---|---|
| ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white) | Intermediate |
| ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) | Intermediate |
| ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | Intermediate |
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Intermediate |

---

## Portfolio

### OmpHub: a game server panel that runs on an Android phone

![Platform](https://img.shields.io/badge/platform-Android%208.0%2B%20(arm64)-3DDC84)
![Version](https://img.shields.io/badge/version-1.1.0-blue)
![Root](https://img.shields.io/badge/root-not%20required-success)

<!-- Add screenshots here:
<p align="center">
  <img src="docs/dashboard.png" width="220">
  <img src="docs/console.png" width="220">
  <img src="docs/files.png" width="220">
</p>
-->

**Role:** [YOUR_ROLE, e.g. Solo developer] &nbsp;·&nbsp; **Status:** v1.1.0 &nbsp;·&nbsp; **Source:** private

**The problem.** Hosting an open.mp or SA-MP server normally means renting a VPS or keeping a PC running. For development, testing, and small communities, that's a lot of cost and setup.

**The solution.** OmpHub is an Android app that runs the game server and a MariaDB database directly on a phone, with no root. Everything is managed from one app.

**What it does**

- Start, stop, and restart the game server and database, with a foreground service that keeps them alive in the background
- Live dashboard with server info and the online player list
- Console over stdin and RCON
- Built-in file manager and text editor for configs and gamemodes
- MariaDB with a SQL console, import, and export
- One-tap backup and restore of the server folder and database
- Supports both open.mp and SA-MP (0.3.7 and 0.3.DL) with a shared server folder

**Technical highlights**

- **Two runtimes, one app.** The game server runs through PRoot + QEMU user-mode in a Debian i386 rootfs, while MariaDB runs natively in a separate Alpine arm64 rootfs, so the database isn't slowed down by emulation.
- **No root on modern Android.** Binaries ship as native libraries, the only location Android allows to execute from.
- **Safe installs.** Rootfs archives are extracted to a temporary folder and renamed, so an interrupted install is never treated as complete.
- **Own protocol client.** A UDP client for the SA-MP query and RCON protocol (also used by open.mp) powers the dashboard and console.
- **Careful config handling.** The panel only edits the keys it needs and leaves everything else untouched. Weak RCON passwords are replaced with random ones automatically.

**Tech stack**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Links:** [Download APK](https://github.com/[GITHUB_USERNAME]/OmpHub/releases/latest) · [Changelog](https://github.com/[GITHUB_USERNAME]/OmpHub/blob/main/CHANGELOG.md)

### More projects

| Project | Description | Tech |
|---|---|---|
| [OTHER_PROJECT_NAME] | [SHORT_DESCRIPTION] | [TECH] |

---

## GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=[GITHUB_USERNAME]&show_icons=true&hide_border=true" height="150" alt="GitHub stats">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=[GITHUB_USERNAME]&layout=compact&hide_border=true" height="150" alt="Top languages">
</p>
