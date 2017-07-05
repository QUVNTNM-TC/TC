QUVNTNM TOOLCHAIN
===================================================
This toolchain is optimized for:
- ARM 64
- QCOM KRYO CPU (-mcpu=cortex-a57.cortex-a53 -mtune=cortex-a57.cortex-a53 )
- Hard-float ABI (-mfloat-abi=hard)
- Linux Kernel 3.18.X

This toolchain uses:
- System zlib
- Linaro GCC 8.0 (latest)
- Linaro glibc 2.25.90(latest from git)
- Latest binutils/etc
- Other components specified in ".config" file
