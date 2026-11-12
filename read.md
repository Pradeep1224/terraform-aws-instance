## EC2 Instance Creation

### resources 

* Ec2 instance -> aws_instance.main

### Inputs

* instance_type (optional)
* sg_ids(mandatory)  - list ofv sg's 
* project (mandatory) string
* environment(mandatory) 
* component(mandatory)
* ec2_tags (mandatory)


### Outputs
* public_ip
* private_ip
* Instance_id
