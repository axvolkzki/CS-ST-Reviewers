1. What is the primary difference between vertical scaling and horizontal scaling in clod environment?
    - A. Horizontal scaling involves replacing servers with larger ones.
    - B. Vertical scaling involves cloud bursting strategies.
    - C. Vertical scaling is less flexible compared to horizontal scaling.
    - D. Vertical scaling 

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer:  Vertical scaling adds more resources to an existing server, while horizontal scaling adds more servers.

        Explanation: Vertical scaling (scaling up) involves increasing resources in an existing server, whereas horizontal scaling (scaling out) involves more infrastructure units like additional servers.
    </details>

2. Which AWS service can run a managed PostgresSQL database that provides online transaction processing (OLTP)?
    - A. Amazon EMR
    - B. Amazon Athena
    - C. Amazon RDS
    - D. Amazon DynamoDB

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Amazon DynamoDB
    </details>

3. Scenario: An educational institution needs a cloud solution that allows students and faculty to access resources from anywhere, while retaining specific data onpemises for privacy. Which model would be best for their needs?
    - A. Private Cloud
    - B. Hybrid Cloud
    - C. Public Cloud
    - D. Community Cloud

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Hybrid Cloud
    </details>

4. What roles does a Route Table play in a clood network?
    - A. Encrypts data during transit
    - B. Define rules for directing traffic within a network
    - C. Caches web content for faster access
    - D. Automatically scales applications

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Defines rules for directing traffic within a network

        Explanation: 
        A Route Table is used in a VPC to determine how network traffic is forwarded between subnets or to external networks.
    </details>

5. What is the primary function of an Elastic Load Balaner (ELB)?
    - A. Stores data in a distributed manner
    - B. Encrypts network traffic
    - C. Distributes traffic across multiple instances
    - D. Manages containerized application

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Distributes traffic across multiple instances

        Explanation: 
        ELB automatically distributes incoming network traffic to multiple backend instances, ensuring high availability and reliability.
    </details>

6. Scenario: To ensure high availability for critical application, you want to deploy instances in multiple physically separated locations within the same AWS region. What should you use to achive this setup?
    - A. Subnets
    - B. Elastic Load Balancer
    - C. Edge Locations
    - D. Availability Zone

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Availability Zone

        Explanation: 
        Availability Zones are physically distinct locations within an AWS Region designed to provide redundancy and resilience. Deloying instances across multiple Availability Zones helps ensure high availability and fault tolerance.
    </details>

7. Which cloud computing characteristic allows resources to be automatically adjusted based on demand?
    - A. Broad Network Access
    - B. Rapid Elasticity
    - C. On-Demand Self-Service
    - D. Resource Pooling

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Rapid Elasticity

        Explanation: 
        Rapid Elasticity ensures that cloud resources can be scaled up or down dynamically based on workload demand, optimizing performance and cost efficiency.
    </details>

8. What is "Cloud Elasticity"?
    - A. Improved data analytics
    - B. The ability to quickly scale resources up or down
    - C. Constant resource allocation
    - D. Redundant storage options

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        The ability to quickly scale resources up or down

        Explanation: 
        Cloud Elasticity refers to the ability to dynamically allocate and deallocate resources based on current demand.
    </details>

9. Which scaling method involves adding more virtual machines or instances to handle increased traffic?
    - A. Horizontal Scaling
    - B. Vertical Scaling
    - C. Static Scaling
    - D. Manual Scaling

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Horizontal Scaling

        Explanation: 
        Horizontal Scaling (scaling in/out) adds or removes instances to handle traffic dynamically. Auto Scaling Groups in AWS enable automatic horizontal scaling.
    </details>

10. Scenario: You have an application running on an EC2 instance within a public subnet of a VPC. This application should interact with a databse in a private subnet. How do you ensure secure communication between the two without exposing the database to the internet?
    - A. Use VPN connection between both instances
    - B. Add the application's security group within the database's security group rules.
    - C. Configure DCHP options to direct traffic to a direct connection.
    - D. Assign a public IP to the database.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Add the application's security group within the database's security group rules.

        Explanation: 
        By allowing inbound rules in the databse's security group for the security group of the application instance, you enable secure communication between the two while keeping the database inaccessible from the internet.
    </details>

