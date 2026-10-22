# Testing with GNOME Boxes

_Prerequisites_

- A Linux-based operating system

- A host machine with preferably 4 GB RAM and 2 or more CPU cores

---

0. First things first, install Boxes if you don't already have it installed. Select your distribution family below to paste the command into your host's terminal:

**Ubuntu / Debian / Linux Mint / Pop!_OS:**

sudo apt update && sudo apt install -y gnome-boxes


**Fedora / RHEL / AlmaLinux / Rocky Linux:**

sudo dnf install -y gnome-boxes


**Arch Linux / Manjaro / EndeavourOS:**

sudo pacman -S gnome-boxes


**openSUSE (Tumbleweed / Leap):**

sudo zypper install gnome-boxes


**Universal Package (Flatpak):**

flatpak install flathub org.gnome.Boxes

--- 

1. Launch Boxes and click + (Create / New Virtual Machine).

---

2. Select Express Installation or Select File and choose bergos-retro-v1.0-i386.iso.

---

3. Configure the virtual machine resources:

- Name: bergos-retro-v1

- Memory: 1.0 GiB (runs smoothly even with 512 MiB)

- Storage Limit: 10.0 GiB

<img width="555" height="506" alt="Schermata_20261022_153402" src="https://github.com/user-attachments/assets/d9b67788-f733-43af-9938-4b03240abe79" />


---

4. Click Create to launch the Live session.

---

5. Once booted, select Boot BergOS Retro (Live Session) from the menu to enter the IceWM desktop automatically.

*Wait a couple of seconds and the desktop environment should boot right up.*

<img width="1255" height="789" alt="Schermata_20261022_153445" src="https://github.com/user-attachments/assets/d69bdda7-92d5-4d09-975f-d37b6f6fc6e1" />


---

6. To install BergOS Retro, click on the Start Menu, select the "System" folder and choose the "Install Debian" option.

<img width="1253" height="942" alt="Schermata_20261022_153527" src="https://github.com/user-attachments/assets/e9fa4c52-a55f-4dcc-866d-2fca6b37a26c" />


---

7. Last but not least, enjoy!
