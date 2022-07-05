# Guide for installing RPM packages on Debian/Ubuntu

Based on comment here: https://github.com/apptainer/singularity/issues/5390#issuecomment-899111181

## Required Software:
- Alien (apt install alien)

## Process:
1. Download rpm: `wget https://.../[package].rpm`
2. Convert rpm: `sudo alien -d [package].rpm`
3. Install deb: `sudo apt-get install ./[package].rpm`

## Packages Converted
1. Singularity: `https://dl.fedoraproject.org/pub/epel/8/Everything/x86_64/Packages/s/singularity-3.8.7-1.el8.x86_64.rpm`

