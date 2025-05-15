# Solution:
# Works:
https://android.stackexchange.com/questions/249223/how-can-i-set-my-android-x86-uefi-installation-resolution-to-19201080-in-my-vm

in Grub for 'virgil/Hw acceleration
Add at end of `linux ... $@`:

```
video=1980x1080
```

## Edit grub file to permanently set:
in '/mnt/boot/grub/android.cfg'

## || one time Boot:
In Grub, Hilight:
"VM Options" -> - "QEMU/KVM - Virgl - SW-FFMPEG"

and press e and to edit grub. Add at end of `linux`. and press "Ctrl+x" or "F10"

https://www.reddit.com/r/BlissOS/comments/s8nlw5/screen_resolution_in_a_vm/
