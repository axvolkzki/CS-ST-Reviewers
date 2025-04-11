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

51. What are the primary advantagus of selecting a SaaS solution for business applications? (Chouse two)
Corplete cuntrol over the infrastructure
    - [ ] Automatic software updates and security patches
    - [ ] Accessibility from any device with an internet connection
    - [ ] Ability to deploy custom develapment environments
    - [ ] Minimal maintenance requirements
    - [ ] Lower initial setup costs

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Minimal maintenance requirements

        - Lower initial setup costs
    </details>

52. Which cloud storage solution is best suited for shared access to files across multiple virtual machines and applications?
    - A. Cold storage
    - B. File storage
    - C. Block storage
    - D. Object storage

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        File Storage

        Explanation: File storage provides a hierarchical structure with directories and files, making it ideal for shared access across multiple instances or applications. It is commonly used for file shares, content management systems, and distributed applications. Examples include Amazon EFS, Azure Files, and Google Filestore.

    </details>

53. Which cloud networking component acts as a security barrier between a VPC and external networks?
    - A. Firewall
    - B. Proxy Server
    - C. Load Balancer
    - D. Switch

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Firewall

        Explanation: 
        A Firewall controls incoming and outgoing network traffic based on security fules, ensuring network protection within cloud environment.
    </details>

54. Scenario: Your company has deployed an application in a VPC with two subnets: a public subnet and a private subnet. How would you configure access so that only instances in the public subnet can connect to the internet?
    - A. Enable VPC Peering with another VPC
    - B. Configure a route table to the Internet Gateway for the public subnet only
    - C. Use a VPN connection with static routus
    - D. Attach a second Internet Gateway

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Configure a route table to the Internet Gateway for the public subnet only

        Explanation: 
        To allow only the instances in the puhlic subnet to connect to the internet, you must configure the route table of the public subnet to include a route pointing to the Internet Gateway. This setup should not be applied to the private suhnet if internet access is to be denied.
    </details>

55. What is the primary benefit of using containerized applications in the cloud?
    - A. Eliminates the need for orchestration
    - B. Improves portability and resource efficiency
    - C. Requires dedicated physical servers
    - D. Runs only on virtual machines

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Improves portability and resource efficiency

        Explanation:
        Containers package applications with dependenties, making them portable across environments. They use fewer resources and start faster than virtual machines. Services like Amazon ECS, AWS Fargate, and Kubernetes (EKS, GKE, AKS) manage containers.
    </details>

56. Which of the following is an example of horizontal scaling in the AWS Cloud
    - A. Adding more RAM capacity to an EC2 instance.
    - B. Replacing an existing EC2 instance with a larger, more powerful one.
    - C. Increasing the compute capacity of a single EC2 instance to address the growing demands of an application.
    - D. Adding more EC2 instances of the same size to handle an increase in traffic.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Adding more EC2 instances of the same size to handle an increase in traffic.
    </details>

57. Which AWS feature will reduce the customer's total cost of ownership (TCO)?
    - A. Elastic computing.
    - B. Single tenancy.
    - C. Encryption.
    - D. Shared responsibility security model.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Elastic Computing
    </details>

58. Which of the following statements correctly describes a key difference between a Network Access Control List (NACL) and a Security Group?
    - A. Both NACLs and Security Groups are stateful and operate at the subnet level.
    - B. NACLs are stateful, whereas Security Groups are stateless.
    - C. NACLs operate at the instance level, while Security Groups operate at the subnet level.
    - D. NACLs operate at the subnet level and are stateless, while Security Groups operate at the instance level and are stateful.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        NACLs operate at the subnet level and are stateless, while Security Groups operate at the instance level and are stateful.
    </details>

