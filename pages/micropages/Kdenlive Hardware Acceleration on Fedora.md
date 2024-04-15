# Kdenlive Hardware Acceleration on Fedora
Run the below commands

## Add RPM Fusion FOSS Repository
```sudo dnf install https://mirrors.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm```

```sudo dnf groupupdate core```

## Install Freeworld Drivers
```sudo dnf swap mesa-va-drivers mesa-va-drivers-freeworld```

```sudo dnf swap mesa-vdpau-drivers mesa-vdpau-drivers-freeworld```
