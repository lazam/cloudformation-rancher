Rancher cluster using AWS cloudformation

Architecture Information:

Platform runs in Rancher OS.

There are  2 stacks for this Cloudformation which are divded into security group and EC2 + RDS.

Security group stack consists of an internal security group which opens the port required for HA and RDS and a Global security group which is for HTTP/HTTPS access everywhere.
Rancher stack consists of EC2 , ELB and RDS.


TBD:
- Automatic HA setup
- Addition of nodes