11. Scenario: You organization wants to develeop a custom application but lacks the infrastructure to suport it internally. They need control over the application environment, including the operating system and runtime. Which cloud service model should they choose?
    - A. IaaS
    - B. SaaS
    - C. PaaS
    - D. FaaS

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        IaaS

        Explanation: 
        IaaS provides the necessary infrastructure (virtualized computing resource) that allows organizations to manage applications, operating systems, and runtime environments, offering greater control than PaaS or SaaS.
    </details>

12. Which advantages are associated with using cloud-based storage solutions? (Choose two)
    - [ ] Remote access and collaboration
    - [ ] Increased thermal output
    - [ ] Cost efficiency
    - [ ] Scalability
    - [ ] Limited accessibility
    - [ ] Data redundancy and replication

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Scalability & Data redendancy and replication
    </details>

13. A startup company in operating on limited funds and is extremely concerned about cost overruns. Which of the below options can be used to notify the company when their monthly AWS bill exceeds $2000? (Choose two)
    - [ ] Enable AWS Cost Anomaly Detection to monitor and alert on unexpected spending patterns.
    - [ ] Configure the Amazon Conncect Service yo alert the company when the threshold is exceeded.
    - [ ] Configure the Amazon Simple Email Service to send billing alerts to their email address on a daily basis.
    - [ ] Set up a CloudWatch billing alarm that triggers an SNS notification when the threshold is exceeded.
    - [ ] Configure the AWS Budgets Service to alert the company when the threshold is exceeded.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Set up a CloudWatch billing alarm that triggers an SNS notification when the threshold is exceeded.

        - Configure the AWS Budgets Service to alert the company when the threshold is exceeded.
    </details>

14. Which service model typically provides the highest level of control for an organization?
    - A. IaaS
    - B. PaaS
    - C. SaaS
    - D. DaaS

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        IaaS

        Explanation: 
        Infrastructure as a Service (IaaS) offers the most control over IT resources, including computing, storage, and networking.
    </details>

15. Which type of storage is typically used for application that require low latency access to raw devices, such as database?
    - A. File Storage
    - B. Object Storage
    - C. Block Storage
    - D. Tape Storage

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Block Storage
    </details>

16. Which of the following cloud service types typically abstracts the hardware layer entirely from the end user?
    - A. IaaS
    - B. FaaS
    - C. PaaS
    - D. SaaS

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        SaaS
    </details>

17. Which advanced cloud storage feature helps reduce storage costs by automatically moving data between different storage classes based on predefined rules?
    - A. Encryption
    - B. Compression
    - C. Data Duplication
    - D. Storage Lifecycle Polciies

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Storage Lifecycle Policies
    </details>

18. What benefits do Infrastructure as a Service (IaaS) models offer? (Choose two)
    - [ ] Flexibility to scale hardware needs
    - [ ] Pay-as-you-go pricing model for resource efficiency
    - [ ] Complete control over the underlying infrastructure
    - [ ] High upfront capital expenditure
    - [ ] Reduced maintenance burden for physical hardware
    - [ ] Full application deployment stack management


    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Flexibility to scale hardware needs

        - Complete control over the underlying infrastructure
    </details>

19. Which of the following is a key benefit of using AWS Lambda?
    - A. Automatically scales with incoming requests
    - B. Charges based on pre-allocated server capacity
    - C. Automatically scales with incoming requests
    - D. Runs only on dedicated EC2 instances
    - E. Requires provisioning and managing servers

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Automatically scales with incoming requests

        Explanation: 
    </details>

20. Which of the following best describes the "Cloud Bursting"?
    - [ ] An attack on cloud infrastructure
    - [ ] Using the cloud to handle additinal load when local resources exceed capacity
    - [ ] Migrating an application from one cloud provider to another
    - [ ] Overloading cloud services causing failures

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Using the cloud to handle additinal load when local resources exceed capacity

        Explanation:
        - Cloud Bursting is a technique used to leverage cloud resources during peak demand period to complement on-premises capacity.
    </details>

