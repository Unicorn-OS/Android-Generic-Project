# Solution:
https://android.stackexchange.com/questions/249223/how-can-i-set-my-android-x86-uefi-installation-resolution-to-19201080-in-my-vm

in '/mnt/boot/grub/android.cfg':

add:
```
nomodeset video=1980*1080
```

# Try:
https://www.reddit.com/r/BlissOS/comments/s8nlw5/screen_resolution_in_a_vm/
