# Install Nessus on Ubuntu with ARM.

```
1) Download the Nessus binary for AARCH64 -> RPM file.
2) Install alien
apt update; apt install alien -y;
alien nessus.rpm --target=arm64 --to-deb 
dpkg -i nessus.deb

