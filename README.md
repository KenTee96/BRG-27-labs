# BRG-27-labs
Documentation for ISEA bridging module

## Day 1

-Learning more about the structure of servers

-Hands on mounting and installation of VMs (tried with Kali Linux and Ubuntu Desktop), configuring and allocation of resources

-Done using virtualbox

-Tried commands like 'ls', 'pwd', 'touch'

-Looked at running services using 'systemctl'

-Stop processes and check on the statuses of services

-Tried chmod to edit the rwx permissions, using ls -l to view permissions


## Day 2

-Sign up on Azure for free student resources and USD$100 credit

-Create resource group and set up cloud VM

-Take into consideration the cost of the VM (chosen cheapest Azure vm size, B1s, 0.5GiB RAM, 

-Setup the network to allow ssh only from my IP for port 22

-Connect to Azure cloud VM via powershell from my pc

-Created a script for updating base packages

-Changed permission to allow execute for the update script

-Used crontab to add in a rule to run the script at 3am everyday and store the stdin/stdout in a log file

## Day 3

-Registered a free subdomain for Azure VM on duckdns (iseacloudlab.duckdns.org)

-SSH into Azure VM and did some configuration

-Installed Nginx

-Installed Certbot for SSL secure connection

-Tried using dig command to verify dns is registered

-Went onto browser to test for the Vm's domain

-Changed the default page to run my own simple index.html

-Included a test file for viewing as a hyperlink (testdoc.txt)

-Logged the access of hyperlink

## Day 4

-Installation of ufw using apt

-Tried extracting IP that are doing suspicious activities to the server from access.log

-Plan to integrate ufw functions into a script and process the extracted IP for blocking/further actions or monitoring
