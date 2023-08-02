# Lession 16

<h3> Network configuration </h3>

The ifconfig command stands for "interface configuration" and is used to display network configuration information.

<span> Syntax: <br> <code> ifconfig [options] </code> </span>

<h4> Note </h4> 
The iwconfig command is similar to the ifconfig command, but it is dedicated to wireless network interfaces.

The lo device is referred to as the loopback device. It is a special network device used by the system when sending network-based data to itself.

The ifconfig command can also be used to temporarily modify network settings. Typically these changes should be permanent, so using the ifconfig command to make such changes is fairly rare.

The ping command is used to verify connectivity between two computers. It does this by sending packets to another machine on a network. If the sender receives a response it should be possible to connect to that machine.

Information is sent using “packets”; the encapsulated unit of data sent over a network. In order for the packets to find the other computer, they will need an address. The ping command uses IP addresses to identify a computer on the network that it wants to connect to.

By default, the ping command will continue sending packets until the break command (CTL + C) is entered at the console. To limit how many pings are sent, use the -c option followed by the number of pings to be sent. The example below shows ping being limited to 4 iterations with -c 4.