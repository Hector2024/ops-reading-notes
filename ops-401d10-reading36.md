# Hectors Reading notes

## Ops Readings

### Cross-Site Scripting

1. Why this topic matters as it relates to what you are studying

- Cross site scripting is an avenue of attack that can and will be exploited if allowed. Knowing something about it can go a long way to preventing it.

2. Explain how a cross-site scripting attack works in non-technical terms.

- It is what happens when an attacker is able to input data in an allowed way by a website, to instead input code for malicious activity. 

3. What are the three types of XSS attacks?

>- Reflected XSS, where the malicious script comes from the current HTTP request.
>- Stored XSS, where the malicious script comes from the website's database.
>- DOM-based XSS, where the vulnerability exists in client-side code rather than server-side code.

(Port-Swiggers, 2024)

4. If an attacker successfully exploits a XSS vulnerability, what malicious actions would they be able to perform?

>- Impersonate or masquerade as the victim user.
>- Carry out any action that the user is able to perform.
>- Read any data that the user is able to access.
>- Capture the user's login credentials.
>- Perform virtual defacement of the web site.
>- Inject trojan functionality into the web site. 
(Port-Swiggers, 2024)

5. What are some security controls that can be implemented to prevent XSS attacks?

- Filter input, encode data on output, appropriate response lheader, content security policy

## Things I want to know more about

- Where can I see some live examples?

## Resources

- [PortSwigger](https://portswigger.net/web-security/cross-site-scripting)

(Used for general understanding and quoted in the reading)