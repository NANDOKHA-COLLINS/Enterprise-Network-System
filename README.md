# Enterprise-Network-System
It shows a small enterprise system
Download the project and unzip and open it using cisco packet tracer

##############
address space given 192.168.1.0/24


three departments:           range of IP address      BRoadcast Ip
admin/IT  192.168.1.0  192.168.1.1- 192.168.1.62      192.168.1.63 

finance/HR 192.168.1.64 
                     192.168.1.65 -192.168.1.126      192.168.1.127

customer service/reception
192.168.1.128
                     192.168.1.129 -192.168.1.190     192.168.1.191 

#################################################################
SWITCH:
vlan are created : admin/IT vlan 10             fa0/1-4
                   finance/HR  vlan 20           fa0/5-8
                   customer service/reception vlan 30  fa0/9-12


interface gig0/2 is a trunckport to transfer traffic from switch to router to 
DHCP pools are configured on the switch according to the vlan

########################################################
ROUTER
Inter-vlan routing is configure on the router(ROSA- Router On the Stick)
##############################################
WLAN
Every wireless has its own SSID rhyming the department it belongs and the Service Set Identifier on its Access points
admin/IT
smartphone/tablet  ................SSID is admin/it
finance/hr   
smartphone/tablet      ................SSID is finance/hr
customer/reception
smartphone/tablet      ................SSID is customer/reception



Developed by Nandokha Collins
nandokhacollins0@gmial.com
0758974868
