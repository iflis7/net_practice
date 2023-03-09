# `NET PRACTICE`

This project is a general practical exercise to let you discover networking.`Version: 2`.<br>


<h1 align="center">
	42cursus' Net Practice
</h1>

<p align="center">
	<b><i>Development repo for 42cursus Net Practice project</i></b><br>
	For further information about 42cursus and its projects, please refer to <a href="https://github.com/iflis7/libft"><b>42cursus repo</b></a>.
</p>

<p align="center">
    <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=65"><img alt="Made with Love" src="https://img.shields.io/badge/Made%20with-Love-1f425f.svg"/></a>
    <img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/iflis7/get_next_line?color=lightblue" />
    <img alt="Number of lines of code" src="https://img.shields.io/tokei/lines/github/iflis7/get_next_line?color=critical" />
    <img alt="Code language count" src="https://img.shields.io/github/languages/count/iflis7/get_next_line?color=yellow" />
    <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/iflis7/get_next_line?color=blue" />
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/iflis7/get_next_line?color=green" />
</p>


## Understanding the Basics of Networking

Before you can set up IP addresses for a basic network, it's essential to have a basic understanding of how networks function. At a high level, a network is a collection of devices that are connected to each other, allowing them to communicate and share resources.

One of the most critical components of a network is the router. A router is a network device that forwards data packets between different networks, such as a local area network (LAN) and the internet. Routers use routing tables to determine the best path for data packets to travel based on the destination IP address.

Another critical component of a network is the switch. A switch is a network device that connects devices within a LAN, allowing them to communicate with each other. Switches use MAC addresses to forward data packets to the correct device.

Other network devices that you may encounter include firewalls, load balancers, and proxy servers. Firewalls are used to block unauthorized access to a network, while load balancers distribute network traffic across multiple servers. Proxy servers act as intermediaries between clients and servers, providing caching and security benefits.

In addition to these network devices, you should also be familiar with network topologies. A network topology refers to the way that devices are connected to each other. Some common network topologies include:

- Bus: Devices are connected to a single cable, with data transmitted in both directions.

- Star: Devices are connected to a central hub or switch.

- Ring: Devices are connected in a closed loop, with data transmitted in one direction.

- Mesh: Devices are connected to each other in a non-linear fashion.

Finally, you should understand the various network protocols that are used to enable communication between devices. Some common network protocols include:

- TCP/IP: This is the most widely used network protocol suite, and it provides a standardized way for devices to communicate over the internet.

- DNS: The Domain Name System is used to translate domain names into IP addresses, making it easier to browse the internet.

- DHCP: The Dynamic Host Configuration Protocol is used to automatically assign IP addresses to devices on a network.

In summary, understanding the basics of networking is crucial before setting up IP addresses for a basic network. You should be familiar with the roles of routers, switches, and other network devices, as well as network topologies and protocols. This knowledge will help you set up a stable and secure network that meets your needs. 


## Know the Different Types of IP Addresses

Before setting up IP addresses for a basic network, it's essential to understand the different types of IP addresses that are available. There are two main types of IP addresses - IPv4 and IPv6.

IPv4 is the most widely used IP address format and consists of a 32-bit address expressed in four groups of decimal numbers separated by dots. Each group can range from 0 to 255, and the total number of unique IPv4 addresses is limited to approximately 4.3 billion. While this may seem like a large number, it is not sufficient to accommodate the rapidly growing number of devices that need to connect to the internet.

IPv6 was developed as a successor to IPv4 and is designed to provide a larger address space. It consists of a 128-bit address expressed in eight groups of hexadecimal numbers separated by colons. Each group can range from 0 to FFFF, and the total number of unique IPv6 addresses is virtually limitless. IPv6 also provides other benefits over IPv4, including improved security and better support for mobile networks.

While IPv6 is becoming increasingly popular, IPv4 is still the most widely used IP address format. This means that you will likely encounter IPv4 addresses more frequently, and it's important to understand how to work with them.

In addition to the standard IPv4 and IPv6 addresses, there are other types of IP addresses that you may encounter, including:

- Private IP addresses: These are reserved IP addresses that are used within a private network and are not accessible from the internet. Private IP addresses are often used in home and business networks.

- Public IP addresses: These are IP addresses that are accessible from the internet and are used to identify devices on the internet. Public IP addresses are assigned to devices by internet service providers (ISPs).

- Static IP addresses: These are IP addresses that are manually assigned to a device and do not change over time. Static IP addresses are often used for servers or devices that require a fixed IP address.

- Dynamic IP addresses: These are IP addresses that are assigned to a device automatically and can change over time. Dynamic IP addresses are often used for devices that connect to the internet sporadically, such as laptops or smartphones.

In summary, there are two main types of IP addresses - IPv4 and IPv6 - that you should be familiar with before setting up a basic network. You should also understand the different types of IP addresses, including private, public, static, and dynamic addresses. This knowledge will help you choose the appropriate IP addressing scheme for your network and configure IP addresses on different devices. 


## Understand Subnetting

Subnetting is a technique used to divide a large network into smaller sub-networks or subnets. This can help to improve network performance, reduce congestion, and enhance security. When you subnet a network, you create multiple subnets, each with its own unique IP address range.