59. Which characteristic distinguishes a public subnet from a private subnet in a VPC environment?
    - A. A public subnet's instances can communicate directly with the internet via an Internet Gateway, while a private subnet's instances cannot unless configured with additional resources like a NAT Gateway.
    - B. Private subnets cannot host any instances.
    - C. A private subnet can only include storage services, while a public subnet hosts compute resources.
    - D. A public subnet is always larger than a private subnet.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer:
        A public subnet's instances can communicate directly with the internet via an Internet Gateway, while a private subnet's instances cannot unless configured with additional resources like a NAT Gateway.

        Explanation: 
        Instances in a public subnet can directly connect to the internet if an Internet Gateway is configured. Private subnets require a NAT Gateway or similar service for internet access while keeping instances shielded from direct inbound internet traffic.
    </details>

60. A Japanese company hosts their applications on Amazon EC2 instances in the Tokyo Region. The company has opened new branches in the United States, and the US users are complaining of high latency. What can the company do to reduce latency for the users in the US while minimizing costs?
    - A. Building a new data center in the US and implementing a hybrid model.
    - B. Applying the Amazon Connect latency-based routing policy.
    - C. Deploying new Amazon EC2 instances in a Region located in the US.
    - D. Registering a new US domain name to serve the users in the US.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Deploying new Amazon EC2 instances in a Region located in the US.
    </details>

61. Which task is AWS responsible for in the shared responsibility model for security and compliance?
    - A. Encrypting data in transit.
    - B. Updating Amazon EC2 host firmware.
    - C. Updating operating systems.
    - D. Granting access to individuals and services.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Updating Amazon EC2 host firmware.

        Explanation: 
        AWS updates host firmware as part of its responsibility under the shared responsibility model, ensuring infrastructure security.
    </details>

62. A Philippine-based e-commerce company is migrating its customer database to AWS. Since the company collects and processes personal information, it must comply with the data Privacy Act of 2012. Which of the following are the company's responsibilities when handling personal data in AWS? (Choose TWO)
    - [ ] Require AWS to handle all data security and privacy compliance requirements.
    - [ ] Establish policies and procedures for processing personal information, including obtaining user consent.
    - [ ] Modify AWS's physical security controls to comply with Philippine data protection laws.
    - [ ] Ensure that AWS services are pre-configured to comply with the Data Privacy Act, requiring no additional configuration.
    - [ ] Implement appropriate access controls and encryption mechanisms to protect personal data.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Establish policies and procedures for processing personal information, including obtaining user consent.

        - Implement appropriate access controls and encryption mechanisms to protect personal data.
    </details>

63. A user is planning to launch two additional Amazon EC2 instances to increase availability. Which action should the user take?
    - A. Launch the instances as EC2 Reserved Instances in the same AWS Region and the same Availability Zone.
    - B. Launch the instances in multiple AWS Regions but in the same Availability Zone.
    - C. Launch the instances as EC2 Spot Instances in the same AWS Region but in different Availability Zones.
    - D. Launch the instances across multiple Availability Zones in a single AWS Region.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Launch the instances across multiple Availability Zones in a single AWS Region.
    </details>

64. The elasticity of the AWS Cloud enables customers to save costs when compared to traditional hosting providers. What can AWS customers do to benefit from the elasticity of the AWS Cloud? (Choose TWO)
    - [ ] Deploy your resources in another region.
    - [ ] Use Serverless Computing whenever possible.
    - [ ] Use Amazon EC2 Auto Scaling.
    - [ ] Deploy your resources across multiple Availability Zones.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer:
        -  Use Serverless Computing whenever possible.
        - Use Amazon EC2 Auto Scaling.
    </details>

65. What type of cloud storage is most suitable for storing large amounts of unstructured data?
    - A. Object storage
    - B. Block storage
    - C. Tape storage
    - D. File storage

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Block Storage

        Explanation: 
        Object storage is well suited for handling unstructured data like media files and backups.
    </details>

66. Which cloud networking component allows private subnet insances to access the internet without being publicly accessible?
    - A. Firewall
    - B. NAT Gateway
    - C. Internet Gateway
    - D. VPN

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        NAT Gateway

        Explanation: 
        A NAT Gateway enables outbound internet access for private subnet insatnces while keeping them hidden from public access.
    </details>

