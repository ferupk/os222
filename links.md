---
permalink: LINKS/
---

[HOMEPAGE]({{site.baseurl}}/) | [LINKS]({{site.baseurl}}/LINKS/) | [GITHUB]({{site.githubrepo}}) | [LOG]({{site.baseurl}}{{site.mylog}}) | [PUBLIC KEY]({{site.baseurl}}{{site.mypubkey}}) | [TARBALL]({{site.tarball}})

## LINKS
Here are some neat links to check out sometimes!

### Week 01

1. [Documentation for Debian](https://www.debian.org/doc/)

   A collection of manuals, FAQs, and other bits of information regarding the Debian operating system. A good point of reference for any inquiries I might encounter along the way.

2. [Basic Vi Commands](https://www.cs.colostate.edu/helpdocs/vi.html)

   Vi is the stock text editor for UNIX operating systems and the one I'm currently using. This is simply a cheatsheet I can refer to when needed. Might update this once I've tried out other text editors.

3. [regex101](https://regex101.com/)

   An incredibly versatile RegEx debugger with references to boot. Supports multiple flavors and features an extensive library of community-made expressions.

4. [AWK cheatsheet](https://quickref.me/awk)

   Another cheatsheet, this time for the scripting language AWK. It's compact and covers the essentials.

### Week 02

1. [Understanding Denial-of-Service Attacks](https://www.cisa.gov/uscert/ncas/tips/ST04-015)

   A introduction to denial-of-service (DoS) attacks by the United States' Cybersecurity and Infrastructure Security Agency. The page notes the different forms of DoS attacks alongside an explanation for a distributed DoS attack. They also provide readers with ways to mitigate the effects of a DoS attack, as well as clues to identify whether one is happening.

2. [The RSA Encryption Algorithm](https://youtu.be/4zahvcJ9glg)

   In this two-part video, high school teacher Eddie Woo explains the mechanisms behind the RSA encryption system. Part 1 showcases the data transmission process with simplified examples, while Part 2 delves into the algorithm used for generating the encryption and decryption keys. The videos are straight to the point and easy to understand despite how quickly it goes by. Mr. Woo's energetic personality also helps to engage the viewer in the subject.

3. [GnuPG Documentation](https://www.gnupg.org/documentation/index.html)

   Gnu Privacy Guard or GnuPG is a command line tool used to encrypt data in accordance to the OpenPGP standard. GnuPG's official site provides a documentation section for any inquiries regarding the software. It hosts guides, FAQs, and numerous options for community support.

### Week 03

1. [Linux File Permissions: Commands with Examples](https://www.youtube.com/watch?v=D-VqgvBMV7g)

   This tutorial video by Code99 introduces you to the concept of permissions for files in Linux. They delve into the concept of user types and the three permissions a user or group might have: reading a file, writing on a file, and executing a file. These permissions can be altered using the `chmod` command with guides to represent permissions in either numeric or symbolic value. Another command — `chown` — is used to change the ownership of files to another user or group.

2. [File Allocation Methods in OS](https://www.scaler.com/topics/file-allocation-methods-in-os/)

   This article by Aniket Marwade provides an overview on 5 different file allocation methods. The explanations are brief but informative, and visual examples are provided to give readers a better understanding of what's going on. The pros and cons of each method are also listed to provide a comparison on the capabilities each method has.

3. [Writing a FUSE Filesystem: a Tutorial](https://www.cs.nmsu.edu/~pfeiffer/fuse-tutorial/)

   This web document by Joseph J. Pfeiffer, Jr., Ph.D. serves as both an introduction to the FUSE interface and a tutorial on how you can write your own filesystem using FUSE. It's quite the extensive read and an interesting personal recount which gives the reader a general idea on how to implement callbacks, data access, and protections in a FUSE filesystem.

### Week 04

1. [Contiguous and Non-Contiguous Allocation](https://www.javatpoint.com/contiguous-and-non-contiguous-memory-allocation-in-operating-system)

   An article about contiguous and non-contiguous memory allocation in a compare-and-contrast format. After a short overview, the writer delves into the key differences of each method. A table of comparisons are also given, providing details on what aspects each method is better at.

2. [Memory Fragmentation, Your Worst Nightmare](https://www.softwareverify.com/blog/memory-fragmentation-your-worst-nightmare/)

   Stephen Kellett at Software Verify gives an extensive view of memory fragmentation and it's effect on running computer programs. The blog post details common causes of the problem as well as symptoms that can help the reader identify when a program is hindered by fragmentation. Various solutions to mitigate the effects of fragmentation are also provided.

3. [Segmented and Paged Memory](https://www.youtube.com/watch?v=p9yZNLeOj4s)

   A quick video rundown on both segmented and paged memory, including it's application and characteristics. Explanations are complemented with simple yet effective visuals to better convey the topic.

### Week 05

1. [Full Introduction to NUMA](https://www.minitool.com/lib/numa.html#software-support-of-numa-5125)

   TechTarget contributor Rahul Awati goes into the Non-uniform Memory Access (NUMA) architecture, explaining how it works and its use in symmetric multiprocessing systems. The pros and cons of the architecture alongside comparisons between NUMA and UMA architecture are also brought up.

2. [Page Replacement Algorithms in Operating Systems](https://workat.tech/core-cs/tutorial/page-replacement-algorithms-in-operating-system-os-q0pioxh7iym5)

   A rundown of three different page replacement algorithms: First In First Out (FIFO), Optimal, and Least Recently Used (LRU). An example case is shown for each algoritms to help compare their inner workings and efficiency.

3. [Second Chance Algorithm](https://www.youtube.com/watch?v=voiL2-nQmlU)

   This video from the channel BBarters explains the Second Chance algorithm for replacing pages. The lecturer uses a main example to demonstrate how the algorithm works and what results can be achieve in terms of the number of page faults.

### Week 06

1. [Process Creation & Termination](https://www.tutorialspoint.com/inter_process_communication/inter_process_communication_process_creation_termination.htm)

   This TutorialsPoint article goes over the creation and termination of processes using the fork() and exit() system calls.

2. [What Is Multithreading: A Guide to Multithreaded Applications](https://totalview.io/blog/multithreading-multithreaded-applications)

   TotalView senior director Bill Burns informs the reader about the concept of multithreading and its applications. Mr. Burns also notes the issues one might encounter when developing multithreaded applications and how to go over debugging them.

### Week 07

1. [Synchronization With Semaphores](https://docs.oracle.com/cd/E19120-01/open.solaris/816-5137/sync-11157/index.html)

   Oracle's Multithreaded Programming Guide includes a section on semaphores and its use in synchronizing processes. The page covers the basic concepts of a semaphore and how to implement them in your code.

2. [Dining Philosophers Problem](https://www.scaler.com/topics/operating-system/dining-philosophers-problem-in-os/)

   The Dining Philosophers Problem is a problem in Operating Systems to demonstrate how incorrect use of limited resources can result in a deadlock. Scaler writer Apurva Sharma delves into the problem and showcases a solution involving the use of semaphores.

3. [Resource Allocation Graph - Deadlock Detection](https://www.gatevidyalay.com/resource-allocation-graph-deadlock-detection/)

   A compact description on how to use the resource-allocation graph to detect deadlocks within a system.

### Miscellaneous

* [hello world 💻](https://www.youtube.com/watch?v=Yw6u6YkTgQ4)

---

© {{site.copyright}} - {{site.author}} - Version: {{site.version}}

---
