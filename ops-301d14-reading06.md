# Hectors Reading notes


## Ops Readings


### Network Address Translation

1. Why this topic matters as it relates to what you are studying

- We use NAT everyday (if we have home wifi) and it is good to know how and what a NAT actually is.

1. What is the main purpose for implementing NAT on a network?

- "The idea of NAT is to allow multiple devices to access the Internet through a single public address." (saurabhsharma56, DEC2021)

2. At what layer of the OSI model does NAT happen?

- Layer 3

3. What happens to packets when NAT runs out of addresses in the pool of available IPs?

- "packets will be dropped and an Internet Control Message Protocol (ICMP) host unreachable packet to the destination is sent." (saurabhsharma56, DEC2021)

4. What disadvantage does using NAT pose for routers?

- "the router being a network layer device, should not tamper with port numbers(transport layer) but it has to do so because of NAT." (saurabhsharma56, DEC2021)

## Things I want to know more about

- If we use VM's and two are on NAT does that mean that they would technically be on different networks?
- What kind of NAT does most home wifi use
- Do we have to use NAT?
 
## Resources

https://www.geeksforgeeks.org/network-address-translation-nat/
(Used for general undrestanding and quoted in the reading)