67. Which cloud networking component allows users to create an isolated network environment within a cloud provider?
    - A. Virtual Private Cloud (VPC)
    - B. Domain Name System (DNS)
    - C. Load Balancer
    - D. Content Delivery Network (CDN)

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Virtual Private Cloud

        Explanation: 
        A Virtual Private Cloud (VPC) enables users to create an isolated network environment within a cloud provider, allowing control over IP addressing, subnets, and security settings. AWS, Azure, and Google Cloud provide VPC services to manage cloud networking securely.
    </details>

68. Each AWS Region is composed of multiple Availability Zones. Which of the following best describes what an Availability Zone is?
    - A. It is a distinct location within a region that is insulated from « failures in other Availability Zones.
    - B. It is a data center designed to be completely isolated from other data centers in the same region.
    - C. It is a logically isolated network of the AWS Cloud.
    - D. It is a collection of data centers distributed in multiple countries.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        It is a distinct location within a region that is insulated from « failures in other Availability Zones.

        Explanation: 
        Availability Zones are isolated locations within a region that provide redundancy and prevent regional failures.
    </details>

69. Which subnet configuration is appropriate for hosting a database that should not be directly accessible from the internet in an AWS environment?
    - A. Private subnet with a NAT Gateway for outbound traffic
    - B. Private subnet with a direct Internet Gateway route
    - C. Public subnet with a direct Internet Gateway route
    - D. Public subnet with Elastic IP

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Private subnet with a NAT Gateway for outbound traffic

        Explanation: 
        Positioning the database in a private subnet restricts direct internet access, while a NAT Gateway allows necessary outbound network communication without exposing the database directly.
    </details>

70. Scenario: Due to a requirement for a critical application, you must ensure redundant data storage and quick application failover within the same geographic area. What's the most effective strategy using AWS infrastructure?
    - A. Utilize multiple Availability Zones within the same AWS Region
    - B. Distribute data across multiple global AWS Regions
    - C. Implement data peering across different Providers
    - D. Store data in multiple Edge Locations

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Utilize multiple Availability Zones within the same AWS Region

        Explanation: 
        Employing multiple Availability Zones within the same Region helps in providing redundancy and failover capabilities within the vicinity, offering an effective disaster recovery strategy.
    </details>

71. Which AWS feature enables secure, isolated network environments where you can launch resources in a virtualized environment and define subnets?
    - A. Elastic Load Balancer
    - B. Subnet Groups
    - C. VPC
    - D. Internet Gateway

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        VPC

        Explanation: 
        A VPC allows you to define an isolated network environment where you can launch AWS resources such as EC2 instances, define your own IP addressing, subnets, route tables, and security settings.
    </details>

72. Scenario: You are a cloud architect tasked with setting up a web application in a cloud environment. The application needs to be accessible publicly from the internet. Which component is essential for enabling this access, and why?
    - A. VPN Connection
    - B. VPC Peering
    - C. NAT Gateway
    - D. Internet Gateway

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Internet Gateway

        Explanation: 
        An Internet Gateway is necessary to allow resources within a VPC to communicate with the internet. It acts as a target for route tables within the VPC that provides the pathway for inbound and outbound traffic to the internet.
    </details>

73. What is the primary purpose of a primary key in a database table?
    - A. To create one-to-many relationships between tables
    - B. To store multiple data types in a single field
    - C. To uniquely identify each record in a table
    - D. To automatically generate indices for faster queries

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        To uniquely identify each record in a table

        Explanation: 
        The primary key is a field (or combination of fields) that uniquely identifies each row in a database table, ensuring that no two rows have the same primary key value.
    </details>

