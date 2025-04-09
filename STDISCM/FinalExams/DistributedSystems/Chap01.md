# Final Exam Reviewer (Mock Test)

## Distributed Systems Chapter 1
***Mode: HARD | Items: 30 | Topic Coverage:***

***Credits: Letty***

### Multiple Choice
1. Which of the following best reflects a fully distributed system?
    - A. Several independent servers that do not interact
    - B. A set of tightly connected computers that hide their locations from the user
    - C. A centralized service that caches results for fast access
    - D. A cloud service with a single backend but replicated interface

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: B

        Distributed systems hide physical separation.
    </details>

2. What is the main difference between decentralized and distributed systems?
    - A. Distributed systems don’t require networking
    - B. Decentralized systems must always use shared memory
    - C. Distributed systems are more about coordination and integration
    - D. Decentralized systems always perform better

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        Distributed systems focus on coordinated work
    </details>

3. What does "distribution transparency" mainly try to achieve?
    - A. Allow users to control server connections directly
    - B. Hide the underlying complexity of the system’s structure
    - C. Increase the number of replicated resources
    - D. Eliminate latency in network communication

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: B

        Main goal is to hide complexity.
    </details>

4. Which type of transparency would ensure that users don’t notice when multiple users are accessing the same file?
    - A. Replication Transparency
    - B. Access Transparency
    - C. Concurrency Transparency
    - D. Location Transparency

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        Concurrency hides conflicts when multiple users access. 
    </details>

5. Which of the following is a disadvantage of full distribution transparency?
    - A. It decreases fault tolerance
    - B. It hides failures too effectively, increasing system performance
    - C. It may require sacrificing system performance
    - D. It disables location-based services

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        Full transparemcy can hurt performance.
    </details>

6. What does the middleware layer do in a distributed system?
    - A. It provides memory allocation for each local device
    - B. It handles only replication and caching
    - C. It manages communication between applications and the OS to support transparency
    - D. It prevents users from accessing remote systems

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        Middleware supports smooth communication.
    </details>

7. In the context of openness, which of the following is not a desirable quality?
    - A. Portability
    - B. Interoperability
    - C. Dynamic configurability
    - D. Proprietary protocols

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: D

        Propriety = closed, not open.
    </details>

8. Which of the following pairs demonstrates a clear distinction between policy and mechanism?
    - A. Using TCP vs UDP
    - B. Enabling write-access vs using file locking
    - C. Using encryption vs setting secrecy levels
    - D. Designing an API vs implementing an API

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: B

        Policy = rule; Mechanism = how it's done. 
    </details>

9. The dependability of a component can be undermined by a fault in another component if:
    - A. The second component is not virtualized
    - B. The component depends on the correctness of the second component
    - C. The second component uses different policies
    - D. Faults cannot affect multiple components

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: B

        Component C relies in C*'s correctness. 
    </details>

10. If a system has high MTTF and low MTTR, what can we infer?
    - A. The system is unreliable
    - B. The system is highly available
    - C. The system has low scalability
    - D. The system is not distributed

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: B

        High uptime + quick fixes = good availability.
    </details>

11. Which of the following best defines reliability R(t)?
    - A. The time it takes to fix a fault
    - B. The rate of response per second
    - C. The probability that the system runs correctly in a time period
    - D. The number of concurrent users

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C 
        
        Reliability is a time-based success rate. 
    </details>

12. Which security mechanism ensures that only authorized parties can read data?
    - A. Integrity
    - B. Authentication
    - C. Confidentiality
    - D. Trust

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        Confidentiality = data privacy.
    </details>

13. Which statement about asymmetric encryption is true?
    - A. The same key is used to encrypt and decrypt data
    - B. The public key must be kept secret
    - C. The private key is shared with everyone
    - D. It uses different keys for encryption and decryption

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: D

        Public/private keys are different. 
    </details>

14. Why are secure hash functions important in digital systems?
    - A. They speed up encryption
    - B. They prevent unauthorized access
    - C. They detect even small changes in data
    - D. They generate encryption keys

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        Hashing = spotting even small changes. 
    </details>

15. What is the main challenge with replication in distributed systems?
    - A. Users cannot access replicated data
    - B. Replication slows down computation
    - C. Ensuring all copies remain consistent
    - D. Encryption cannot be used on replicated data

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        Hard to keep all copies in sync.
    </details>

16. Which type of scalability deals with multiple organizations controlling different parts of a system?
    - A. Size Scalability
    - B. Administrative Scalability
    - C. Distance Scalability
    - D. System Scalability

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: B

        Different orgs = administrative challenge. 
    </details>

17. Which type of scalability problem occurs when moving from a LAN to a WAN?
    - A. Loss of file system access
    - B. Data corruption
    - C. Communication latency
    - D. Node clustering

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        WAN =  more latency than LAN. 
    </details>

18. What’s one way to reduce geographical latency in distributed systems?
    - A. Use synchronous communication
    - B. Increase the number of administrators
    - C. Use asynchronous communication
    - D. Rely only on centralized servers

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        Async avoid waiting for replies. 
    </details>

19. Why is full global synchronization generally avoided?
    - A. It increases system transparency
    - B. It increases performance
    - C. It limits large-scale scalability
    - D. It enhances data consistency automatically

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        Global sync slows down big systems.
    </details>

20. In cluster computing, the system is:
    - A. Heterogeneous and spread across the internet
    - B. Built with random devices across cities
    - C. A group of similar machines connected via LAN
    - D. A type of sensor network

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        Clusters = similar machhines + LAN.
    </details>

