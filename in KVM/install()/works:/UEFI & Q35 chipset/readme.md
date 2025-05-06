When partitioning, make a single large partition leaving 5 GB "empty space" at the start of disk!

# KVM setting:
```
OS profile: Andrroid-x86 9.0
firmware: UEFI
chipset: Q35
disk bus: SATA || VirtIO
display.spice server.listen type = None
display.spice server.OpenGL = True
video.model = Virtio
video.3D acceleration = True
```
