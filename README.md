# DNSpoofer
DNS (Domain Name System), translates human readable domain names (for example, www.amazon.com) to machine readable IP addresses (for example, 192.0. 2.44).

DNS (Domain Name System) spoofing (a.k.a. DNS cache poisoning) is an attack in which altered DNS records are used to redirect online traffic to a fraudulent website that resembles its intended destination.


```
╭─stagefright@Aspire ~/Projects/DNSpoofer_Py ‹main*› 
╰─$ sudo python3.6 Dnspoof.py

██████╗░███╗░░██╗░██████╗██████╗░░█████╗░░█████╗░███████╗░░░██████╗░██╗░░░██╗
██╔══██╗████╗░██║██╔════╝██╔══██╗██╔══██╗██╔══██╗██╔════╝░░░██╔══██╗╚██╗░██╔╝
██║░░██║██╔██╗██║╚█████╗░██████╔╝██║░░██║██║░░██║█████╗░░░░░██████╔╝░╚████╔╝░
██║░░██║██║╚████║░╚═══██╗██╔═══╝░██║░░██║██║░░██║██╔══╝░░░░░██╔═══╝░░░╚██╔╝░░
██████╔╝██║░╚███║██████╔╝██║░░░░░╚█████╔╝╚█████╔╝██║░░░░░██╗██║░░░░░░░░██║░░░
╚═════╝░╚═╝░░╚══╝╚═════╝░╚═╝░░░░░░╚════╝░░╚════╝░╚═╝░░░░░╚═╝╚═╝░░░░░░░░╚═╝░░░

What website do you want to spoof? > http://www.vulnweb.com/

What IP address do you want to spoof it as? > https://google.com

[+] Starting to spoof...
^C
Exitting...
```

# Running

> Install python and git

* Install pyenv from https://github.com/pyenv/pyenv-installer

* Install python 3.6 from pyenv because netfilterqueue does not support 3.6 < python.

> Clone git repository
```
git clone https://github.com/Stagefright071/DNSpoofer_Py
```

> Install script requirements
```
sudo python3.6 -m pip install -r requirements.txt
```

> Run the script as **root**
```
sudo python3.6 ArpSpoof.py
```

# Thanks!