21. In grid computing, what is a "virtual organization"?
    - A. A fake company for simulations
    - B. A system that only uses cloud servers
    - C. A temporary group of users who share resources
    - D. A scheduling system for multiprocessors

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        Grids = temporary sharing groups.
    </details>

22. Which of the following middleware types uses a "publish/subscribe" model?
    - A. Remote Procedure Call
    - B. Message-Oriented Middleware
    - C. Shared File Systems
    - D. Distributed Databases

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: B

        MOM uses publish-subscribe.
    </details>

23. What is a key feature of ubiquitous computing systems?
    - A. The user must manually activate interactions
    - B. The system interacts continuously and blends into daily life
    - C. They run only on mobile phones
    - D. They require manual updates every hour

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: B

        Ubiquitous = always present and subtle.
    </details>

24. Why did distributed shared memory systems fail in practice?
    - A. They had too much hardware cost
    - B. They were easier to program
    - C. They couldn’t match the speed of real multiprocessors
    - D. They were only available on Linux

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        Couldn't compete with real hardware.
    </details>

25. What does a TP Monitor do?
    - A. Encrypts data using symmetric keys
    - B. Handles multiple user logins
    - C. Coordinates the steps of a transaction
    - D. Monitors CPU temperature

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        TP monitors manage transactions.
    </details>

26. What is one downside of using file transfer to integrate applications?
    - A. It supports flexible data formats
    - B. It’s slow but secure
    - C. It’s simple but lacks flexibility and consistency
    - D. It requires secure sockets

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        File transfer is simple but weak.
    </details>

27. Which system does not blend into a user’s environment?
    - A. Ubiquitous computing
    - B. Sensor networks
    - C. Mobile computing
    - D. Centralized mainframe

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: D

        Centralized mainframes aren't "blended in."
    </details>

28. What is the key feature of context awareness?
    - A. The system can sense the user's situation and act accordingly
    - B. The system updates automatically every hour
    - C. The user can control other devices
    - D. The network becomes more secure

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: A

        Know user's context = better interaction.
    </details>

29. Which of the following is a false assumption that causes pitfalls in distributed systems?
    - A. Bandwidth is limited
    - B. Latency varies
    - C. The network is secure
    - D. Users are untrusted

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: C

        "Network is secure" is a false assumption.
    </details>

30. Why is it a mistake to assume “there is one administrator” in distributed systems?
    - A. It’s always the case
    - B. Many systems require coordination across different teams
    - C. One admin can manage all systems perfectly
    - D. Admins are not needed in modern systems

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: B

        Usually there are many teams/admins.
    </details>


### Enumeration

31. It is a system with once main computer that does everything. If that one breaks, the whole system stops working.
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: Centralized System
    </details>

32. It is a system with multiple computers, but they don't fully work together yet. Better than the other with one main computer but not fully connected.
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: Decentralized System
    </details>

33. Is it s system where many computers work together as one. They share work and resources, and users don’t notice where things are located.
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: Distributed System
    </details>

34. It is a system where computers that are connected to each other but not necessarily working as a single system.
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: Networked System 
    </details>

35. What is difference between Integrative View and Expansive View?
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Integrative view is connecting existing networked computer systems into a larger system  while Expansive View adds more computers to grow the system (extending additional computers).
    </details>

36. What is the goal of Distribution Transparency?
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: It is to hide the fact that parts of the system are on different computers and it should feel like one single system to the user.
    </details>

37. What are the type of Transparency?
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Access Transparency
        - Location Transparency
        - Replication Transparency
        - Concurrency Transparency
        - Failure Transparency
        - Mobiltiy Transparency
    </details>

38. What type of transparecy that the user move devices or data around, and it still works?
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: Mobility Transparency
    </details>

39. What type of transparency that the user don't know or care where it is?
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: Location Transparency
    </details>

40. What type of transparency that the user can access things the same way, no matter where they are?
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: Access Transparency
    </details>

41. It is a transparency that system keeps working even if one part fails?
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: Failure Transparency
    </details>

42. It is a transparency where the users don't know ow many copies exist.
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: Replication Transparency
    </details>

43. What is Concurrency Transparency?
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: Concurrency Transparency is where the users can use it at the same time.
    </details>

44. What is Middleware?
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: A layer between your app and the system that helps make distribution transparency work.
    </details>

45. What should be the capabilities of Openness?
    - A. Work with other systems
    - B. Use standard rules
    - C. Be easy to upgrade
    - D. None of the above.
    - E. All of the above (except D).

    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: All of the above.
    </details>

46. What is the difference between Policy v. Mechanism?
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Policy: The “rules” (e.g., what kind of access is allowed).
        
        - Mechanism: The “tools” to enforce those rules (e.g., passwords, encryption).
    </details>

47. What is Dependability in Distributed Systems?
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: The system should keep working correctly and not crash easily.
    </details>

48. Enumerate all Dependability Concepts.
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 
        - Fault – Something goes wrong (like a hardware problem).
        
        - Error – A fault causes incorrect behavior.
        
        - Failure – The system doesn’t do what it should.
    </details>

49. What are the metrics for dependability?
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 

        - Reliability (R(t)) – How long a system keeps working properly.

        - MTTF (Mean Time to Failure) – Time until it breaks.

        - MTTR (Mean Time to Repair) – Time to fix it.

        - MTBF (Mean Time Between Failures) – MTTF + MTTR.
    </details>

50. What are the common security terms in Distributed System?
    <details markdown=1><summary markdown='span'>Answer</summary>

        Correct Answer: 

        - Confidentiality – Keep data private.

        - Integrity – No unauthorized changes.

        - Authentication – Prove who you are.

        - Authorization – Check what you’re allowed to do.

        - Trust – Believe that a system or person will do the right thing.
    </details>