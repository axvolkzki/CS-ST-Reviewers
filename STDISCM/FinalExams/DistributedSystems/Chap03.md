# Final Exam Reviewer (Mock Test)

## Distributed Systems Chapter 3
***Mode: HARD | Items: 30 | Topic Coverage: Threads, Virtualization, Clients, Servers, Code Migration***

***Credits: Letty***

Instructions: Read carefully. Answers + explanations follow each question.

1. What makes thread context switching cheaper than process context switching?
    - A) Threads run in the kernel space
    - B) Threads use different memory segments
    - C) Threads share the same address space
    - D) Threads are executed sequentially

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: C

        Explanation: Threads in a process share the same address space, making context switching faster and less expensive than switching processes which require memory remapping.
    </details>

2. Which of the following is NOT stored in a processor context?
    - A) Stack pointer
    - B) Memory management unit (MMU) registers
    - C) Program counter
    - D) Addressing registers

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: B

        Explanation: MMU registers are stored in the process context, not the processor context.
    </details>

3. What is the minimal context required to execute a series of instructions for a thread?
    - A) Thread context only
    - B) Process context only
    - C) Processor context only
    - D) Thread context, which includes processor context

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: D

        Explanation: Thread context includes the processor context plus additional data to resume the thread.
    </details>


4. In Python multiprocessing, what is one main consequence of using separate processes instead of threads?
    - A) Threads share memory
    - B) Shared variables like shared_x are not preserved
    - C) Threads are slower
    - D) Processes are cheaper to create

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: B

        Explanation: In multiprocessing, processes do not share memory; so shared_x updates are not reflected across processes.
    </details>

5. What does a thread context include that a processor context does not?
    - A) Instruction set
    - B) CPU registers
    - C) Thread-specific memory
    - D) Cache data

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: C

        Explanation: Thread context contains processor context plus thread-specific memory state.
    </details>

6. What issue arises when user-level threads are blocked?
    - A) Only the thread is paused
    - B) OS will schedule another kernel thread
    - C) The whole process can be blocked
    - D) Another user-level thread can take over

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: C

        Explanation: The kernel sees only the process; if one thread blocks, the whole process may block.
    </details>

7. Which threading model allows threads to be scheduled on multiple processors by the OS?
    - A) User-level threads only
    - B) Kernel-level threads
    - C) Monolithic threading
    - D) Lightweight processes

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: B

        Explanation: Kernel-level threads are visible to the OS scheduler, allowing true parallel execution.
    </details>

8. Why are thread-based servers preferred over process-based servers in high-I/O scenarios?
    - A) Threads are more secure
    - B) Threads reduce parallelism
    - C) Thread creation is faster and uses less memory
    - D) Threads need multiple port allocations

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: C

        Explanation: Threads are lightweight, making them ideal for I/O-heavy tasks that require quick switching.
    </details>

9. What does Thread-Level Parallelism (TLP) measure?
    - A) Number of threads in memory
    - B) Instruction-level performance
    - C) Effective parallel execution of threads
    - D) Number of virtual CPUs

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: C

        Explanation: TLP is a metric for how many threads are running concurrently at a given time.
    </details>

10. What is the main disadvantage of user-level threads?
    - A) They cannot be scheduled
    - B) They are more expensive to create
    - C) They cannot benefit from multicore CPUs
    - D) They require special kernel modules
    
    <details markdown=1><summary markdown='span'>Answer</summary>
        
        ✅ Answer: C

        Explanation: The OS doesn’t see user threads, so it cannot schedule them on multiple cores.
    </details>

11. Which part of the client-server model initiates communication?
    - A) Thread
    - B) Server
    - C) Stub
    - D) Client

    <details markdown=1><summary markdown='span'>Answer</summary>
        ✅ Answer: D

        Explanation: Clients always initiate requests to the server.
    </details>

12. Which of the following is a benefit of stateless servers?
    - A) High performance via caching
    - B) Independent client-server operations
    - C) Prefetching support
    - D) Persistent sessions

    <details markdown=1><summary markdown='span'>Answer</summary>
        
        ✅ Answer: B

        Explanation: Stateless servers do not rely on stored client data, making them more fault-tolerant.
    </details>

13. What is the purpose of a dispatcher in the dispatcher/worker server model?
    - A) Executes all incoming requests
    - B) Stores state information
    - C) Assigns requests to worker threads
    - D) Handles urgent messages

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: C

        Explanation: The dispatcher passes incoming requests to available worker threads.
    </details>

14. What technique is used to send urgent data without blocking the main server port?
    - A) Use of containers
    - B) Multiplexing
    - C) Dedicated urgent port
    - D) Kernel trapping

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: C

        Explanation: A separate thread/process and port handles urgent requests.
    </details>

