# Verilog-code-for-NoC-
Reconfigurable NoC verilog code 
This NoC module consists of an array of router
 modules, an array of link modules, and an array 
of node modules. The router modules are 
responsible for routing packets through 
the NoC, the link modules represent the 
physical communication links between routers, 
and the node modules represent the endpoints
 of the NoC, where packets are either
 transmitted or received.

The NoC module also includes code to connect 
the different modules together and to expose
 the necessary input and output ports.

The router modules are connected to the link
 modules by connecting the output ports of
 the routers to the input ports of the links, 
and the output ports of the links to the 
input ports of the routers. This allows 
the routers to transmit packets to other 
routers through the links.

The node modules are connected to the router
 modules by connecting the output ports of 
the nodes to the input ports of the routers, 
and the output ports of the routers to the
 input ports of the nodes. This allows the 
nodes to transmit packets to and receive
packets from the routers.
