# Basic Shell Commands

## Where am I?

### whoami
Shows the current logged-in username

**When to use:**
- Check if you're logged into the correct account
- Verify user identity in scripts
- Quick confirmation of current user

```bash
whoami
```
**Example Output:**
```
Ubuntu
```
### pwd - Print Working Directory
Shows where you are in a directory/ folder

**When to use:**
- To check current folder
- Crucial before executing other commands.
- If debugging issue regarding file path.

```bash
pwd
```
**Example output:**
```
/home/ubuntu
```
### hostname
shows the computer name

**When to use:**
- To see your computer's name.
- To customize temp or permenantly.
- To identify your system on a network.

```bash 
hostname #To view your computer name
sudo hostname new-username #to change temp (until reboot)
sudo hostnamectl set-hostname new-username #to change permanently.
```
**Example output:**
```
Ubuntu
```
**Self-Notes:**
- **Sudo** stands for *superuser do* , it lets you run as an administrator (root user). Many system-level commands require special permission. If not added you'll get an error as *permission denied*.
- **ctl** stands for control. Usually used for managing a system componenet.

| Command       | Meaning                                                      |
| ------------- | ------------------------------------------------------------ |
| `hostnamectl` | Control/manage the system's hostname                         |
| `systemctl`   | Control/manage system services (like starting/stopping apps) |
| `timedatectl` | Control the system’s date and time settings                  |
| `localectl`   | Control system locale and keyboard layout                    |


### uname -Unix name
used to show what unix system you are using.

```bash
uname
```
**Example output:**
```
Linux
```
**Other options:**
| Command    | What it shows                                    |
| ---------- | ------------------------------------------------ |
| `uname -a` | All system info (kernel, OS, machine type, etc.) |
| `uname -r` | Kernel version                                   |
| `uname -n` | Network hostname (same as `hostname`)            |
| `uname -m` | Machine hardware name (e.g., `x86_64`)           |
| `uname -s` | Kernel name                                      |
| `uname -v` | Kernel version string                            |



