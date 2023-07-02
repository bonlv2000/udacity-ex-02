# Deploy a High-Availability Web App using CloudFormation

 File Automation YAML Deploy CloudFormation : udacity-ex-02.yaml
 Load Balancer DNS Name : http://udaci-webap-1smsjb0wfbnpz-1249958698.us-east-1.elb.amazonaws.com/

 1. Parameters
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/00e6d89b-c0cd-45f4-ac9e-9b55b273c7d0)

 2. Security groups
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/7ed8fb42-613a-4065-bcaa-a911caefc69d)

 3. Target Group
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/57f7e443-e84f-4ad4-b7be-5e8d5a8b2a19)

 4. Load Balancer
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/95205d31-0d60-4844-a094-860abf257dbb)

 5. Launch Configuration
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/2af71e2d-3749-4a45-b217-dd1112dd28fb)

 6. Auto Scaling groups
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/aff627e1-0ce5-4b78-8ff6-6193eb5e6c27)

 7. a URL to verify his work is running properly
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/33ffd5d4-bdeb-4ecf-a675-70f2c948bbad)

 8. The Load Balancer will have a Listener rule associated with the same target group
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/6999966b-a854-415c-b484-a65a2433b6f2)

 9. Port 80 should be used in Security groups, health checks and listeners associated with the load balancer
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/3ad98b26-b6ab-4cb1-b491-e8d729c7e1c2)
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/b4cad2d7-b829-4732-8565-906ebbde78bb)

 10. Auto-Scaling Students should be using PRIV-NET ( private subnets ) for their auto-scaling instances
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/f4d5f53c-3347-40a1-9ea4-673c92f1c302)

 11. The machine should have 10 GB or more of disk and should be a t3.small or better.
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/a91984aa-a962-4f7c-9125-317ce794e22f)
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/09f232f8-9630-421f-9ca6-4500895d1ff5)
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/d77ffc43-d617-4636-82b2-a1c9d344391b)

 12. There shouldn’t be a ‘keyname’ property in the launch config
![image](https://github.com/bonlv2000/udacity-ex-02/assets/59633180/039e77dd-4e74-4d48-b423-fcc312251d39)




