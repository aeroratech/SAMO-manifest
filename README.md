# SAMO Camera Manifest

This repository contains the `repo` manifest for the SAMO camera  project.

## Download the Source Code

1. Create the SAMO workspace:

   ```bash
   mkdir SAMO
   ```

2. Extract the **proprietary** components into the workspace:

   ```bash
   tar -xJf proprietary.tar.xz -C ./SAMO/
   ```

3. Enter the workspace, initialize, and synchronize the source tree:

   ```bash
   cd SAMO
   repo init -u https://github.com/aeroratech/SAMO-manifest.git -b main -m SAMO.xml
   repo sync -j "$(nproc)"
   ```

## Build Instructions

### Build Environment Requirements

- Operating system: Ubuntu 22.04
- Memory: at least 32 GB RAM
- Storage: at least 200 GB of available disk space

TODO
