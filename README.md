# secubian-livecd
This is a light linux iso used to acquire artefact during cybersecurity incident.

Based on Debian and generate with "Live build" tool.


## Requirements

```
# Packages installation
sudo apt install git-core live-build

# Retrieve repository
git clone https://github.com/kidrek/secubian-livecd.git
cd secubian-livecd

# ISO Generation
sudo lb build
```

## Usage

1. Boot on ISO 
2. Mount your backup storage to store the acquired disk
3. Select ```guymager``` and launch acquisition

You can also use terminal and launch acquisition manually with ```dd````