15. What virtualization technique allows an unmodified guest OS to run efficiently?
    - A) Full emulation
    - B) Containerization
    - C) Paravirtualization
    - D) Hardware-assisted virtualization

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: D

        Explanation: Hardware-assisted virtualization supports unmodified OSes using trap-and-emulate features.
    </details>

16. Which type of virtualization uses an interpreter/emulator to run apps on another OS?
    - A) Native VM
    - B) Process VM
    - C) Hypervisor
    - D) Bare-metal
    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: B

        Explanation: Process VMs translate instructions at the application level.
    </details>

17. Which virtualization type provides the best isolation between users on a cloud platform?
    - A) Containers
    - B) User-level threads
    - C) Virtual machines
    - D) Shared libraries

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: C

        Explanation: VMs provide strong isolation since they include full OS and virtual hardware.
    </details>

18. What condition must be true for virtualization to be secure and functional?
    - A) All instructions must be non-privileged
    - B) Sensitive instructions must trap
    - C) System calls must return NULL
    - D) Instruction sets must be identical

    <details markdown=1><summary markdown='span'>Answer</summary>
        
        ✅ Answer: B

        Explanation: Sensitive instructions should cause a trap in user mode to let the VMM handle them.
    </details>

19. What is the main limitation of using containers instead of VMs?
    - A) Containers don’t support applications
    - B) Containers are heavier
    - C) Containers rely on host OS
    - D) Containers cannot share files

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: C

        Explanation: Containers share the host OS kernel, limiting cross-platform portability.
    </details>

20. What is a union file system in containers used for?
    - A) Encrypt file data
    - B) Provide isolated file storage
    - C) Layer read-only base with writable layer
    - D) Speed up file I/O
    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: C

        Explanation: Union FS overlays file systems to keep the container's base read-only and only write to the top layer.
    </details>

21. What is the purpose of control groups (cgroups)?
    - A) Track container file changes
    - B) Limit and manage resource usage
    - C) Synchronize threads
    - D) Prevent code injection

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: B

        Explanation: Cgroups impose CPU, memory, and I/O limits on containers or groups of processes.
    </details>

22. What best describes weak code mobility?
    - A) Move the code with no state
    - B) Move code and execution state
    - C) Move thread registers only
    - D) Restart thread from same point

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: A

        Explanation: Weak mobility moves code (and optionally data) but not the execution state.        
    </details>

23. What does strong mobility preserve during migration?
    - A) Source machine configuration
    - B) Object address in memory
    - C) Entire execution state
    - D) Data segment only

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: C

        Explanation: Strong mobility allows continuation of execution where it left off.
    </details>

24. Which migration strategy causes the least downtime?
    - A) Post-copy
    - B) Pre-copy
    - C) Full-stop migration
    - D) Instruction tracing

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: B

        Explanation: Pre-copy reduces downtime by transferring memory pages while the VM is still running.
    </details>

25. In post-copy VM migration, when are memory pages moved?
    - A) Before process stops
    - B) After execution resumes
    - C) During idle time
    - D) In parallel with initial copy

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: B

        Explanation: Pages are fetched after the VM starts on the new machine (on-demand).
    </details>

26. What makes migration across heterogeneous systems difficult?
    - A) IP addressing
    - B) Thread context incompatibility
    - C) Lack of shared libraries
    - D) File system errors

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: B

        Explanation: Processor/thread contexts are tightly coupled to OS and hardware specifics.
    </details>

27. What method allows the client to interact with a distributed object in ICE?
    - A) Remote shell login
    - B) Object stub invocation
    - C) String-based proxy
    - D) DNS lookup

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: C

        Explanation: The client uses a string-based proxy to reference a remote object in ICE.
    </details>

28. What is a “slice” in PlanetLab?
    - A) A container with shared filesystem
    - B) A VM running on native OS
    - C) A group of isolated vservers
    - D) A single-process VM

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: C

        Explanation: A slice is a distributed set of vservers assigned to an experiment or app.
    </details>

29. In a DNS-based load balancing system, what’s the main risk?
    - A) DNS can't cache requests
    - B) DNS may be too close to the client
    - C) DNS resolver may be far from actual user
    - D) DNS doesn't support replication

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: C

        Explanation: The resolver location might distort the client’s true network location.
    </details>

30. What part of a server process listens for incoming client requests?
    - A) Handler
    - B) Adapter
    - C) Dispatcher
    - D) Listener thread

    <details markdown=1><summary markdown='span'>Answer</summary>

        ✅ Answer: D

        Explanation: The listener thread waits for client connections and then passes them off to handlers.
    </details>
