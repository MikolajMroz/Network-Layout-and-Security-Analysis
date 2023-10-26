# Network-Layout-and-Security-Analysis
Mapping out the ACME Inc. Network, its associated IP address ranges, and its subnets, followed by several security tests and vulnerability assessments. 

## BACKGROUND

ACME Inc. has requested a thorough overview of their company network, creating a professional visual map of connected devices and all their associated IP addresses, subnets, and domains through the use of current network testing tools and techniques. This allows them to have a comprehensive diagram of the network to consult in the event of any issues down the line as necessary documentation was not previously available and is vital to the operation and maintenance of any legitimate modern business. 

The company also wished for a full security investigation into these devices, exploiting and documenting found vulnerabilities. Any such vulnerabilities are to be paired with appropriate screenshots for easy recreation by the network team as well as ways of counteracting them to improve the security of the network and the safety of all its users. Issues with the general network layout and design are also to be noted and improved upon, as the company is expecting a fully robust network setup for use by its employees and consumers and must adhere to relevant security laws to obtain this. 

Before the investigation took place, a single ‘Coursework’ Virtual Machine was provided to be imported into VMWare. Inside it was a remote desktop to a Kali machine, connected to the ACME INC. network with a variety of pre-installed, approved tools on it. All mapping and testing activity was confined to the ACME INC. network, as the VM hosting it was not to be attacked.

## AIM
The aims of the project are to:
•	Map out the ACME Inc. network in a detailed, easy-to-follow visual format listing each device, interface, IP address, subnet, and connection. 

•	Discover, exploit, and document all found vulnerabilities in the network software and design, listing appropriate countermeasures and improvements.

## NETWORK MAPPING METHODOLOGY
To map the devices on the target network, the following methodology was used.

1.	Determine the interface information of the Kali machine.
   
2.	Scan the connected network for active devices and open ports.
   
3.	Gain access to network devices and analyze routing/interface information.
   
4.	Connect to any newly discovered devices to uncover the remaining parts of the network, repeating steps 2-3 until no new networks or devices are being found.
   
5.	Create a map of all known devices, interfaces, and networks from the found information.

## SUBNET TABLE
The ACME INC. network was found to be using VLSM (Variable Length Subnet Masks), which splits the IP address ranges more efficiently than traditional methods. Hence, there is space for additional IP addresses within the network where certain VLSM address ranges were not utilized.

![image](https://github.com/MikolajMroz/Network-Layout-and-Security-Analysis/assets/98950042/4daf6c60-b51b-46f7-9fc6-d24e6e2bd9c1)

## NETWORK DIAGRAM
The ACME INC. network follows the topology design below. 

![image](https://github.com/MikolajMroz/Network-Layout-and-Security-Analysis/assets/98950042/3d4f8a65-e373-4f81-9668-c9e5baf3c66d)
