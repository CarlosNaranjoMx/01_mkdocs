# AWS


## 3 cloud computing
```mermaid
flowchart TD
    G(Cloud Computing) --> H(self-service)
    G --> J(on-demand)
    G --> K("Trade capital expense (CAPES) for operational expense (OPEX)")
```
```mermaid
flowchart TD
    G(AWS Cloud) --> H(The shared responsibility model)
    G --> I(What defines the distribution of responsibilities for security in the AWS Cloud?)
    G --> J(The shared Responsibility Model)
```
```mermaid
flowchart TD
    G(Which Global Infrastructure identity is composed of one or more discrete data centers with redundant power, networking, and connectivity, and are used to deploy infrastructure?)
```

## 4 IAM Security tool
```mermaid
flowchart TD
    G(IAM Security tool) --> H("IAM Policies (jsons)")
    G --> I(IAM  Credentias report)
    G --> J(not root credentials)
    G --> K(Assigning users proper IAM Policies)
```
```mermaid
flowchart TD
    G(IAM Security tool) --> H("MFA ")
```

## 7 Elastic Load Balancing & Auto Scaling Groups

```mermaid
flowchart TD
    G(High Availability) --> H(thriving)
```
```mermaid
flowchart TD
    G(Network Load Balancer) --> H(hundred of thousand)
    G --> |no equal| I
    I(Aplication Load Balancer) --> J(Http & https)
```
```mermaid
flowchart TD
    G(Auto Scaling Strategy) --> |no equal| H(Active Scaling)
```
```mermaid
flowchart TD
    G(Load Balancers) --> |no equal| H(Auto Scaling Groups)
```
```mermaid
flowchart TD
    G(Vertical Scaling) --> H(size increase)
```
```mermaid
flowchart TD
    G(Auto Scaling Groups) --> H(scale-in scale-out)
    G --> H(No change EC2 types)
```
## 8 Amazon S3
```mermaid
flowchart TD
    G(Amazon S3) --> H(buckets)
```
```mermaid
flowchart TD
    G(Amazon Glacier Deep Archives) --> H(cost-effective option)
```
```mermaid
flowchart TD
    G(AWS Storage Gateway) --> H(hybrid cloud storage)
    G --> H(on-premises)
```
```mermaid
flowchart TD
    G(Snowball Edge) --> H(move petabytes)
```

```mermaid
flowchart TD
    G(AWS CLI or AWS API) --> H(Access Keys)
```

```mermaid
flowchart TD
    G(AWS Snowcone) --> H(edge computing and data transfer device, 8 TB of usable storage)
```
```mermaid
flowchart TD
    G(storage class) --> H(Lifecycle Rules)
```
## 14 Cloud Watch
```mermaid
flowchart TD
    G(Cloud Watch) --> H(Monitoring every service, centralizes the logs from all of your systems, applications, and AWS services)
    G --> I(Cloud Watch Alarms, notifications of a metrics)
    G --> J(X-Ray, analyze an debug production)
    
```
```mermaid
flowchart TD
    N(Cloud Watch) --> L(CodeGuru, service automatically analyzes code and provide performance recommendations)
    N --> M(AWS Healt Dashboard, remediation guidance)
    N --> K(Cloud Trail, inspect, audit and record events and API callas made within your AWS account, investigate first if )
```
## 15 Network Access Control List (NACL)
- NAT Gateways, allow your instances in your private subnet to access the Internet while remaining private
- public and private subnet
- Site-toSite VPN, it's not public
- Internet gateway, horizontally scaled, redundant, and highly available VPC component
- AWS Direct Connect, makes it easy to establish a dedicated private network connection
- VPC Peering, communicate with each other
- VPC, (virtual private cloud)
- Transit Gateway, connect hundred of VPC

## 16 RDS, data at rest
- RDS, data at rest
- Macie, discover and protect sensitive data in AWS
- WAF Web Application firewall, protect against web exploits
- SSL y TLS (ACM) Certificate Manager
- The customer, firewall and configuration EC2 Instances
- Detective, find the root of potential security issues
- Inspector, automated security assessment service, helps to improve security and compliance of applications
- Artifact find on-demand access to AWS compliance documentation
- Penetration Testing is allowed without prior on 8 services. DDoS, port flooding and protocol flooding are examples of prohibited activities
- Security Hub, centrall automate security checks
- KMS, easily create and control the keys
- Access the billing dashboard not require the root user
- Shield, safeguard running aplications from DDoS attacks
- GuardDuty,  is a threat detection service that continuously monitors for malicious activity and unauthorized behavior 
- Losing your MFA device not contact AWS abuse Team ¿
- The situations where you should contact the AWS Abuse team are: Spam, Port scanning, DoS or DDoS attacks, Intrusion attempts, Hosting objectionable or copyrighted content, Distributing malware.