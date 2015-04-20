This directory contains dockerfiles to build images for various Rust compiler configurations to allow compiling rust binaries on the various available linux hosts.

Docker is used to ease using a virtual machine and get linux x64 builds done for various distributions.

# Using Make

Make is setup with a single target in each leaf-directory. To build an appropriately named image, use
```bash
make image
```
