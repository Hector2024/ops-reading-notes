# Hectors Reading notes

## Ops Readings

### Modeling a Web Application

1. Why this topic matters as it relates to what you are studying

- Threat analysis is one of the ways we have to fight against threats, it is a good way to keep our systems healthy and clean.

2. What is the main goal of Threat Hunting and how is it different from traditional threat monitoring?
    
- As the name implies hunting is when you are actively seeking and finding threats as opposed to monitoring, where we just passively monitor for the threats.
    
3. What are the four types of YARA rules and what does each one of them use to identify and classify malicious software?

> - String-based rules: These rules use strings of text, either as literal values or as regular expressions, to identify malware. For example, you might use a string-based rule to detect malware that contains a specific string of characters in its code.
> - File metadata-based rules: These rules use metadata about the files being analyzed to identify malware. For example, you might use a file metadata-based rule to detect a particular file type or to identify files that have been created or modified within a specific time period.
> - Hash-based rules: These rules use cryptographic hashes to identify malware. A cryptographic hash is a unique representation of the contents of a file, and if any part of the file changes, the hash will also change. Hash-based rules can be used to detect malware that has been modified or disguised in an attempt to evade detection.
> - Network-based rules: These rules use network traffic data, such as IP addresses or ports, to identify malware. For example, you might use a network-based rule to detect malware that is communicating with a specific IP address or port.

(Geeks for Geeks, JAN 2023)

4. How are YARA rules similar to how Anti-Virus programs detect malicious software?

- Both use signiture detection

## Things I want to know more about

- Are there other things like YARA to follow?

## Resources

- [Archer News Network](https://archerint.com/what-are-yara-rules/)
- [Geeks for Geeks](https://www.geeksforgeeks.org/threat-hunting-using-yara/)
(Used for general understanding and quoted in the reading)