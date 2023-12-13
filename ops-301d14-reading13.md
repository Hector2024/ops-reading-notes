# Hectors Reading notes


## Ops Readings


### Active Directory

1. Why this topic matters as it relates to what you are studying

- Windows being the major provider for things we are bound to run into the AD, it is good to know something before running into it in the wild

What is Active Directory?

1. What exactly is “Active Directory” and are the key services it provides?

- "Active Directory (AD) is Microsoft’s directory and identity management service for Windows domain networks." (CyberArk, 2023)

2. What are the differences between a domain, forest, and tree in Active Directory?

> - A domain is a collection of objects (e.g. users, devices) that share the same Active Directory database. A domain is identified by a DNS name like company.com.
> - A tree is a collection of one or more domains with a contiguous namespace (they have a common DNS root name like marketing.company.com, engineering.company.com, and sales.company.com).
> - A forest is a collection of one or more trees that share a common schema, global catalog, and directory configuration—but aren’t part of a contiguous namespace. The forest typically serves as the security boundary for an enterprise network.

-(CyberArk, 2023)

3. How can objects (e.g. users, devices) within a domain be grouped?

- They can be grouped by organizational untis or whatever other system you would like 

4. Explain the benefits of Active Directory, as you would to a family member.

 > - Domain: A group of people and computers working together in one place.
 >  - Tree: Different groups of people and computers (domains) in a neighborhood, all connected and able to work together easily.
 >  - Forest: The entire neighborhood where these groups (trees) are located, with some shared rules and resources.


## Things I want to know more about

- Are there different services that do this
- Can i get a job just doing AD?
- At what size do networks benifit from AD
 
## Resources

https://www.cyberark.com/what-is/active-directory/
(Used for general understanding and quoted in the reading)

https://chat.openai.com/share/34f549ae-688e-4004-8231-be68410546d0
(used to further understand and quoted in the reading.)