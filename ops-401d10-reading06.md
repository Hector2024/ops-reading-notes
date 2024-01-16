# Hectors Reading notes


## Ops Readings


###  Data file encryption

1. Why this topic matters as it relates to what you are studying

- File encryption and hashing are good ways to ensure your data is safe and unaltered. Knowing some of how the process works is a good idea.

2. You have been made responsible for the company’s file server. How would you preserve the three elements of the CIA triad?

- First we have to make sure that the data at rest and the data in transit are both being encrypted by method of SSL or SSH for data in transit and Open PGP, disk level, or file level encryptions.
- Second we want to use hashing or digital signitures to ensure entegrity
- Lastly we want to set up a redundant system in case of failure. Like a Active-Active or Active-Passive availability cluster. 

3. Explain how hashing verifies data integrity using non-technical terms.

- Hashing is when something like a file gets its own serial number. That serial number will change if you touch that file, even if it is only a space or 1 letter. This way hashing ensures that the file you made and sent has not been changed by anyone on its way to the intended party.

4. How is hashing and encryption different?

- Hashing is for the integrity of the data it, has nothing to do with protecting it from anyone. As opposed to Encryption which has to do with the protection of the data. 
- Hashing is like a signatures on a paper, if its changed or if the signatures looks off the paper has probably been changed but Encryption is like writing a coded message where it does not matter if someone gets it because they do not have the code to figure it out.

## Things I want to know more about

- How do the crypto signatures work with the hashes?
- Are we making advances towards different hashed?
- Are we making advances towards different encryption methods?

## Resources

https://www.jscape.com/blog/implementing-the-cia-triad-when-transferring-files-through-the-internet
https://www.howtogeek.com/67241/htg-explains-what-are-md5-sha-1-hashes-and-how-do-i-check-them/
(Used for general understanding and quoted in the reading)