To subnet a network, you need to determine the subnet mask, which is used to divide the network into subnets. The subnet mask is a 32-bit number that is used to mask the network portion of an IP address from the host portion. It consists of a series of ones followed by a series of zeros, where the number of ones indicates the size of the network portion and the number of zeros indicates the size of the host portion.

For example, if you have an IPv4 address of 192.168.1.0 and a subnet mask of 255.255.255.0, this would give you a network address of 192.168.1.0 and a host range of 192.168.1.1-192.168.1.254. This would allow you to create up to 254 hosts on this network.

To subnet this network further, you would need to borrow bits from the host portion to create additional subnets. For example, if you borrowed 2 bits from the host portion, this would give you 4 subnets, each with a host range of 62 addresses. The new subnet mask would be 255.255.255.192, and the new subnets would have IP addresses of 192.168.1.0/26, 192.168.1.64/26, 192.168.1.128/26, and 192.168.1.192/26.

When subnetting, it's important to be able to calculate subnets and determine the number of hosts per subnet. This can be done using the subnet mask and the formula 2^n, where n is the number of borrowed bits. For example, if you borrow 2 bits, you will have 2^2 = 4 subnets, each with 2^6-2 = 62 hosts.

Subnetting can be a complex topic, but it's an important skill for network administrators and engineers to have. Understanding subnetting can help you to design and implement networks that are efficient, secure, and scalable.


## Configure IP Addresses on Devices

Once you have a basic understanding of networking and IP addressing, you'll need to know how to configure IP addresses on different devices. This is an essential skill for network administrators and engineers.

To configure IP addresses on devices, you'll need to access the device's configuration interface. The process for accessing this interface can vary depending on the device, but typically involves opening a web browser and entering the device's IP address in the address bar. You may also need to enter a username and password to log in to the device.

Once you're logged in to the device, you'll need to locate the settings for configuring IP addresses. This can also vary depending on the device, but is typically found under a "Network" or "LAN" menu. In some cases, you may need to navigate through several menus to find the appropriate settings.

When configuring IP addresses on a device, you'll need to enter the appropriate IP address, subnet mask, and gateway information. The IP address should be unique within the network, and should be within the range of the network's IP address scheme. The subnet mask should be set to the appropriate value based on the network's subnetting scheme. The gateway is typically set to the IP address of the device that provides access to the internet or to other networks.

It's important to ensure that the IP addresses are configured correctly on all devices within the network. Misconfigured IP addresses can cause communication issues and other problems.

Configuring IP addresses on devices can be a complex process, but it's an essential skill for network administrators and engineers. With the right knowledge and experience, you can configure IP addresses on devices quickly and efficiently, ensuring that your network runs smoothly and securely.


## Understanding DHCP

DHCP (Dynamic Host Configuration Protocol) is a protocol that automatically assigns IP addresses to devices on a network. This makes it easier to manage IP addresses on a large network, as administrators don't need to manually assign IP addresses to each device.

To use DHCP, you'll need to configure a DHCP server on your network. This can be done using a router, switch, or dedicated DHCP server. The DHCP server is responsible for assigning IP addresses to devices on the network, as well as providing other network configuration information, such as subnet mask and gateway settings.

To configure DHCP on a router or server, you'll need to access the device's configuration interface and locate the settings for DHCP. This typically involves navigating to a "DHCP" or "LAN" menu, and enabling the DHCP server. You may also need to configure settings such as the IP address range and lease time.

Once DHCP is configured, devices on the network can request an IP address from the DHCP server. The DHCP server will assign an available IP address to the device, along with other network configuration information. Devices can also renew their IP address lease periodically to ensure that they remain connected to the network.

It's important to troubleshoot DHCP issues if they occur. Common issues include IP address conflicts, where multiple devices are assigned the same IP address, and DHCP server failures. To troubleshoot these issues, you'll need to check the DHCP server logs and network configuration settings.

Understanding DHCP is an important skill for network administrators and engineers. With the right knowledge and experience, you can configure DHCP on a network quickly and efficiently, ensuring that devices are connected to the network with the appropriate IP addresses and network configuration settings.


## Understanding DNS

DNS (Domain Name System) is a system that translates domain names into IP addresses. This makes it easier for users to access websites and services, as they don't need to remember the IP addresses of each site they visit.

To use DNS, you'll need to configure a DNS server on your network. This can be done using a router, switch, or dedicated DNS server. The DNS server is responsible for maintaining a database of domain names and their associated IP addresses. When a user types in a domain name, the DNS server looks up the IP address associated with that domain name and returns it to the user's device.

To configure DNS on a network, you'll need to access the device's configuration interface and locate the settings for DNS. This typically involves navigating to a "DNS" or "Internet" menu, and entering the IP address of the DNS server. You may also need to configure other settings, such as the DNS search domain and DNS server priority.

It's important to troubleshoot DNS issues if they occur. Common issues include DNS server failures, where the DNS server is not responding to requests, and DNS resolution errors, where the DNS server is unable to resolve a domain name to an IP address. To troubleshoot these issues, you'll need to check the DNS server logs and network configuration settings.

Understanding DNS is an important skill for network administrators and engineers. With the right knowledge and experience, you can configure DNS on a network quickly and efficiently, ensuring that users are able to access websites and services with ease.





