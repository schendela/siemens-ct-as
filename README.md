# siemens-ct-as
Code test for siemens
The cloudformation template will deploy a ec2 instance with all supporting infrastructure. 
It deploys a new vpc. Cidr 10.10.0.0/24
New subnet 10.10.10.0/25
Deploys Route Table and routes. Associates the subnet with the RT.
Deploys a sg and attaches to the ec2
