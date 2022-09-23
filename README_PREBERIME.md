# Windows_10_11_Hosts
Windows10/11 Block Malware Sites hosts

Zaščita vašega omrežja bodisi osebnega računalnika ali serverja preko hosts datoteke ali direktno žive liste IP preko vašega požarnega zida Windows FireWall ali Linux

Žival lista slabih omrežij se dobi direktno na naših EU-US-RU strežnikih in po novem od leta 2020 privat VPN/VPS HTU-SRV-66-SI-EU Lucija - Slovenija - domene:
perc.ddns.net  
pcsnet.myftp.org  
oglasi.hopto.org  
obala.hopto.org  
piramide.zapto.org  
pcs.sytes.net

Navodila za uporabo Windows Hosts datoteke:
Najlažja varianta je da si poberete hosts datoteko npr. preko drugih ponudnikov primer:

* https://github.com/topics/hosts

* https://winhelp2002.mvps.org/hosts.htm
* https://github.com/StevenBlack/hosts
* https://github.com/BorisPerc/Windows_10_11_Hosts/
ipd...

Za integrirat blok listo v vaš Windows enostavno odprete datoteko kot administrator v mapi:
c:\Windows\System32\drivers\etc\hosts

Vključite po vaši izbiri vse blokade tako da kopirate v to datoteko \Windows\System32\drivers\etc\hosts vse hoste ki jih hočete blokirati

V požarni zid Windows 10/11 in starejše različite, si lahko dodate poglejte navodila:
Živo listo slabih ipjev si lahko dnevno poberete preko URL:
https://piramide.zapto.org/iplist-pcsnet.txt
ali fiksna lista slabih ip preko URL:
https://piramide.zapto.org/iplist.txt
Za integracijo IP naslovov v vaš Widnows požarni zdi sem vam pripravil skript katerega lahko poberete:
https://github.com/BorisPerc/windowsblockit
Vse IPje oz. slaba omrežja, priporočam doma v kolikor vaši otroci uporabljajo isti računalnik ali imajo svojega, da jim blokirate vse nezaželene strani 
ali socialna omrežja katera nimajo nobenih poučnih funkcionalnosti in so po večini vsa škodljiva za vaše otroke.

Blokado izvrište preko hosts datoteke tako npr. FaceBook blokada:
0.0.0.0 facebook.com
0.0.0.0 www.facebook.com
itd....


