---
date: 2022-02-06T18:31
tags:
  - profile
  - characteristic
  - fingerprint
---

# KDBGScan

KDBG structure to determine OS.

[[0dc8d333]] scans for "_KDDEBUGGER_DATA64" by looking for constant values embedded in the structure. It includes the hard-coded 4-byte signature of KDBG.
KDGB is used by kernel debugger to find active processes, handles to objects, loaded modules, etc.
