# c-195
Router is a device used to connect to the internet. And
nowadays the device which we have at our homes is a
combination of switch and router. Because it can connect
multiple devices with it such as mobile, laptop, computers
etc. And it also connects us with the internet.
-----------------------------------------
if we
want to connect multiple switches together then we need a
router.
—————————————————————


 instead of manually selecting the cable let’s click on
the automatic selection.
This will choose the best cable according to the device and
connect it to the appropriate port.
Which in our case is a fast Ethernet port.
Our switch and PC both have this port.PC only has 1
FastEthernet port but switch has multiple ethernet ports

--------------------------------------------------------------

create 1st local area networks with switch
create 2nd local area network with switch

Next step is to connect the Router with Switch.
The cable needed for this connection is also copper
straight through.

But the port will be different on the router.
Our switch has the Fast Ethernet Port as well as Gigabit
Ethernet port.

But router has only Gigabit Ethernet port
Difference between these 2 ports is that gigabit Ethernet is
faster than fast ethernet.

The maximum speed of data transmission on fast Ethernet
is 100 MBPS but on the gigabit port it is 1000MBPS.
But there are other differences also such as gigabit is
costly and it can be used to transmit data over long
range(upto 70 km).
But fast ethernet can transmit over short distances only
upto 10 KM.

In order to connect the 2 devices select the copper straight
through cable and click on the switch. Here select the
Gigabit port.
——————————————————

There are 2 steps we need to perform in order to bring the
router online.
First is by default the port of the router is turned off.
We need to turn that On.
For that double click on the router and go to the config tab
and then in the bottom left select the gigabit 0 port.
Here you have the option to turn it on

Check the on option.
In the second setup we need to assign the IP address to
this port as well. Important note is that this IP address
should be in range of the IP of our LAN.
For example the IP address for the computers are 10.0.0.1
to 10.0.0.3
SO the IP should be something like 10.0.0.4 We can
choose the last number of our own.

————————————————————————

And here we can see that our first data packet failed but
rest 3 came through.
This is very common when we set up the network. We lose
the data packet on our first ping.
So let’s ping one more time to see if everything is working
fine or not.

——————————————
And here we can see that our first data packet failed but
rest 3 came through.
This is very common when we set up the network. We lose
the data packet on our first ping.
So let’s ping one more time to see if everything is working
fine or not.
On our second ping we can see that all the packets are
sent and received. It means our network is working fine.
What we have created here is a Wide Area Network. If we
connect a lot of networks like this we will have something
called as INTERNET

—————————

In this we have learned how to set up a router and connect
multiple LAN’s with it.
We also learned about the default gateway and how it
plays an important role in connecting the computer to the
internet
