# Gtech Assistant: releases

Golden Technologies' own assistant for Windows: the week's schedule and meetings, payments to make, documents such as
the tax clearance (read, kept locked, reminded before they expire), tasks, and School Assist's licences.

This repository holds only the installers and the signed update files. Installed copies check here for updates and
install them by themselves.

* **Download:** the [latest release](https://github.com/Kim-G7/Gtech-Assistant-releases/releases/latest), file
  `Gtech-Assistant-Setup-<version>.exe`. It installs for the current Windows user (no administrator needed).
* **Who can use it:** only Golden Technologies' admin account (a password and an authenticator app). A copy without
  that account opens on its sign-in screen and nothing else.
* **Updates are signed:** each release has `update.json` (version, file, size, SHA-512) signed with Golden
  Technologies' update key (Ed25519). An installed copy only takes an installer whose signature and hash check out.
