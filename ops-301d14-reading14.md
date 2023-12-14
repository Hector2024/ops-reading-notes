# Hectors Reading notes


## Ops Readings


### Group Policy

1. Why this topic matters as it relates to what you are studying

- Group polocies are everywhere in the working world not only in tech and getting familiar with one is a good way manage users in ourcase

What is Group Policy and What Role Does It Play in Data Security

1. What role does Group Policy play in Windows Active Directory?

- "provides a centralized place for administrators to manage and configure operating systems, applications, and users’ settings." (Jason Coggins, NOV2022)

2. Name and describe different ways GPOs can benefit security.

> - Password Policy: Many organizations are operating with relaxed password policies, with many users often having passwords set to never expire. Passwords that aren’t regularly rotated, are too simple or use common passphrases are at risk of being hacked through brute force. GPOs can be used to establish password length, complexity and other requirements.
> - Systems Management: GPOs can be used to simplify tasks that are at best mundane and at worst critically time-consuming. You can save yourself hours and hours of time configuring the environment of new users and computers joining your domain by using GPOs to apply a standardized, universal one.
> - Health Checking: GPOs can be used to deploy software updates and system patches to ensure your environment is healthy and up to date against the latest security threats.

(Jason Coggins, NOV2022)


3. How can the acronym “LSDOU” help you figure out which policies are in effect?

- You just follow the ladder L,S,D,OU. If there are conflicting policies the system will follow the lowest rung on the ladder. If S has a conflicting policy with D then it will follow S for the policy.

## Things I want to know more about

- Why is the is policy conflict handled that way.
- What are normal policies
- Do the SOPs, AUPs, and GPO go together?
 
## Resources

https://www.lepide.com/blog/what-is-group-policy-gpo-and-what-role-does-it-play-in-data-security/
(Used for general understanding and quoted in the reading)