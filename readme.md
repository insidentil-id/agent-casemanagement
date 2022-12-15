## Requirement
Check to Network Administrator to Open Port 9000, 9042, 9200, 9001

## Pre-install
sudo apt get update<br>
sudo apt install git

## Running As Super User
sudo su

## Clone Repository
git clone https://github.com/insidentil-id/agent-casemanagement<br>
sudo chmod 777 -R agent-casemanagement<br>
cd agent-casemanagement<br>
chmod u+x docker-install.sh<br>
./docker-install.sh<br>
docker compose up -d

## Running Docker When Machine Restart
sudo chmod 666 /var/run/docker.sock


## Login
http://IP:9000<br>
Default admin credentials are admin@thehive.local / secret


## Credit
Script By Cyber Threat Hunting Team<br>
Direktorat Operasi Keamanan Siber<br>
Special Thanks to Team: maNDayUGIikHSanNaLonAldAvIDSUBkHAnREndRAalSItAdAFi