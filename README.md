# `deb-harden-audit`

## Overview



## Requires

* auditd

## Hardening Applied



## Directory Structure



## User Management



## Verification



## Build Package

### Get Package Building Requirements

```bash
apt update && apt install devscripts
```

### `.deb` Packaging

Build the package using the included build script or using debuild directly:

```bash
./build.sh

# Or by using debuild directly
cd package && debuild -us -uc -b
```
