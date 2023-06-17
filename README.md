# libxatracker2
kali 2023.1  Fix  libxatracker2<br>
kali@kali:~$ sudo apt update<br>
kali@kali:~$<br>
kali@kali:~$ sudo apt full-upgrade -y<br>

..............................................
10 upgraded, 0 newly installed, 0 to remove and 641 not upgraded.<br>
Need to get 1,902 kB/24.0 MB of archives.<br>
After this operation, 69.6 kB of additional disk space will be used.<br>
Do you want to continue? [Y/n] y<br>
Ign:1 http://http.kali.org/kali kali-rolling/main amd64 libxatracker2 amd64 22.3.6-1+deb12u1<br>
Ign:1 http://http.kali.org/kali kali-rolling/main amd64 libxatracker2 amd64 22.3.6-1+deb12u1<br>
Ign:1 http://http.kali.org/kali kali-rolling/main amd64 libxatracker2 amd64 22.3.6-1+deb12u1<br>
Err:1 http://http.kali.org/kali kali-rolling/main amd64 libxatracker2 amd64 22.3.6-1+deb12u1<br>
  Connection failed [IP: 192.99.200.113 80]<br>
E: Failed to fetch http://http.kali.org/kali/pool/main/m/mesa/libxatracker2_22.3.6-1%2bdeb12u1_amd64.deb  Connection failed [IP: 192.99.200.113 80]<br>
E: Unable to fetch some archives, maybe run apt-get update or try with --fix-missing?<br>
<br>
kali@kali:~$<br>
kali@kali:~$ wget https://the.earth.li/debian/pool/main/m/mesa/libxatracker2_22.3.6-1+deb12u1_amd64.deb<br>
kali@kali:~$ sudo dpkg -i libxatracker2_22.3.6-1+deb12u1_amd64.deb<br>
kali@kali:~$ sudo apt full-upgrade -y<br>

or <br>
https://github.com/sec13b/libxatracker2/raw/main/libxatracker2_22.3.6.deb<br>
