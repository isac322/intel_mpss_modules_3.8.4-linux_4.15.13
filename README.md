# intel_mpss_modules_3.8.4 - linux_4.15.13
Custom patch for Linux 4.15.13 (probably and below)

# Build and install

```bash
make MIC_CARD_ARCH=k1om -j 64
sudo make install

sudo depmod
sudo modprobe mic
```
