# Hectors Reading notes


## Ops Readings


### Routing

1. Why this topic matters as it relates to what you are studying

- Routing is important as it relates to layer 3 of the OSI modle it is also where traffic get routed to get to another network

VirtualBox Network Settings Guide

1. Which network mode in VirtualBox can be used to emulate unplugging the Ethernet cable from the network?

- Not attached or you can uncheck the "cable connection box"

2. Which network mode would be best if you wanted to run a server on a VM that could be fully accessible from your physical local area network?

- Bridged

3. What are the three options of promiscuous mode and what does each do?

> - "Deny. Any traffic that is not intended to the virtual network adapter of the VM is hidden from the VM. This option is set by default.
> - Allow VMs. All traffic is hidden from the VM network adapter except the traffic transmitted to and from other VMs.
> - Allow All. There are no restrictions in this mode. A VM network adapter can see all incoming and outgoing traffic." (NAKIVO Team, JUN2023)


4. What is Port Forwarding?

- Port forwarding is when you tell your router to forward traffic from a public port to another private port allowing public access a private network

## Things I want to know more about

- I want to see it in action 
- How do VPNs use port forwarding?
 
## Resources

https://www.nakivo.com/blog/virtualbox-network-setting-guide/
(Used for general undrestanding and quoted in the reading)