21. What are key differences between relational and NoSQL databases (Choose two)
    - [ ] NoSQL databases are typically more scalable for big data applications than relational databases.
    - [ ] NoSQL databases can handle unstructured data more efficiently.
    - [ ] Relational databases use SQL, whereas NoSQL databases might use other query methods.
    - [ ] Relational databases enforce ACID transactions strictly, while NoSQL databases often prioritize scalability over strict consistency.
    - [ ] NoSQL is schema-based, while relational is schemaless.
    - [ ] Relational databases are best suited for hierarchical data stores.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - NoSQL databases can handle unstructured data more efficiently.

        - Relational databases use SQL, whereas NoSQL databases might use other query methods.
    </details>

22. Which deployment model involves a combination of on premises infrastructure and public cloud services?
    - A. Hybrid cloud
    - B. Public cloud
    - C. Community cloud
    - D. Private cloud

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Hybrid Cloud

        Explanation:
        Hybrid Cloud combines on premises, private cloud, thirdparty, public cloud services.
    </details>

23. Which cloud storage type is ideal for applications that require low-latency access to frequently changing data, such as databases and virtual machines?
    - A. Object storage
    - B. Block storage
    - C. Cold storage
    - D. Block storage
    - E. File storage

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Block Storage
    </details>

24. A small business is looking to use a comprehensive solution for their email and office productivity needs without developing or maintaining any software. Which cloud service model is most suitable for their requirements?
    - A. laaS
    - B. CaaS
    - C. PaaS
    - D. SaaS

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        SaaS

        Explanation: 
        SaaS provides a fully managed software solution that typically runs in the cloud and is accessed over the internet, ideal for office and email services without the overhead of managing or maintaining software.
    </details>

25. Which cloud computing benefit ensures that applications remain accessible even during hardware failures?
    - A. Security
    - B. Scalability
    - C. Cost Savings
    - D. Reliability

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Cloud providers implement high availability and redundancy mechanisms, ensuring applications stay online even if infrastructure components fail.
    </details>

26. Which storage service can be used as a low-cost option for hosting static websites?
    - A. Amazon Glacier.
    - B. Amazon DynamoDB.
    - C. Amazon Simple Storage Service (Amazon S3).
    - D. Amazon Elastic File System (Amazon EFS).

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Amazon S3

        Explanation: 
        Amazon S3 provides a low-cost, scalable option for hosting static websites without requiring dedicated compute resources.
    </details>

27. What does the "Principle of Least Privilege" refer to?
    - A. All trusted IAM users should have access to any AWS service in the respective AWS account.
    - B. IAM users should not be granted any permissions; to keep your account safe.
    - C. All IAM users should have at least necessary permissions to access the core AWS services.
    - D. You should grant users only the permission they need when they need them and nothing more.
    - E. You should grant your users only the permission they need when they need them and nothing more.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        You should grant users only the permission they need when they need them and nothing more.
    </details>

28. What is the primary advantage of using auto-scaling in the cloud?
    - A. Ensures optimal resource allocation based on demand
    - B. Prevents application scaling
    - C. Reduces the need for a Virtual Private Cloud (VPC)
    - D. Eliminates the need for load balancers

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Ensures optimal resource allocation based on demand

        Explanation:
        Auto-scaling automatically adjusts computing resources to match workload demand, ensuring high availability and cost efficiency.
    </details>

29. Amazon EC2 instances are conceptually very similar to traditional servers. However, using Amazon EC2 server instances in the same manner as traditional hardware server instances is only a starting point. What are the main benefits of using the AWS EC2 instances instead of traditional servers? (Choose TWO)
    - [ ] Can be scaled manually in a shorter period of time.
    - [ ] Prevents unauthorized users from getting into your network.
    - [ ] Improves Fault-Tolerance
    - [ ] Provides your business with a seamless remote accessibility
    - [ ] Provides automatic data backups.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Can be scaled manually in a shorter period of time.
        
        - Improves Fault-Tolerance 
    </details>

30. Which of the following are characteristics of a well-defined primary key in a relational database design? (Choose two)
    - [ ] Values are unique across the table
    - [ ] Values can be null
    - [ ] Can be changed frequently to maintain flexibility
    - [ ] Used to enforce entity integrity
    - [ ] Consists of a single column
    - [ ] Minimal and contains only necessary fields

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Values are unique across the table

        - Minimal and contains only necessary fields
    </details>

