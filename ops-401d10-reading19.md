# Hectors Reading notes

## Ops Readings

### What is Amazon GuardDuty?

1. Why this topic matters as it relates to what you are studying

- AWS is a big competitor and their services are not going away. It would benifit us to know it.

2. What are some of the IoCs that GuardDuty can detect?

- "GuardDuty can detect compromised EC2 instances and container workloads serving malware, or mining bitcoin" (AWS)

3. What are some of the data sources which GuardDuty can use?

- "The GuardDuty console provides access to your GuardDuty account, data, and resources." (AWS)

4. How does GuardDuty use access behavior to spot potential malicious activity?

- It analyzes and processes foundational data sources, uses threat intelligence feeds, and machine learning to identify potential malicious activity. In simpler terms it gets a base line of your systems and along with known signitures of threats it then monitors your systems for unusal behavior.


## Things I want to know more about

- How often does this system get updated?
- What do the false/positive to positive/positive ratios look like?
- How  much of an inconvenience does this make for an influx of real traffic?

## Resources

- [AWS](https://docs.aws.amazon.com/guardduty/latest/ug/what-is-guardduty.html)
(Used for general understanding and quoted in the reading)