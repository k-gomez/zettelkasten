---
date: 2022-03-02T08:30
tags:
  - tesla
  - analysis
  - linux
---

# Busybox

Tesla uses the busybox binary in their autopilot. This binary is pretty small and implements different common Linux commands (e.g. `cat`, `ls`, ...).

Based on the analysis of the 2016 os-release from the Tesla autopilot, the busybox binary is located in the `bin` folder.

This could be used in [[db8ec17f]] of the collected data.
