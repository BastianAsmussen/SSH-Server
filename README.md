# Arch Linux SSH Server
## How To Install:
1. Make sure `git` is installed.
```bash
sudo pacman -S git
```

2. Clone the repository.
```bash
git clone https://github.com/BastianAsmussen/SSH-Server
```

3. Change directory.
```bash
cd SSH-Server
```

4. Review the configuration files and make changes if necessary.
```bash
nano ssh/sshd_config
nano fail2ban/jail.local
```

5. Make the install script executable.
```bash
sudo chmod +x mk-ssh
```

6. Run the install script as root.
```bash
sudo ./mk-ssh
```
