# Hectors Reading notes


## Ops Readings


### Network scanning with NMAP

1. Why this topic matters as it relates to what you are studying

- NMAP seems to be another industry standard that people are looking for, getting fluent in it could help your job search, career, and knowledge

2. What is a port? Describe it with an analogy that would help a family member understand.

- A computer port is like a port in a harbor, it is where things (in this case network communications) leave from to go somewhere and where they arrive when coming back.

3. What does a port scanner send to a port to check the current status?

- "a port scanner does is send a packet of network data to a port to check the current status." (Michael Buckbee, OCT 2023)

4. When a port scanner sends a request to connect, what are the three possible responses? Describe them.

>"Open, Accepted: The computer responds and asks if there is anything it can do for you.
>Closed, Not Listening: The computer responds that “This port is currently in use and unavailable at this time.”
>Filtered, Dropped, Blocked: The computer doesn’t even bother to respond."
(Michael Buckbee, OCT 2023)

5. What is the difference between TCP and UDP?

- TCP needs to establish communication and make sure ALL the packets to arrive before sending or resending packets, thats why its used in things like files and email as opposed to UDP which does not care if it is communicating or if it received all the packets and thats why it is used in things like games and streaming services

6. List and describe the ports used for the following:

- Telnet
   - Port 23: is to help establish a remote connection with telenet.
- SSH
   - Port 22: Used to secure shell into another system
- DNS
   - Port 53: Is what is used for the domain name system so we do not have to type in the ip address to sites we would like to go to like google.
- SMTP
   - Port 465: Is the port that helps send an email
- HTTP
   - Port 80: Is the port that helps with browsing unencrypted web pages.
- HTTPS
   - Port 443: Is used for websites with encryptions in order to help secure payments and information.
- RDP
   - Port 3389: Is the standard to let remote desktop protocol through, to remote into another computer.
- Ping
   - "Ping uses a network layer protocol called Internet Control Message Protocol (ICMP) and is available on all operating systems." (Bosko Marijan ,March 2021)

## Things I want to know more about

- What are the most important ports?
- Where can I see port surfing in action?
- I see the harm in open ports but how does that help intruders?
 
## Resources
https://www.varonis.com/blog/port-scanning-techniques
(Used for general understanding and quoted in the reading)

https://phoenixnap.com/kb/ping-specific-port
(quoted in the reading for the ping question)