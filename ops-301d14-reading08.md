# Hectors Reading notes


## Ops Readings


### RADIUS Authentication

1. Why this topic matters as it relates to what you are studying

- As ops proffessionals it is important to know the AAA and what a Radius is.

Computer Network - AAA 

1. Explain each of the three A’s as you would to a non-technical family member. Use an analogy or a story.

- Authentication: something like a user name and password, something to identify you.
- Authorization: like a badge at a crime scene, are you allowed here?
- Accounting: Someone or something is watching what you do while your on the computer, even if it does not seem like it.

2. What should the administrator do if the ACS server fails to authenticate a user during AAA implementation?

- "If the ACS server fails to authenticate, the administrator should mention using the local database of the device as a backup, in the method list, to implement AAA." (saurabhsharma56, OCT2023)

3. What is the role of the NAS in the AAA implementation using an ACS server? Use a diagram.

- "sends authentication requests to the ACS server and the server takes the decision to allow the user to access the network resource or not according to the credentials provided by the user." (saurabhsharma56, OCT2023)

RADIUS Concepts

1. What are the benefits of using RADIUS for authentication and authorization?

- Better securtiy, better management, better usage tracking.

2. What is RADIUS and what does it stand for?

- Remote Authentication Dial In User Service: Is an offsite resource that handles user authentication.

3. Research: What encryption algorithms does RADIUS use?

- "RADIUS (Remote Authentication Dial-In User Service) itself does not mandate specific encryption algorithms. Instead, the security of RADIUS is typically achieved through the use of underlying protocols, such as Transport Layer Security (TLS) or Datagram Transport Layer Security (DTLS), which provide encryption and secure communication." (ChatGPT)

## Things I want to know more about

- What other services are out there?
 
## Resources

https://www.geeksforgeeks.org/computer-network-aaa-authentication-authorization-and-accounting/
(Used for general understanding and quoted in the reading)

https://www.techtarget.com/searchsecurity/definition/RADIUS
(Used for general understanding and quoted in the reading)

https://chat.openai.com/share/aef7dae1-56d4-46e3-8ea2-a2b3e669cc2b
(Used for general understanding and quoted in the reading)
