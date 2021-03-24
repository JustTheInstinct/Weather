# Installation Instruction:
Assuming that the client is on Linux and currently on their home directory:
1. Place the weather.sh file into "/home/vagrant" directory
2. Place the weathertime.timer file into "/etc/systemd/system" directory
3. Place the weather.service file into "/etc/systemd/system" directory
4. Run "sudo systemctl enable weather" while in "home/vagrant" directory

Note: Weather should be displayed every hour when journalctl is ran
