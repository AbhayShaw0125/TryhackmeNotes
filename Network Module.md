Devices on networks are similar to human :
Human can be recognized via : 
1. Name
2. Fingerprint

We can change our name via deed poll but we can't change our fingerprints.
Similarly devices also have two means of identification:
1. MAC address 
2. IP address 


### **IP Address**
An IP address can be used to identify a host on a network for a period of time, where that IP address can be associated to another device without the IP address changing.
![](attachment/e304571b2c110294336fb9e07e42e054.png)

[NOTE]

IP Address can change from device to device but cannot be active simultaneously more than once within same network

IP address follow a set of standards called **protocol**

- A public IP address is used to identify a device on the internet while a private IP address is used to identify a device amongst other devices.
![](attachment/6490c926721ef97446ea81b74f1b9ca5.png)
MAC Address
Devices on  a network will have a physical network interface ,a microchip board found on the device motherboard.
This network interface is assigned  a unique address at factory it is built called **MAC address.**

MAC ADDRESS: It is a 12 digit hexadecimal number split into two's seperated by colons.
![](attachment/1e9f1f92eae8db31835b194b67e7cf5c.png)


## Ping
Ping is a tool .
It uses ICMP (Internet Control Message Protocol) packets to determine the performance of a connection between two devices whether the connection exists or  is reliable.

1. The time taken by ICMP packets travelling between devices is measured by ping.
2. The measuring is done through ICMP echo packet and ICMP echo reply from target device
![](attachment/fa1059837abd79dd8b97778d862fc3e9.png)

- pinging a device that has the private address of _192.168.1.254_
- Ping informs us that we have sent six ICMP packets, all of which were received with an average time of 4.16 milliseconds.