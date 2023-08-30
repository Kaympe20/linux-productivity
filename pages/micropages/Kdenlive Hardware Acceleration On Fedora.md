# Kdenlive Hardware Acceleration On Fedora
Run The Below Commands
## Add RPM Fusion FOSS Repository
```sudo dnf install https://mirrors.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm```

```sudo dnf groupupdate core```
## Install Freeworld Drivers
```sudo dnf swap mesa-va-drivers mesa-va-drivers-freeworld```

```sudo dnf swap mesa-vdpau-drivers mesa-vdpau-drivers-freeworld```
