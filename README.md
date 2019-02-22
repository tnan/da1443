# da1443
<b>Screen</b><br>
yum -y install screen && screen<br>

<b>Auto</b><br>
wget https://github.com/tnan/da1443/raw/master/da1443-en.sh && chmod +x da1443-en.sh && printf 'services_es60_64.tar.gz\ny\n123\n1234\nXXX.XXX.XXX.XXX\ny\neth0\nXXX.XXX.XXX.XXX\ny\n4\ny\ny\n' | ./da1443-en.sh 2>&1|tee directadmin_install.log<br>

<b>Manual</b><br>
wget https://github.com/tnan/da1443/raw/master/da1443-en.sh<br>
chmod +x da1443-en.sh<br>
./da1443-en.sh 2>&1|tee directadmin_install.log<br>

XXX.XXX.XXX.XXX = IP Address
