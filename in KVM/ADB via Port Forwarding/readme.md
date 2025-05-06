quote:
>For adb/usermode networking, I don’t have a NIC setup in virt manager, instead I modified the xml to manually add qemu parameters for the NIC and port forwarding to allow adb connect localhost:4444 to work. I used to use virbr0 for this but now that I discovered this XML magic that eliminates the need for specifying an IP address I don’t see myself going back.
>
>Credit goes to this question 33 and this one 19 for showing me that trick.

https://unix.stackexchange.com/questions/627187/ssh-into-gnome-boxes-os/649326#649326
https://unix.stackexchange.com/questions/350339/how-to-port-forward-ssh-in-virt-manager/519067#519067
