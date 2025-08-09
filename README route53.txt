 AWS Route 53 - Domain & DNS Setup

 Project Overview

This project covers the setup of a custom domain using AWS Route 53.  
You will learn how to create a hosted zone, add DNS records, and map your domain to an EC2 instance or any AWS resource.

Features

 Create Hosted Zone in Route 53  
add A record to point domain to EC2 public IP  
 Configure NS and SOA records automatically  
 Understand TTL and routing policies  

Steps Performed

1. Create Hosted Zone
   Domain used: `vivekcloudtest.com`  
   Route 53 auto-created NS and SOA records.

2. Create A Record 
   Type: A (IPv4 address)  
   Value: EC2 Public IP `15.206.49.178`  
   TTL: 300 seconds  
    Routing policy: Simple


3. Test domain 

    Access your site via `http://vivekcloudtest.com`  


Demo Video
[Watch the demo here](https://drive.google.com/file/d/1zWi7oT_gvOC8MLTXvPCYy3I2ILiv5dJy/view?usp=sharing)




Created by Vivek Teja
