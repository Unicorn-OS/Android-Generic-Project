# Solution:
# Works:
in Grub for 'virgil/Hw acceleration
Add at end of `linux ... $@`:

```
video=1920x1080
```

## Edit grub file to permanently
Grub, select: Debugging -> debugging

then:
```
nano /mnt/boot/grub/android.cfg
```

under first entry: `function add_boot_entry { linux $kd/kernel ... $src $@ }`
add `video=1920x1080` at end.

type `exit` twice. Then reboot VM.

## Boot with virgl drivers
on next bootup — In Grub, Select:  
"VM Options" -> - "QEMU/KVM - Virgl - SW-FFMPEG"

prime.:
- https://android.stackexchange.com/questions/249223/how-can-i-set-my-android-x86-uefi-installation-resolution-to-19201080-in-my-vm
- https://www.reddit.com/r/BlissOS/comments/s8nlw5/screen_resolution_in_a_vm/

## Android Settings: Display size and text
change: "Display size - Make everything bigger or smaller"