74. Which cloud computing service provides DNS resolution to route traffic efficiently between domain names and IP addresses?
    - A. AWS VPC Peering
    - B. AWS Route 53
    - C. AWS CloudFront
    - D. AWS Direct Connect

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        AWS Route 53

        Explanation:
        AWS Route 53 is a scalable and highly available DNS (Domain Name System) service that resolves domain names to IP addresses.
    </details>

75. Which of the following steps should be taken by a customer when conducting penetration testing on AWS?
    - A. Conduct penetration testing using Amazon Inspector, and then notify AWS support.
    - B. Request and wait for approval from AWS support, and then conduct testing.
    - C. Request and wait for approval from the customer's internal security team, and then conduct testing.
    - D. Notify AWS support, and then conduct testing immediately.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Request and wait for approval from AWS support, and then conduct testing.
    </details>

76. In the context of databases, what does the 'Consistency' property in ACID refer to?
    - A. Data is always available offline.- B. Every transaction is executed independently to prevent conflicts.
    - C. ll transactions are executed with the same priority.
    - D. The database remains in a valid state before and after the transaction.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        The database remains in a valid state before and after the transaction.

        Explantion:
        Consistency ensures that a database transaction cannot violate predefined database rules, keeping data in a valid state.
    </details>

77. Scenario: A multinational company is deploying a global application that requires compliance with local data residency regulations, ensuring data stays within specific geographic locations. Which AWS feature should be used to meet these requirements?
    - A. Edge Location
    - B. AWS Region
    - C. Availability Zone
    - D. VPC Peering

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer:
         AWS Region
    </details>

78. Which storage type would be most appropriate for a centralized network drive that needs to support multiple read/write requests from various servers?
    - A. Object storage
    - B. Block storage
    - C. Tiered storage
    - D. File Storage

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        File Storage

        Explanation:
        File Storage is structured hierarchically and is suitable for situations like network attached storage (NAS), allowing multiple client to access files concurrently.
    </details>

79. The identification process of an online financial services company requires that new users must complete an online interview with their security team. The completed recorded interviews are only required in the event of a legal issue or a regulatory compliance breach. What is the most cost-effective service to store the recorded videos?
    - A. Amazon EBS.
    - B. AWS Marketplace.
    - C. S3 Intelligent-Tiering.
    - D. Amazon S3 Glacier Deep Archive.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer:
        Amazon S3 Glacier Deep Archive
    </details>

80. Which of the following is a key characteristic of cloud computing that allows users to provision resources as needed, without human intervention?
    - A. Measured Service
    - B. On-Demand Self-Service
    - C. Resource Pooling
    - D. Braod Network Access

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer:
        On-Demand Self-Service
    </details>

81. Scenario: You are designing a relational database and need to create a relationship between two tables: 'Orders' and 'Customers'. Which key would you use in the 'Orders' table to establish a relationship to the 'Customers' table?
    - A. Composite key
    - B. Primary key
    - C. Foreign key
    - D. Secondary key

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer:
        Foreign key

        Explanation: 
        A foreign key in the 'Orders' table is used to establish a link to the primary key in the 'Customers' table, defining the relationship between orders and customers.
    </details>

82. Scenario: A financial services company is highly regulated and needs to manage sensitive customer data with stringent compliance requirements. They also handle peak workloads periodically for data analysis, which requires additional computing resources temporarily. Which cloud deployment model would best suit their needs?
    - A. Private cloud
    - B. Community cloud
    - C. Public cloud
    - D. Hybrid cloud

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Hybrid Cloud

        Explanation: 
        A hybrid cloud model allows the company to keep sensitive data and critical operations on a private cloud for better control and compliance, while leveraging public cloud resources during peak workloads for scalability.
    </details>

83. What is the main benefit of attaching security groups to an Amazon RDS instance?
    - A. Controls what IP address ranges can connect to your database instance.
    - B. Manages user access and encryption keys.
    - C. Distributes incoming traffic across multiple targets
    - D. Deploys SSL/TLS certificates for use with your database instance.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Controls what IP address ranges can connect to your database instance.

        Explanation: Security Groups restrict database access by allowing only specific IP ranges to connect, improving security.
    </details>

