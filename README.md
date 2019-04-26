# Zram

Download the script and copy to /usr/bin/ folder
> sudo wget -O /usr/bin/zram.sh https://raw.githubusercontent.com/ALAS/zram/master/zram.sh

Making The File Executable
> sudo chmod +x /usr/bin/zram.sh

Edit /etc/rc.local File To Run Zram Script On Startup
> sudo nano /etc/rc.local

Add This Line Before exit 0
> /usr/bin/zram.sh &
