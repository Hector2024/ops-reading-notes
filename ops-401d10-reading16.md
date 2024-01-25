# Hectors Reading notes

## Ops Readings

### The Pros and Cons of Network Intrusion Detection Systems

1. Why this topic matters as it relates to what you are studying

- Studying a data breach is the best way to understand the current threats and some upcoiming ones. If you study your adversary you will learn.

2. What were the three commands used for the attack?

> "Code for 3 commands used for the attack
>
>-  Get Credentials
>
> First command when executed obtained security
>credentials known as ****-WAF-Role account (an IAM account) for an
>elevated role access AWS Web Application Firewall (WAF)
>
>-  List Buckets
>
> Second command, when executed, used the security
credentials *****-WAF-Role account to list files and folders (aka S3 buckets)
>
>-  Download Files
>
> Third command, when executed used the *****-WAF-Role
>account to download files that were accessible by the credentials."

(Capital One data breach PDF)

3. What misconfiguration of AWS components allowed the attacker to access sensitive data?

>- "the attack occurred due to a misconfiguration error at the application layer of a firewall installed by Financial
>Institution, exacerbated by permissions set by Financial Institution that were likely broader than intended."
(Capital One data breach PDF)
4. What are two of the AWS Governance practices that could have prevented such attack?

>- "EC2 
>
>Exposing unnecessary shell access, probably from a left-over development /
>staging or a production debugging deployment.
>- S3 bucket 
>
>Financial Institute determined that the third command (the “Sync Command”),
>when executed, used the ***-WAF-Role to extract or copy data from those
>folders or buckets in Financial Institute storage space for which the ***-WAF-
>Role account had the requisite permissions. (III.A.11)
>Suggests that the attacker had access to ‘aws s3 sync’ command. i.e. the IAM
>role used S3 list (e.g. aws s3 ls) and Read access (e.g. aws s3 sync)."
(Capital One data breach PDF)
## Things I want to know more about

- Was the report taken serious the first time?
- Who was the last big bank to be broken into?
- Why did the person conducting the attack post it on HIS github page?

## Resources

- [Capital One Data Breach](https://www.zscaler.com/resources/white-papers/capital-one-data-breach.pdf)
(Used for general understanding and quoted in the reading)