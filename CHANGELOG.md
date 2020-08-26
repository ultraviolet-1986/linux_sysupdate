# sysupdate Changelog

## Table of Contents

- [0.1.x Series](#01x-series)

## 0.1.x Series

### 0.1.7 Currently in Development

- Included support for `yum`, this is to allow usage of this program on legacy
  RHEL or CentOS systems (<= 7.x).

### 0.1.6 Released Thursday 20th August 2020

- Corrected program return codes to verify program exit status. This status can
  be checked on the BASH (or compatible) shell using this command: `echo $?`.
- Corrected text colour declarations by placing them within the
  `update_software.h` header file.
- Removed redundant code which detects a non-GNU/Linux system and prevents
  execution.