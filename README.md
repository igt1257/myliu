/Users/louis/Library/Rime <BR>
<BR>

#Raspberrypi <BR>
root@raspberrypi:# apt-get install ibus-rime <BR> 
root@raspberrypi:# curl -fsSL https://git.io/rime-install | bash <BR>
root@raspberrypi:# cd /root/plum/ <BR>
root@raspberrypi:# bash rime-install bopomofo <BR>

pi@raspberrypi:$ wget https://github.com/igt1257/myliu/archive/refs/heads/main.zip <BR>
pi@raspberrypi:~ $ unzip main.zip <BR>
pi@raspberrypi:~ $ mv myliu-main/* /home/pi/.config/ibus/rime/ <BR>
pi@raspberrypi:$ ls -l /home/pi/.config/ibus/rime <BR>
Preferences > IBus Preferences > Input Method > Add > Chinese > Rime
