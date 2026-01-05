/Users/louis/Library/Rime <BR>
<BR>

#Raspberrypi <BR>
root@raspberrypi:# apt-get install ibus-rime <BR> 
root@raspberrypi:# curl -fsSL https://git.io/rime-install | bash <BR>
root@raspberrypi:# cd /root/plum/ <BR>
root@raspberrypi:# bash rime-install bopomofo <BR>
<BR>
  
pi@raspberrypi:$ wget https://github.com/igt1257/myliu/archive/refs/heads/main.zip <BR>
pi@raspberrypi:~ $ unzip main.zip <BR>
pi@raspberrypi:~ $ mv myliu-main/* /home/pi/.config/ibus/rime/ <BR>
pi@raspberrypi:$ ls -l /home/pi/.config/ibus/rime <BR>
<BR>

Preferences > IBus Preferences > Input Method > Add > Chinese > Rime<BR>






#Ubuntu <BR>
louis@ubunt22:~$ sudo su -
root@ubunt22:~# apt-get install ibus-rime
root@ubunt22:~# curl -fsSL https://git.io/rime-install | bash
root@ubunt22:~# cd /root/plum/
root@ubunt22:~# bash rime-install bopomofo

louis@ubunt22:~$ wget https://github.com/igt1257/myliu/archive/refs/heads/main.zip
louis@ubunt22:~$ unzip main.zip
louis@ubunt22:~$ mv myliu-main/* /home/louis/.config/ibus/rime/
louis@ubunt22:~$ ls -l /home/louis/.config/ibus/rime

#無蝦米
Settings > Keyboard > Input Sources > + > Chinese(Taiwan) > Chinese(Rime)

#注音
Settings > Keyboard > Input Sources > + > Chinese(Taiwan) > Chinese(Chewing)
