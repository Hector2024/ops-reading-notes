# Hectors Reading notes


## Ops Readings


### Cloud Security Principles and Frameworks

1. Why this topic matters as it relates to what you are studying

- AWS is one of the biggest companys and resources out there for cloud computing, if we stay in the feild we will run into it so it is a good idea to learn the Cloud Security Principles and Frameworks from one of the biggest comapanies out there.

2. Explain the levels of abstraction in AWS to someone without a technical background.

- Different levels of abstraction means that the customer can be as involved or hands off as they want to be with their systems.

3. What are the control plane and data plane responsible for in container abstraction?

>    - " A containers control plane that is responsible for exposing the API and interfaces to define, deploy, and lifecycle containers. This is also sometimes referred to as the container orchestration layer.
>    - A containers data plane that is responsible for providing capacity (as in CPU/Memory/Network/Storage) so that those containers can actually run and connect to a network. From a practical perspective this is typically a Linux host or less often a Windows host where the containers get started and wired to the network. "

(Massimo Re Ferre, SEP2018)

4. Where does AWS Lambda fall in the layers of abstraction and what makes it so special?

- It added another layer of abstraction to aws and lets the customers run code without needing to scale it or run an instance.
>- "What makes Lambda so special is its event-driven model. Not only can you invoke Lambda directly (for example, via the Amazon API Gateway), but you can trigger a Lambda function upon an event in another AWS service (for example, an upload to Amazon S3 or a change in an Amazon DynamoDB table)."

(Massimo Re Ferre, SEP2018)

## Things I want to know more about

- What other progress has been made in the levels of abstraction since the publishing of the article?
- Can there be more progress made?
 
## Resources

https://aws.amazon.com/blogs/architecture/compute-abstractions-on-aws-a-visual-story/
(Used for general understanding and quoted in the reading)
