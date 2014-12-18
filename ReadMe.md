# BGU VPN - ReadMe File

Connect with vpn on macintosh systems

created by [Dor Amir].


## Installation
Open your terminal and go to the folder location.
Write this line:
```sh
sudo chmod +x install.sh
```
enter your computer password

and run the file
```sh
./install.sh
```
this will install the snx file in your system
**it's important to do it first!**

### Getting started

open the file 'startvpn.sh' with any text editor
and change this line:
```sh
/usr/bin/snx -s vpn.bgu.ac.il -u your_username@vpn
```
**write your BGU username where 'your_username' is.**

now Save and Close.

##Start VPN connection
Double click on 'startvpn.sh'

*make sure that it's defualt running program is your terminal and not anthoer one like xCode.*

you will see something like this:

![alt tag](http://s9.postimg.org/u5q1355bj/Screen_Shot_2014_12_18_at_18_01_46.png)

enter your PIN code and your Token code and click Enter.

*note: it will seem like you are not writing but it's ok*

You are connect to the BGU network now! ***Have Fun!***

##Stop VPN connection
Double click on 'stopvpn.sh'

*make sure that it's defualt running program is your terminal and not anthoer one like xCode.*

You are disconnected now!

[Dor Amir]:amirdor@gmail.com