84. Which cloud compute model allows applications to run without provisioning or managing servers, scaling automatically based on demand?
    - A. Virtual Machines
    - B. Serverless Computing
    - C. Dedicated Servers
    - D. Containers

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Serverless Computing
    </details>

85. Which type of cloud storage is best suited for storing unstructured data, such as images and videos, in a scalable manner?
    - A. Block Storage
    - B. Object Storage
    - C. File Storage
    - D. Relational Database

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Object Storage

        Explanation: 
        Object Storage is deal for storing unstructured data like images, videos, and backups. It provides scalability, durability, and accessibility through APIs, making it suitable for cloud environments. Services like Amazon S3, Azure Blob Storage, and Google Cloud Storage use object storage.
    </details>

86. Which component connects a VPC to the internet, allowing public access?
    - A. Network Firewall
    - B. Internet Gateway
    - C. NAT Gateway
    - D. VPN Gateway

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Internet Gateway
    </details>

87. Which of the following are challenges of cloud adoption? (Choose two)
    - [ ] Cost inefficiency
    - [ ] Rapid deployment
    - [ ] Complexity and lack of expertise
    - [ ] Data security and privacy

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Complexity and lack of expertise
        
        - Data security and privacy
    </details>

88. Which of the following security-related actions are available at no cost?
    - A. Accessing forums, blogs, and whitepapers.
    - B. Attending AWS classes at a local university.
    - C. Contacting AWS Professional Services to request a workshop.
    - D. Calling AWS Support.
    - E. Accessing forums, blogs, and whitepapers.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Accessing forums, blogs, and whitepapers.
    </details>

89. Scenario: A startup is developing a new mobile application. They have limited budget constraints and need to rapidly deploy and scale their application as demand grows. Which cloud model should they consider and why?
    - A. Community cloud, for shared resources with similar businesses
    - B. Public cloud, for cost-efficiency and scalability
    - C. Private cloud, for better security and control
    - D. Hybrid cloud, for optimal control

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Public cloud, for cost-efficiency and scalability

        Explanation:
        Public Clouds provide a cost-effective solution for startups, enabling rapid deployment and on demand scalability without the need for significant upfront investment in IT infrastructure.
    </details>

90. Scenario: A large multinational corporation wants to transition its HR systems to the cloud to improve accessibility for its global workforce, but its infrastructure also includes legacy applications that are not cloud compatible. What cloud deployment strategy should be adopted?
    - A. Hybrid cloud, to integrate existing infrastructure with new cloud services
    - B. Public cloud, to replace legacy systems completely
    - C. Private cloud, to retain control of all HR applications
    - D. Multicloud, to utilize services from multiple cloud providers

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Hybrid cloud, to integrate existing infrastructure with new cloud services

        Explanation: 
        A hybrid cloud deployment allows the corporation to transition part of their infrastructure to the cloud for improved accessibility while maintaining legacy systems onpremises or within a private cloud, integrating both for a seamless operation.
    </details>

91. Scenario: You are asked to design a network architecture for an application that will have both web facing components and database components. Which of the following architectural choices best represents the purpose and benefits of using both public and private subnets?
    - A. Deploy everything in a private subnet to eliminate internet traffic concerns.
    - B. Use public subnets for web facing components to allow direct internet access, and private subnets for databases to enhance security by limiting inbound internet traffic.
    - C. Use public subnets for databases to ensure redundancy across regions.
    - D. Deploy both components in a public subnet for easier access and management.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Use public subnets for web facing components to allow direct internet access, and private subnets for databases to enhance security by limiting inbound internet traffic.

        Explanation: 
        In a typical architectural setup, webfacing components are deployed in public subnets to ensure they can serve internet requests, while sensitive components like databases are placed in private subnets to restrict their exposure to the internet.
    </details>

