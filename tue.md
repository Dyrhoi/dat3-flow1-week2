# Fundamental Network Topics

Understanding Basic Network Terms like IP, TCP/IP, DNS, DHCP and more.
These exercises are meant to be answered with text, based on internet searches so write down your reply so you will remember for later.

* **What is your public IP address right now, and how did you find it?**  
  Current IP is: 80.xxx.14.xxx \<redacted\>
* **What is your private IP address right now (do this both at home and in school), and who/what gave you that address?**  
   Private IP is 192.168.0.20 and was automatically assigned by my router.
* **What’s special about these address ranges?**
   * 10.0.0.0 – 10.255.255.255
   * 172.16.0.0 – 172.31.255.255 
   * 192.168.0.0 – 192.168.255.255

   All these addresses are within the private ip range. So they can all be used as private IP addresses.
* **What’s special about this ip-address: 127.0.0.1?**  
    This IP is also known as localhost and it points to the own local network.
* **What kind of service would you expect to find on a server using these ports: 22, 23, 25, 53, 80, 443?**  
   * 22: Most commonly used in context of SSH.
   * 23: Used by the telnet protocol.
   * 25: SMTP (Simple Mail Transfer Protocol), used for email routing between mail servers.
   * 53: DNS, domain name system.
   * 80: HTTP.
   * 443: HTTPS.
* **What is the IP address of studypoints.info and how did you find it?**  
    The IP address of studypoints.info is: 157.230.21.145, I used the *ping* windows command to get my result.  
    ![alt text](https://github.com/Dyrhoi/dat3-flow1-week2/blob/master/pictures/studypointsinfo_ping.PNG?raw=true "Usage of windows Ping Command")

* **If you write https://studypoints.info in your browser, how did “it” figure out that it should go to the IP address you discovered above?**  
    The DNS server has the domain name mapped to the IP address, therefore the browser knows where to retrieve the information from.

* **Explain shortly the purpose of an ip-address and a port-number and why we need both**  
   The primary functions of the Internet Protocol are providing identification of computer hosts and straight forward location service.

   A port-number makes it able for a singular host to offer a magnitude of services.

* **What is your (nearest) DNS server?**  
    I will assume it's webspeed.dk, as this is the current DNS I am connected to.

* **What is (conceptually) the DNS system and the purpose with a DNS Server?**  
    The Domain Name System, or DNS, is a globally distributed, scalable, reliable, dynamic database, used to map between hostnames and IP addresses, and to provide electronic mail routing information. 


* **What is your current Gateway, and how did you find it?**  
    192.168.0.1 - Also found within ipconfig command.

* **What is the address of your current DHCP-Server, and how did you find it?**  
    192.168.0.1 - Also found within ipconfig command.

* **Explain (conceptually) about the TCP/IP-protocol stack**
* **Explain about the HTTP Protocol (the following exercises will go much deeper into this protocol)**
* **Explain (conceptually) how HTTP and TCP/IP are connected (what can HTTP do, and where does it fit into TCP/IP)**
#