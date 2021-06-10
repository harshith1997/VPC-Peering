##<font color =red> Is it possible to access the resources in other VPC, in same accout or differnt account/Region ??</font>

![Capture1](https://user-images.githubusercontent.com/28533352/121317539-05e99100-c928-11eb-9407-6467dd379036.PNG)

**YES** 


#  VPC Peering

Vpc peering is the network connection between 2 VPC's which enables us to route the traffic between 2 VPC's using private IPV4/IPV6 address

Establishing the peering relationship between 2 vpc in the different region is called inter-region vpc peering

![interregionvpc](https://user-images.githubusercontent.com/28533352/121317661-24e82300-c928-11eb-8ccc-4db62df6de28.PNG)

Al traffic reamains in the Private IP's

Steps Between Requester and Acceptor VPC

![VPCPEERINGSTEPS](https://user-images.githubusercontent.com/28533352/121318830-3da50880-c929-11eb-82b1-d87e0ace55cb.PNG)


Life Cycle

![Lifecycle](https://user-images.githubusercontent.com/28533352/121322688-d2f5cc00-c92c-11eb-9b1d-15df1d4c62af.PNG)

Multiple VPC Peering Connection

It is one to one relation between 2 vpc
- case 1: There is no support for the transitive relationship or connections between VPC
(a->b->c) -> (a->~c)

![TRANSITIVEPEERING](https://user-images.githubusercontent.com/28533352/121323834-c9209880-c92d-11eb-92e3-858d8e74a5cb.PNG)

- case 2

![corporate](https://user-images.githubusercontent.com/28533352/121324633-87442200-c92e-11eb-860d-3d9a38be32ae.PNG)

-case 3 

![internetgateway](https://user-images.githubusercontent.com/28533352/121324777-ac389500-c92e-11eb-8cd8-17ad495f86de.PNG)

-case 4

![AMAZONS3](https://user-images.githubusercontent.com/28533352/121325079-ef930380-c92e-11eb-8bc5-532e4b0dda45.PNG)

