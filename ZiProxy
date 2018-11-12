#/bin/bash

echo -e "\ 033 [1; 33m- - - - -> \ 033 [01; 34m Iniciou a configuracao do ZiProxy, Porta 8080 CONNECT"
echo -e "\ 033 [1; 33m #################"
sleep 3

apt-get update -y
clear
apt-get upgrade -y
clear
apt-get install ziproxy -y
clear

cd /etc/ziproxy/
mv ziproxy.conf ziproxy.conf1
wget https://raw.githubusercontent.com/Guilhermezkz/mytest/master/ziproxy.conf
/etc/init.d/ziproxy restart
clear

echo -e "\ 033 [1; 31mCANAL @PayloadHTTP"
echo -e "\ 033 [1; 31mBy: LindoFuLL"
echo -e "\ 033 [1; 31mPronto"