92. Which AWS service is best suited for launching and managing virtual machines?
    - A. EC2
    - B. Lambda
    - C. RDS
    - D. S3

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        EC2

        Explanation: 
        Amazon EC2 (Elastic Compute Cloud) is designed for running and managing virtual servers.
    </details>

93. Which cloud scaling strategy involves adding or removing instances dynamically to handle changes in workload demand?
    - A. Static Scaling
    - B. Horizontal Scaling
    - C. Manual Scaling
    - D. Vertical Scaling

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Horizontal Scaling

        Explanation:
        Horizontal scaling (scaling out/in) adds or removes instances dynamically to meet workload demands. This approach improves availability, fault tolerance, and cost efficiency. It is commonly implemented using Auto Scaling Groups in AWS, VM Scale Sets in Azure, and Managed Instance Groups in GCP.
    </details>

94. Which cloud computing characteristic allows resources to be automatically allocated based on demand?
    - A. Elasticity
    - B. Virtualization
    - C. High Availability
    - D. Fault Tolerance

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Elasticity 
    </details>

95. What is a key benefit of using Auto Scaling in a cloud environment?
    - A. Eliminates the need for load balancers.
    - B. Prevents application scaling based on demand.
    - C. Reduces the need for a Virtual Private Cloud (VPC).
    - D. Ensures optimal resource allocation by automatically adjusting compute capacity.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Ensures optimal resource allocation by automatically adjusting compute capacity.

        Explanation:
        Auto Scaling dynamically adjusts the number of instances to match demand, ensuring high availability and cost-efficiency. It works with Auto Scaling Groups (ASG) and Load Balancers in AWS to automatically increase or decrease instances based on traffic patterns.
    </details>

96. What is the key benefit of autoscaling in cloud environments?
    - A. Fixed capacity planning
    - B. Improved object storage
    - C. Reduced network latency
    - D. Automated workload management

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Automated workload management

        Explanation: 
        Autoscaling allows resources to scale automatically in response to demand, optimizing workload management.
    </details>

Feedback

97. Scenario: A technology startup is developing a machine learning application but does not want to invest in maintaining the hardware infrastructure. They do need a scalable environment for testing and deploying their models. Which cloud service model should they utilize?
    - A. CaaS
    - B. SaaS
    - C. PaaS
    - D. laaS

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer:
        PaaS

        Explanation: 
        PaaS offers the ideal environment for development, testing, and deployment of applications like machine learning models by providing the platform and resources, such as model training services, without the overhead of infrastructure maintenance.
    </details>

98. One of the most important AWS best-practices to follow is the cloud architecture principle of elasticity. How does this principle improve your architecture's design?
    - A. By automatically provisioning the required AWS resources based on changes in demand.
    - B. By automatically scaling your on-premises resources based on changes in demand.
    - C. By automatically provisioning the required AWS resources based on changes in demand.
    - D. By reducing interdependencies between application components wherever possible.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        By automatically provisioning the required AWS resources based on changes in demand.
    </details>

99. What is a primary advantage of cloud computing compared to traditional IT infrastructure?
    - A. On premises management
    - B. Fixed costs
    - C. Increased latency
    - D. Trade fixed expense for variable expense

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        Trade fixed expense for variable expense

        Explanation:
        Instead of having to invest heavily in data centers and servers before you know how you're going to use them, you can pay only when you consume computing resources, and pay only for how much you consume.
    </details>

100. You have been tasked with auditing the security of your VPC. As part of this process, you need to start by analyzing what inbound and outbound traffic is allowed on your EC2 instances. What two parts of the VPC do you need to check to accomplish this task?
    - A. Network ACLs and Subnets.
    - B. Security Groups and Network ACLs.
    - C. Network ACLs and Traffic Manager.
    - D. Security Groups and Internet Gateways.

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer:
        Security Groups and Network ACLs.
    </details>