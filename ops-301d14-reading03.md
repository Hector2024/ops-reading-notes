# Hectors Reading notes


## Ops Readings


### Network Segmentation

1. Why this topic matters as it relates to what you are studying

- We are ops proffesionals so we will be working with network segmentaion. It helps midigate and contain risks

CIDR Block Notation Explained in 2 Minutes

1. What is CIDR notation? a CIDR block?

- "CIDR notation is a way of representing a CIDR block, which is simply a range of IP addresses. When you create a network, the aim is to make sure there are enough available IP addresses for your use case, without making the CIDR block too large and wasteful." (Michael Nicholas, AUG2018)

2. How many octets are found in an IPv4 address?

- 4 octets

3. Setting binary aside and using the decimal system, what is the range of numbers found in an octet?

- 000.000.000.000 - 255.255.255.255

4. What does the final digit after the “/” represent in an IPv4 address?

- how many bits make up the mask

5. How many IP addresses are in the CIDR block 10.0.0.0/24?

- 256 with 254 being usable

What Is Network Segmentation and Why It Matters?

1. In your own words, describe network segmentation.

- It is when your network is split up

2. Network segmentation isn’t important as long as the network is using a well configured firewall. Do you agree? Why or why not?

- No firewalls have a high workload and always have the possibility of missing something so segmenting it allows you some redundency and extra percation in case of emergencies.

3. What is a screened subnet?

- When 1 firewall is used for 3 netwroks interfaces.

4. Cameras, ID card scanners, locked doors and biometrics are just a few examples of what type of security?

- Physical

## Things I want to know more about

- I want to see it in action 
 
## Resources
https://medium.com/@ethicalentrepreneur/cidr-block-notation-explained-in-2-minutes-1010ec0dbc15
(Used for general understanding and quoted in the reading)

https://www.comptia.org/blog/security-awareness-training-network-segmentation
(Used for general undrestanding in the reading)