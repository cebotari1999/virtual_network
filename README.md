    Subnetting
  
The configuration of virtual network start with subnetting. 
- The address 27.87.0.0/16 was divided into 11 subnets, 9 for VLANs: A, B,..., I and 2 for 
routers connections;
- For all stations have been configured IP, mask, default gateway;
- DNS for stations in Pink zone is IP of server H2, DNS for stations 
in blue zone is IP of server I2;

      Switch ports configuration
    
- Switch - Station connection: is a access connection for the VLAN of station;
- Switch - Switch connection: is a trunk connection, are allowed only VLANs necessary for 
conectivity in local network(for Green network are configured VLANs A and B);
- Switch - Router connection: is a trunk connection, are allowed only VLANs necessary for 
conectivity in local network;

    Inter-VLAN routing
    
- The routers was configured;
- The Green and Blue zones was configured as Router on Stick;

      Routers connectivity
- GR1, BR1, YR1, YR2 - are in first VLAN;
- YR1, YR2 - are in second VLAN;
![image](https://user-images.githubusercontent.com/57103861/175052293-6ce7e60e-a0cc-4360-b2f0-c82a00c2edb5.png)
