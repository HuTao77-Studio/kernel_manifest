## 1. Initializing Repo ##
```bash
# Create a directory for the source files
# This can be located anywhere (as long as the fs is case-sensitive)
$ mkdir oneplus-kernel
$ cd oneplus-kernel

# Install Repo in the created directory
$ repo init -u https://github.com/HuTao77-Studio/kernel_manifest.git -b oneplus/sm8650_u_14.1.0_oneplus_ace3pro --depth=1
```
```bash
# Let Repo take care of all the hard work
$ repo sync
```
