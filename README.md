# Installation Instruction:
Assuming that the client is on Linux and currently on their home directory:
1. Pull files from master branch
2. Place the weather.sh file into "/home/vagrant" directory
3. Place the weathertime.timer file into "/etc/systemd/system" directory
4. Place the weather.service file into "/etc/systemd/system" directory
5. Run "sudo systemctl enable weather" while in "home/vagrant" directory

Note: Weather should be displayed every hour when journalctl command is executed
