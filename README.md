# Implementing-Wordpress-Website

1. Preparing the webserver

First and EC2 instance running Redhat OS was provisioned

![EC2 Instance](https://github.com/oghare01/Implementing-Wordpress-Website/assets/141191975/3d3304a8-1ea9-4ae2-a6c6-c73622d4945c)

The Availablity Zone (AZ) was taken note of, as it was used to creat EBS volunes to be attached to the instance. 
Three volumes in a similar AZ as the instance were created and attached to the instance

![Created volumes](https://github.com/oghare01/Implementing-Wordpress-Website/assets/141191975/ae778566-4dae-4856-b455-4f746f157b2f)

2. Block Inspection and partioning

The instances was connected into on the terminal and the 'lsblk' command was used to check the block connected. With the results as shown below 

![Block inspection](https://github.com/oghare01/Implementing-Wordpress-Website/assets/141191975/8f2b8103-a49e-4b07-9df4-af3a4aee2fef)


3. 
