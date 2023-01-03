# OS-Tutorial
Create the iso file using docker image with this command
```make build-x86_64```
then emulate the OS using qemu with this command
```qemu-system-x86_64 -cdrom dist/x86_64/kernel.iso```
