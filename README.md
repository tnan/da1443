# da1443
yum -y install screen && screen && wget https://github.com/tnan/da1443/raw/master/da1443-en.sh && chmod +x da1443-en.sh && printf 'services_es60_64.tar.gz\ny\n123\n1234\nXXX.XXX.XXX.XXX\ny\neth0\nXXX.XXX.XXX.XXX\ny\n4\ny\ny\n' | ./da1443-en.sh 2>&1|tee directadmin_install.log
