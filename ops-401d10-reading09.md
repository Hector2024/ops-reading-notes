# Hectors Reading notes


## Ops Readings


###  Protecting Data at Rest with Device Encryption

1. Why this topic matters as it relates to what you are studying

-

### What is Public Key Infrastructure (PKI)

1. Name the three main components which make up PKI.

- Certificate Authority, public key, private key

2. How would you explain, to a non-technical friend, the role PKI plays in protecting traffic between your browser and a web server.

- PKI does a sort of hand shake. You go to your computer and ask for a website and if it is a secure website it will look for the SSL certifiacate (The thing that lets it know it is safe). Once it verifys the certificate it puts you in a secure connection to protect you, your information, and the website.

3. What is the main weakness of the PKI architecture?

- "The main weakness of public PKI is that any certificate authority can sign a certificate for any person or computer." (SSH 2023)

## Things I want to know more about

- Who is the reegistration authority and how do we know they can be trusted?
- Can the PKI directory be hacked to show a different CA in the registry?
- Are there just layers of CAs for every site?

## Resources

https://www.ssh.com/academy/pki 
(Used for general understanding and quoted in the reading)
