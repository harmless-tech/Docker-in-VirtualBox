# Docker-in-VirtualBox

## For Windows
### 1. Install VirtualBox.
- https://www.virtualbox.org/wiki/Downloads
- [Make sure to have virtualization enabled in the bios.](https://www.howtogeek.com/213795/how-to-enable-intel-vt-x-in-your-computers-bios-or-uefi-firmware/)

### 2. Install Docker Desktop.
- https://www.docker.com/products/docker-desktop
- Make sure to disable Docker Desktop on startup.
- Ignore the warning about containers and hyper-v.
- Quit Docker Desktop from the taskbar.

### 3. Create a Docker Machine in VirtualBox.
- Run the command ```docker-machine create --driver=virtualbox Docker```
- Make sure to allow it to create a network adapter.

### 4. Once it finishes you now have a Docker Machine in VirtualBox.

## Accessing the Docker Machine.
### 1. Download the docker vm scripts and add them to your path.
- Run ```dvm-start``` to start the dvm.
- Run ```dvm-restart``` to restart the dvm.
- Run ```dvm-stop``` to stop the dvm.
- Run ```dvm``` in cmd to add the dvm variables.
- Run ```dvmp``` in powrshell to add the dvm variables.
- Run ```dvm-cmd``` to open cmd with the dvm variables.
- Run ```dvm-pshell``` to open powershell with the dvm variables.

## Port Forwarding