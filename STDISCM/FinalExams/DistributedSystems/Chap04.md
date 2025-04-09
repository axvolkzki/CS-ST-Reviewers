# Final Exam Reviewer (Mock Test)

## Distributed Systems Chapter 4
***Mode:  | Items: 15 | Topic Coverage:***

***Credits: Letty***

1. Which layer provides actual end-to-end communication between processes in distributed systems?
    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: Transport Layer

        Explanation: The transport layer (TCP/UDP) provides reliable or best-effort data transfer directly between applications on different machines.
    </details>

2. What type of communication stores messages until they can be delivered?
    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: Persistent

        Explanation: Persistent communication means the system holds onto the message until it reaches the receiver — even if it takes time.
    </details>

3. What is a key drawback of synchronous communication in client-server systems?
    <details markdown=1><summary markdown='span'>Answer</summary>
        
        ✅ Answer: The client must wait and cannot do anything else

        Explanation: In synchronous comm, the client blocks until the server replies — leading to potential delays and inefficiency.
    </details>

4. What does middleware do in distributed systems?
    <details markdown=1><summary markdown='span'>Answer</summary>
        ✅ Answer: Provides common services like naming and security

        Explanation: Middleware acts as a helper layer that provides functionality (e.g., marshaling, security, naming) so applications don't have to implement it themselves.
    </details>

5. What protocol provides reliable, stream-based communication?
    <details markdown=1><summary markdown='span'>Answer</summary>
        ✅ Answer: TCP

        Explanation: TCP ensures ordered, reliable delivery of a continuous stream of data — ideal for critical communications.
    </details>

6. Which term describes the transformation of parameters into a byte stream during RPC?
    <details markdown=1><summary markdown='span'>Answer</summary>
        ✅ Answer: Marshaling

        Explanation: Marshaling converts data into a format suitable for network transmission (serialization).
    </details>

7. In RPC, what is the main role of a stub?
    <details markdown=1><summary markdown='span'>Answer</summary>
        ✅ Answer: Translate local calls into network messages

        Explanation: The stub is a proxy that hides the network call — making a remote function look like a local one.
    </details>

8. Which is true about copy-in/copy-out semantics in RPC?
    <details markdown=1><summary markdown='span'>Answer</summary>
        ✅ Answer: Parameters are copied and returned at the end

        Explanation: RPC doesn't maintain shared memory; parameters are sent in, and modified versions are returned (if applicable).
    </details>

9. What is the purpose of ZeroMQ?
    <details markdown=1><summary markdown='span'>Answer</summary>
        ✅ Answer: To replace sockets with a higher-level abstraction

        Explanation: ZeroMQ provides structured messaging (e.g., request-reply, pub-sub) over raw sockets to simplify distributed programming.
    </details>

10. In a publish-subscribe model, what does the subscriber do?
    <details markdown=1><summary markdown='span'>Answer</summary>
        ✅ Answer: Listens for messages with a matching topic

        Explanation: Subscribers filter messages by topic — only receiving relevant ones (e.g., "TIME", "NEWS").
    </details>

11. What is a message broker responsible for in message-oriented middleware?
    <details markdown=1><summary markdown='span'>Answer</summary>
        ✅ Answer: Routing and transforming messages

        Explanation: A broker transforms messages and routes them appropriately, especially in heterogeneous systems (e.g., AMQP brokers).
    </details>

12. What is the role of a death certificate in distributed messaging?
    <details markdown=1><summary markdown='span'>Answer</summary>
        ✅ Answer: To indicate intentional deletion

        Explanation: Death certificates are special messages that signal a value has been removed — preventing it from being restored by sync processes.
    </details>

13. In epidemic protocols, what does anti-entropy aim to do?
    <details markdown=1><summary markdown='span'>Answer</summary>
        ✅ Answer: Equalize states across replicas

        Explanation: Anti-entropy helps all nodes slowly converge to the same data state by sharing updates randomly (pull/push).
    </details>

14. What is the benefit of asynchronous RPC?
    <details markdown=1><summary markdown='span'>Answer</summary>
        ✅ Answer: Client does not need to wait for a response

        Explanation: The client can send a request and move on without blocking — perfect for performance-critical or non-urgent tasks.
    </details>

15. In flooding multicast, what prevents infinite message propagation?
    <details markdown=1><summary markdown='span'>Answer</summary>
        ✅ Answer: Nodes ignore repeated messages

        Explanation: Each node tracks received messages — if it’s seen one before, it doesn't forward it again.
    </details>