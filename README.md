# secubian-livecd
This is a light linux iso used to acquire artefact during cybersecurity incident.

Based on Debian and generated with "Live build" tool.

## Requirements

```
# Packages installation
sudo apt install git-core live-build

# Retrieve repository
git clone https://github.com/kidrek/secubian-livecd.git
cd secubian-livecd

# ISO Generation
sudo lb build

# Send ISO to USB key
dd if=CERT-Forensic_live_system-amd64.hybrid.iso of=/dev/sd{b-z}
```


It's possible to add data partition in ISO.
Thanks to lange@debian.org for this script : ```mk-data-parition```
Source : https://raw.githubusercontent.com/faiproject/fai/refs/heads/master/bin/mk-data-partition


## Usage

1. Boot on ISO 
2. Mount your backup storage to store the acquired disk
3. Select ```guymager``` and launch acquisition

You can also use terminal and launch acquisition manually with ```dd```
