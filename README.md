# snap for nvme-z app


<h1 align="center">
  <img src="https://nvme-z.tech/logo-512-fit.png" alt="nvme-z" width="50%">
</h1>

<p align="center"><b>NVMe-Z, Your NVMe SSD’s Health & Upgrade Zen!</b>. 
<p align="center">NVMe-z is a user-friendly application for viewing detailed information about NVMe storage devices on your system. It provides an intuitive interface to display device health, capabilities, and status, making it easy to monitor and recommends upgrade for best performance.</p>

<p align="center"><i>Ideal for both enthusiasts and professionals, NVMe-z helps you keep track of your storage hardware with clarity and ease.</i></p>

<p align="center">
<a href="https://snapcraft.io/nvme-z">
  <img alt="nvme-z" src="https://snapcraft.io/nvme-z/badge.svg" />
</a>
</p>

## Install

```shell
snap install nvme-z
```

## Snap configuration

Snaps are confined, as such NVMe-Z may be unable to perform some of the tasks it typically does when unconfined. 
  This may result in the system log getting spammed with apparmor errors. 
  Granting access to the hardware-observe interface when in the snap will enable the features, and thus improve user experience.

```shell
snap connect nvme-z:hardware-observe
```

<iframe title="Publicise card" src="https://snapcraft.io/nvme-z/embedded?button=black&channels=true&summary=true&screenshot=true" style="width: 100%; height: 100%; border: 1px solid #CCC; border-radius: 2px;"></iframe>