# DDOS-on-Ubuntu-VM
This project is designed to launch a Distributed Denial of Service (DDoS) attack on a
Mininet virtual network using a Floodlight topology, detect the attack using Floodlight, and
graph the resulting traffic flow via sFlow. Mininet is used on a Ubuntu virtual machine in order to
quickly create a virtual network, with Floodlight being used to quickly generate the topology for
the network. A DDoS attack simulation is then generated by using terminal commands which
will flood the network with undesired and useless traffic. The attack will be identified and
prevented using the existing features of Floodlight, while sFlow keeps a running graphical log of
the traffic experienced by the network.
