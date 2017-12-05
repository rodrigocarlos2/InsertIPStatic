# Insert IP Static on Linux

* The IP is no Static IP and No Internet Connection.

* It's necessary configure the Static IP in server.

* Run the commands:

* nano /etc/network/interfaces

* Insert the text:

> auto eth0
<br>
> iface eth0 inet static
<br>
> address 10.180.20.2
<br>
> gateway 10.180.20.1
<br>
> netmask 255.255.255.252

* After it, make the command:

* service networking restart

# Credits

* Rodrigo Leal
