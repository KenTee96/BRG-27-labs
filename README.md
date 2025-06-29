# BRG-27-labs
Documentation for ISEA bridging module

Day 1

-Learning more about the structure of servers

-Hands on mounting and installation of VMs (tried with Kali Linux and Ubuntu Desktop), configuring and allocation of resources

-Done using virtualbox

-Tried commands like 'ls', 'pwd', 'touch'

-Looked at running services using 'systemctl'

-Stop processes and check on the statuses of services

-Tried chmod to edit the rwx permissions, using ls -l to view permissions


Day 2

-Sign up on Azure for free student resources and USD$100 credit

-Create resource group and set up cloud VM

-Take into consideration the cost of the VM (chosen cheapest Azure vm size, B1s, 0.5GiB RAM, 

-Setup the network to allow ssh only from my IP for port 22

-Connect to cloud VM via powershell from my pc

-Created a script for updating base packages

-Changed permission to allow execute for the update script

-Used crontab to add in a rule to run the script at 3am everyday and store the stdin/stdout in a log file