31. Which of the following are advantages often associated with NoSQL databases? (Choose two)
    - [ ] Built for SQL queries
    - [ ] Can be easily scaled horizontally
    - [ ] Strict adherance to ACID properties
    - [ ] Optimized for high-velocity, large-scale data processing
    - [ ] Typically better suited for handling unstructures or semi-structured data
    - [ ] Schema flexibility

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Can be easily scaled horizontally

        - Schema flexibility
    </details>

32. Under the AWS shared responsibility model, which of the following activities are the customer's responsibility? (Select TWO)
    - [ ] Training the data center staff.
    - [ ] Configuring Network Access Control Lists (ACL).
    - [ ] Maintaining environmental controls within a data center.
    - [ ] Encrypting data on the client-side.
    - [ ] Patching operating system components for Amazon Relational Database Server (Amazon RDS).

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Configuring Network Access Control Lists (ACL).

        - Encrypting data on the client-side.
    </details>

33. A company needs to host a big data application on AWS using EC2 instances. Which of the following AWS Storage services would they choose to automatically get high throughput to multiple compute node?
    - A. S3
    - B. Amazon Elastic Block Store.
    - C. Amazon Elastic File System.
    - D. AWS Storage Gateway.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Amazon Elastic File System
    </details>

34. You have noticed that several critical Amazon EC2 instances have been terminated. Which of the following AWS services would help you determine who took this action?
    - A. AWS Trusted Advisor.
    - B. AWS CloudTrail
    - C. Amazon Inspector
    - D. EC2 Instance Usage Report

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
    </details>

35. Which networking device is primarily responsible for directing data packets between different networks by using IP addresses?
    - A. Bridge
    - B. Hub
    - C. Router
    - D. Switch

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Router

        Explanation:
        Routers operate at the network layer of the OSI model and use IP addresses to determine the best path for forwarding packets between networks.
    </details>

36. Scenario: You need to open port 22 for a web server instance hosted within your VPC, but you want to limit access to only a specific set of IP addresses representing your office network. How should you configure the security group rule?
    - A. Open port 22 to the default VPC
    - B. Open port 22 to the specific CIDR block of your office's external IP range
    - C. Open all ports to the specific CIDR block of your office
    - D. Open port 22 to 0.0.0.0/0

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Open port 22 to the specific CIDR block of your office's external IP range

        Explanation: By setting the inbound rule for port 22 to the specific CIDR block of your office network, you ensure that only machines coming from the specified IP address range can access the web server.
    </details>

37. Which cloud networking component enables organizations to create an isolated network environment within a public cloud?
    - A. Virtual Private Cloud (VPC)
    - B. Content Delivery Network (CDN)
    - C. API Gateway
    - D. Load Balancer

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Virtual Private Cloud

        Explanation:
        A VPC (Virtual Private Cloud) allows organizations to create a logically isolated network within a public cloud provider, defining subnets, security policies, and access controls.
    </details>

38. Which service model is most appropriate for a company that wants to deploy a web application without managing the underlying hardware or software stack, but still wants to develop custom features for their application?
    - A. LaaS
    - B. PaaS
    - C. SaaS
    - D. MPLS

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        PaaS

        Explanation: PaaS provides a platform allowing developers to build, deploy, and manage applications without dealing with the underlying infrastructure, while still offering customization of the application features.
    </details>

39. Scenario: A database server in your VPC must be secured so that it only accepts connection requests from web servers within the same VPC. How would you configure the Security Group to accomplish this?
    - A. Deny all inbound traffic
    - B. Allow inbound traffic from a CIDR block that includes the entire internet
    - C. Set inbound rules to allow traffic from the default security group of the VPC
    - D. Allow inbound traffic only from the IP address range of the web server security group

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Allow inbound traffic only from the IP address range of the web server security group

        Explanation: To secure the database server, the Security Group should have inbound rules that allow traffic only from the web server instances, identified by their security
        group ID or IP address range.
    </details>

40. What are key characteristics of object storage? (Choose two)
    - [ ] Requires a fixed block size for data storage
    - [ ] Typically used for backup, archiving, and cloud storage
    - [ ] Scalable, with metadata attached to each object
    - [ ] Suitable for large amounts of unstructured data
    - [ ] Accessed through low-level storage protocols
    - [ ] Hierarchical file structure
    
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Scalable, with metadata attached to each object

        - Suitable for large amounts of unstructured data
    </details>

41. Which cloud storage feature ensures that data remains accessible and protected from loss, often measured in terms of "nines" (e.g., 99.999999999%)?
    - A. Compression
    - B. Tiered Storage
    - C. Data Availability and Durability
    - D. Data Deduplication

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Data Availability and Durability
    </details>

42. Which cloud security feature protects applications by filtering unwanted traffic based on pre-defined rules?
    - A. Load Balancer
    - B. Proxy Server
    - C. Firewall
    - D. VPN

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Firewall

        Explanation: 
        A Firewall monitors and controls incoming and outgoing traffic based on security rules, protecting cloud resources from unauthorized access.
    </details>

43. When launching an EC2 instance, which of the following network-related configurations can be defined? (Choose two)
    - [ ] The specific AWS region for the instance
    - [ ] The security group for controlling inbound/outbound rules
    - [ ] The environmental zone
    - [ ] The specific subnet within the VPC
    - [ ] Assigning a public or private IP address
    - [ ] The physical host placement

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - The security group for controlling inbound/outbound rules

        - The specific subnet within the VPC
    </details>

44. A user is planning to launch two additional Amazon EC2 instances to increase availability. Which action should the user take?
    - A. Launch the instances across multiple Availability Zones in a single AWS Region.
    - B. Launch the instances as EC2 Reserved Instances in the same AWS Region and the same Availability Zone.
    - C. Launch the instances as EC2 Spot Instances in the same AWS Region, but in different Availability Zones.
    - D. Launch the instances in multiple AWS Regions, but in the same Availability Zone.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        A. Launch the instances across multiple Availability Zones in a single AWS Region.

        Explanation: 
        Launching instances across multiple Availability Zones increases availability by preventing failures in a single zone from affecting all instances.
    </details>

45. Which type of cloud database is best suited for high-speed transactions and structured data with relationships between tables?
    - A. Object storage
    - B. NoSQL database
    - C. File storage
    - D. Relational database

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Relational Database

        Explanation: 
        Relational databases (RDBMS) store structured data with tables, rows, and columns, enforcing relationships between them using primary and foreign keys. They are optimized for high-speed transactions and support SQL queries. Examples include Amazon RDS, Azure SQL Database, and Google Cloud SQL.
    </details>

46. Scenario: You are designing a customer table for a new ecommerce platform. Which of the following would be the most suitable choice for a primary key?
    - A. Customer's last name
    - B. Autoincrementing customer ID
    - C. Postal code
    - D. Customer's email address

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Autoincrementing customer ID
    </details>

47. What is the purpose of a Virtual Private Cloud (VPC)?
    - A. To enhance inhouse server capabilities
    - B. To serve DNS queries efficiently
    - C. To provide a private cloud on onpremises hardware
    - D. To create a secure network within a public cloud

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        A VPC enables the creation of a logically isolated network within a public cloud environment.
    </details>

48. What is the primary function of a Content Delivery Network (CDN)?
    - A. Storing data permanently in cloud storage
    - B. Caching and distributing web content closer to users
    - C. Encrypting network traffic
    - D. Managing virtual machines in the cloud

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Caching and distributing web content closer to users

        Explanation:
        A CDN (Content Delivery Network) stores cached content on edge servers located closer to users, reducing latency and improving website performance. Examples include AWS CloudFront, Azure CDN, and Google Cloud CDN.
    </details>

49. Which clooud networking component routes traffic efficiently within a VPC?
    - A. Virtual Router
    - B. DNS Resolver
    - C. Internet Gateway
    - D. Firewall

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Virtual Router

        Explanation:
        A Virtual Router dynamially routes traffic within a VPC and between networks, ensuring efficient communication.
    </details>

50. Snenario: A startup company needs to minimize latency for its users located in Australio and New Zealand. Which AWS Region is most suitable for deploying their application?
    - A. South America (Sao Paulo)
    - B. Asia Pacific (Sydney)
    - C. EU (Ireland)
    - D. US East (N. Virginia)

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Asia Pacific (Sydney)

        Explanation: 
        Deploying in the Asia Pacific (Sydney) Region will likely provide the lowest latency for users in Australia and New Zealand, as it's geographically closer to their location.
    </details>