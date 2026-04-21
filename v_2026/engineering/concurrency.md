<img src="https://hackernoon.com/banner-image.png" alt="drawing" width="1012"/>

# [concurrency](https://hackernoon.com/tagged/concurrency)
### Let's learn about [Concurrency](https://hackernoon.com/tagged/concurrency) via these 62 free blog posts. They are ordered by HackerNoon reader engagement data. Visit the [/Learn](https://hackernoon.com/learn) or [LearnRepo.com](https://learnrepo.com) to find the most read blog posts about any technology.

The ability of different parts of a program or multiple programs to execute out-of-order or in partial order without affecting the final outcome, crucial for maximizing resource utilization and responsiveness in modern systems.

### [1. Async/Await in Golang: An Introductory Guide](https://hackernoon.com/asyncawait-in-golang-an-introductory-guide-ol1e34sg)
![](https://cdn.hackernoon.com/images/3Ur17PtJhkV5UkAAJFu6z8t0fKg1-eh2032xi.jpeg)
Golang is a concurrent programming language. It has powerful features like Goroutines and Channels that can handle asynchronous tasks very well. Also, goroutines are not OS threads, and that's why you can spin up as many goroutines as you want without much overhead, it's stack size starts at 2KB only. So why async/await? Async/Await is a nice language feature that provides a simpler interface to asynchronous programming.

### [2. Optimistic and Pessimistic Locking in JPA](https://hackernoon.com/optimistic-and-pessimistic-locking-in-jpa)
![](https://cdn.hackernoon.com/images/bu2EcgsBMkb4EPIleKDsMfYfLKF3-ap92iku.jpeg)
The article explains optimistic and pessimistic locking. We consider a Spring Data JPA application with concurrent transactional code as an example.

### [3. Concurrent Programming in Python is not what you think it is.](https://hackernoon.com/concurrent-programming-in-python-is-not-what-you-think-it-is-b6439c3f3e6a)
![](https://cdn.hackernoon.com/images/9y1zw12i8.jpg)
Originally published on melvinkoh.me

### [4. Mastering Synchronization Primitives in Go ](https://hackernoon.com/mastering-synchronization-primitives-in-go)
![](https://cdn.hackernoon.com/images/illustrate-a-programming-language-screen-clgxqt91l000001s66gfc128h.png)
Golang's Goroutines make it easy to run code concurrently. We can simply add the keyword “go” in front of a function call to make it run in a separate routine, or asynchronously.

### [5. Solve Database Concurrency Issues with TypeOrm](https://hackernoon.com/database-concurrencies-with-typeorm-6b1631k8)
![](https://cdn.hackernoon.com/images/caEFaH2LIyTEqUMLqhhb3nC4EXg1-tjpy31rs.jpeg)
Solve concurrency issues with typeorm query to fix race-condition and deadlock  bug. 

### [6. Understanding Concurrent Collections in C#](https://hackernoon.com/understanding-concurrent-collections-in-c)
![](https://cdn.hackernoon.com/images/gk2qp4pBWCW0A4R3x2JZIfp39qg2-8x337r7.jpeg)
A brief introduction to concurrent collections in c sharp.

### [7. Leveraging Multithreading To Read Large Files Faster In Go](https://hackernoon.com/leveraging-multithreading-to-read-large-files-faster-in-go-lmn32t7)
![](https://cdn.hackernoon.com/drafts/he6u32fh.png)
The other day I was interviewing at one of the companies, and I was asked the following question, how can you count occurrences of a word in a 50gb file with 4gb of RAM. The trick is to not load the whole file into memory and keep processing each word as we keep on moving the pointer of the file. With this, we can easily process the whole file with a minimal amount of memory resources.

### [8. Comparing Optimistic and Pessimistic Locking With GO and PostgreSQL](https://hackernoon.com/comparing-optimistic-and-pessimistic-locking-with-go-and-postgresql)
![](https://cdn.hackernoon.com/images/LDruOynCeFhvHi3906Wfi1uzXy03-3s93pu8.jpeg)
Comparison between Optimistic and Pessimistic locking with Golang and PostgreSQL

### [9. Goroutines: How to Run Concurrency Code in Go](https://hackernoon.com/goroutines-how-to-run-concurrency-code-in-go)
![](https://cdn.hackernoon.com/images/SnVhdDNm3fMGfftKZO7mnXldvQm2-erb3m1q.png)
Try out concurrency in Go on a simple example. What are greenthreads and asynchronous preemtpion? Understanding channels by using worker-pool pattern.

### [10. Concurrency in Golang And WorkerPool [Part 1]](https://hackernoon.com/concurrency-in-golang-and-workerpool-part-1-e9n31ao)
![](https://cdn.hackernoon.com/images/3Ur17PtJhkV5UkAAJFu6z8t0fKg1-cz631ep.jpeg)
Project Link: https://github.com/Joker666/goworkerpool

### [11. How Does Node.js Achieve Concurrency?](https://hackernoon.com/how-does-nodejs-achieve-concurrency)
![](https://cdn.hackernoon.com/images/1vUvJ9iHgHZcKTT7tkxuBZ7UIAf1-w1f3ozd.jpeg)
Ever wondered how Node.js handles multiple requests despite being single threaded? Find out the secret to concurrency in Node.js and how the event loop works

### [12. Parallel Merge Sort with Fork/Join Framework](https://hackernoon.com/parallel-merge-sort-with-forkjoin-framework)
![](https://cdn.hackernoon.com/images/a088Dwhw1pNtxFTtazApdvSQJk03-kj235gm.jpeg)
In this article, I show how to use the ForkJoinPool, which hasn’t received significant dissemination among Java developers.

### [13. Smoke Your Server Using Goroutines](https://hackernoon.com/smoke-your-server-using-goroutines-zau32au)
![](https://cdn.hackernoon.com/drafts/tqgc3293.png)
We all want to test our servers and the latency induced by scale. There are different ways to do that one way would be to use postman to send multiple requests. But how do I send concurrent requests? Say I want to a million requests with different levels of concurrency. This can be easily achieved by leveraging the power of Goroutines.

### [14. Concurrent React Mode: Using Suspense and useTransition to Build A Better UX](https://hackernoon.com/concurrent-react-using-suspense-and-usetransition-to-build-better-ux-cman2cdd)
![](https://images.unsplash.com/photo-1518932945647-7a1c969f8be2?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=1080&fit=max&ixid=eyJhcHBfaWQiOjEwMDk2Mn0)
The React JS dev team announced some exciting changes several months ago - React would be getting a "Concurrent Mode". Essentially this would allow React to perform multiple UI renders concurrently. Of course, JavaScript is single threaded and true concurrency is an illusion, but the new features will allow web apps (and Native Apps once these features hit React Native) to be much more responsive and snappy than they are now with less effort and custom code from the developer to make this happen.

### [15. How We Increased Database Query Concurrency by 20 Times](https://hackernoon.com/how-we-increased-database-query-concurrency-by-20-times)
![](https://cdn.hackernoon.com/images/oNIroQpI1FZj2l5g1MSUvunDFzu2-g9f368l.jpeg)
Learn 5 ways to accelerate point queries and 4 methods to further improve concurrency: row storage format, short circuit, prepared statement, and row storage ca

### [16. Understanding Concurrency and Multithreading in iOS Development](https://hackernoon.com/understanding-concurrency-and-multithreading-in-ios-development)
![](https://cdn.hackernoon.com/images/ios-development-p5lueiqfci2aiiin8ox68qtu.png)
An introduction to concurrency and multithreading in iOS development

### [17. Why Rust Is So Popular?](https://hackernoon.com/why-rust-is-so-popular-gk1p3ur5)
![](https://firebasestorage.googleapis.com/v0/b/hackernoon-app.appspot.com/o/images%2FMJpFVUEItkSdoh38rYo60VT7RfH3-im1628vx.jpeg?alt=media&token=2c932a0d-8b47-4ad8-a0a4-01c58d780ac8)
If you are looking for some kind of metal panel business idea, allow me to be clear: the Rust I am referring to is a programming language.

### [18. Top 5 Concurrency Interview Questions for Software Engineers](https://hackernoon.com/top-5-concurrency-interview-questions-for-software-engineers-x48i30qu)
![](https://cdn.hackernoon.com/images/e5u3z97.jpg)
(Some background: I’ve interviewed hundreds of candidates for software engineering jobs at Facebook and Microsoft. I’ve also failed several coding interviews myself when I wasn’t prepared.)

### [19. Interview with Anderson Queiroz: Golang is The Perfect Language for the 21st Century](https://hackernoon.com/interview-with-anderson-queiroz-golang-is-the-perfect-language-for-the-21st-century-xmc433jo)
![](https://cdn.hackernoon.com/images/y54f33rq.jpg)
Introduction

### [20. Rethinking Programming: Making Sequence Diagrams Cool Again](https://hackernoon.com/rethinking-programming-making-sequence-diagrams-cool-again-6z1p3yv9)
![](https://cdn.hackernoon.com/images/NpclsXHLfPf1qjBCjmjlbDg2CFo1-3k83xuv.jpeg)
Introduction

### [21. Understanding Concurrency Patterns in Go](https://hackernoon.com/understanding-concurrency-patterns-in-go)
![](https://cdn.hackernoon.com/images/FnJSyiTSqmPvpvgC9FHggSRb8Gj2-js8336m.png)
Explore Go’s concurrency patterns, including worker pools, fan-out/fan-in, and pipelines, to build efficient, robust, and scalable applications.

### [22. Inside BEAM: How Elixir and Erlang Leverage a Shared Runtime for Resilient Applications](https://hackernoon.com/inside-beam-how-elixir-and-erlang-leverage-a-shared-runtime-for-resilient-applications)
![](https://cdn.hackernoon.com/images/kIHr1rRf4vghAXgOb3lKJOUQdc02-vo931ck.jpeg)
Explore the origins and guiding principles behind Erlang and Elixir to understand their full potential and innovation. 

### [23. A Guide to Improving Your Python Performance Speed](https://hackernoon.com/a-guide-to-improving-your-python-performance-speed-th2835dj)
![](https://cdn.hackernoon.com/images/scJFRtReiyVdTsEi7KjcSIGTVDE3-19ay22vd.jpeg)
This guide aims to summarize popular methods for boosting the execution speed of your Python code.

### [24. Building AxonerAI: A Rust Framework for Agentic Systems](https://hackernoon.com/building-axonerai-a-rust-framework-for-agentic-systems)
![](https://cdn.hackernoon.com/images/NXU20Up8kqblDLj2vQC0J9fsuVg1-s523bej.png)
AxonerAI: Rust framework for building AI agents. Alternative to LangChain with memory safety, true concurrency and blazing fast executions.

### [25. Understanding Synchronized Collections in Java](https://hackernoon.com/understanding-synchronized-collections-in-java)
![](https://cdn.hackernoon.com/images/hxgB3A2KjtPk4sJXB1ezGnusKBx1-co83gm4.jpeg)
Learn about Java's synchronized collections that helps you achieve thread-safety in the most easiest way!

### [26. JavaScript Concurrency Models: The Event Loop](https://hackernoon.com/javascript-concurrency-models-the-event-loop-kj2b31ar)
![](https://cdn.hackernoon.com/images/HrzvBX6xNSVZBKImURJl23sRwcQ2-96t31cy.jpeg)
JavaScript has a concurrency model based on an event loop, which is responsible for executing the code, collecting and processing events, and executing queued sub-tasks. 

### [27. Here's How I Scaled A Cryptocurrency Exchange's Trading Engine to 1 Million TPS](https://hackernoon.com/heres-how-i-scaled-a-cryptocurrency-exchanges-trading-engine-to-1-million-tps-a62e3xyt)
![](https://firebasestorage.googleapis.com/v0/b/hackernoon-app.appspot.com/o/images%2F15KWsubDTMQic1C8YLh2c9G911U2-hgb3t3a.jpeg?alt=media&token=ebb13149-6d03-4e87-a29c-a79b940a1feb)
Crypto exchange has been in great demand with the adaptability of cryptocurrencies surging and multiple new tokens/coins been put there attracting users by showcasing their great potential.

### [28. Is Kafka the Key? The Evolution of Highlight's Ingest](https://hackernoon.com/is-kafka-the-key-the-evolution-of-highlights-ingest)
![](https://cdn.hackernoon.com/images/NqzCl6zSU1hR6VaJ0Sp5hkDySGf2-slb3my0.jpeg)
Building a distributed message processing queue using Apache Kafka requires some thought. We walk through how we process thousands of large messages per second.

### [29. Inteview with Frank Müller: One Decade of Go - the Power of Concurrency](https://hackernoon.com/inteview-with-frank-muller-one-decade-of-go-the-power-of-concurrency-eq6u370h)
![](https://cdn.hackernoon.com/drafts/7l2y37n0.png)
Frank Müller, Solution Engineer at Loodse, is one of the co-organizers of the GoDays conference in Berlin, which took place in January of 2020. It has been an exciting moment when Google announced its Language Go in 2009. After some hype and early years of establishing the language, it was settled as a robust and scalable fundament for networked systems. We invite you to enjoy a travel through a decade of our beloved Go within the interview of Grigory Petrov, Dev Rel at Evrone.com with Frank Müller.

### [30. Solving Producer/Consumer Problem of Concurrent Programming in Python](https://hackernoon.com/solving-producerconsumer-problem-of-concurrent-programming-in-python-vk1i28av)
![](https://cdn.hackernoon.com/images/g21528da.jpg)
In "Concurrent Programming in Python is not what you think it is", I wrote about the notorious GIL in Python and did a simple experiment on existing concurrency mechanism in Python. Today, I'll describe another common scenario in concurrent programming, the Producer/Consumer problem, with Python.

### [31. The Essential Guide to Relearning Java Thread Primitives](https://hackernoon.com/a-guide-on-relearning-java-thread-primitives)
![](https://cdn.hackernoon.com/images/PVJZAra3SJb106HGMWMnMsiHUCk1-99c2hbj.jpeg)
Synchronized was revolutionary and still has great uses. But it's time to move to newer thread primitives and potentially, rethink our core logic.


### [32. The Truth About “Cancelling” Async/Await: You’re Mostly Just Ignoring Results](https://hackernoon.com/the-truth-about-cancelling-asyncawait-youre-mostly-just-ignoring-results)
![](https://cdn.hackernoon.com/images/2jqChkrv03exBUgkLrDzIbfM99q2-al0238i.jpeg)
JavaScript can’t truly cancel async/await work—most “cancellation” just stops waiting. 

### [33. Go Concurrency: Goroutines, Mutexes, WaitGroups & Condition Variables](https://hackernoon.com/go-concurrency-goroutines-mutexes-waitgroups-and-condition-variables)
![](https://cdn.hackernoon.com/images/8KGWNss2rIT5ieSmxoe0XLD4sac2-xra358z.jpeg)
Comprehensive guide to Go concurrency: goroutines, mutexes, WaitGroups, and condition variables with examples, best practices, and gotchas.

### [34. Using Java Executor framework for Multithreading [A How To Guide]](https://hackernoon.com/how-to-use-java-executor-framework-for-multithreading-8r1h32ba)
![](https://images.unsplash.com/photo-1503551723145-6c040742065b?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=1080&fit=max&ixid=eyJhcHBfaWQiOjEwMDk2Mn0)
In my Previous Blog I covered the basics of Multithreading in Java. Click here to read that blog.

### [35. Building a Simple REST API in Go Without Frameworks](https://hackernoon.com/building-a-simple-rest-api-in-go-without-frameworks)
![](https://cdn.hackernoon.com/images/R4wsbPS5sLRmPKPzOZLOzxdFQOA2-nt03bgz.jpeg)
Learn how to build a RESTful API in Go from scratch using only the net/http package, in-memory data, and mutex for concurrency.

### [36. Understanding Concurrency in Golang with Goroutines: Latest Update in Version 1.23](https://hackernoon.com/understanding-concurrency-in-golang-with-goroutines-latest-update-in-version-123)
![](https://cdn.hackernoon.com/images/LDruOynCeFhvHi3906Wfi1uzXy03-wz02ves.png)
Explore the power of Goroutines in Golang for concurrency management, including new enhancements in Golang 1.23 that optimize performance and memory usage. 

### [37. How Coroutines Enable Cooperative Multitasking and Concurrency](https://hackernoon.com/how-coroutines-enable-cooperative-multitasking-and-concurrency)
![](https://cdn.hackernoon.com/images/XKjmz9tZa8XTDU9MqcuFluHFxfj2-wd825bk.jpeg)
In this story I explain how concurrency works in Kotlin coroutines with an example to prove how it works. Concurrency in coroutines is cooperative.

### [38. Tips For A Successful Concurrent Requests With Async/Await And Promise.all](https://hackernoon.com/tips-for-a-successful-concurrent-requests-with-asyncawait-and-promiseall-rk1l34f4)
![](https://cdn.hackernoon.com/images/CfwKcq2ny4hfMjglXzZ0Z89fz1R2-u86l36f2.jpeg)
Let's talk about concurrency, async/await, promise.all, and lightning web components

### [39. How Goroutines Behave on CPU-Bound vs I/O-Bound Tasks](https://hackernoon.com/how-goroutines-behave-on-cpu-bound-vs-io-bound-tasks)
![](https://cdn.hackernoon.com/images/lfFKjSfJfkamXdqdlc6jYh0R8003-yh03adq.png)
Goroutines can supercharge Go apps—or slow them down. Learn when they help, when they hurt, and how to benchmark your workloads.

### [40. What Every Gopher Should Know About the Go Memory Model](https://hackernoon.com/what-every-gopher-should-know-about-the-go-memory-model)
![](https://cdn.hackernoon.com/images/8KGWNss2rIT5ieSmxoe0XLD4sac2-2xa38uv.jpeg)
Learn how Go's memory model defines visibility between goroutines using happens-before rules and synchronization primitives like channels and mutexes.

### [41. The Myth of Single-Threaded JavaScript: Inside the Language’s Hidden Concurrency Engine](https://hackernoon.com/the-myth-of-single-threaded-javascript-inside-the-languages-hidden-concurrency-engine)
![](https://cdn.hackernoon.com/images/2jqChkrv03exBUgkLrDzIbfM99q2-00023qg.png)
Explore the concurrency model of modern JavaScript, including the event loop, async/await, and more.

### [42. Safeguarding Concurrent Programs in Java: Thread Safety from an Object Oriented Perspective](https://hackernoon.com/safeguarding-concurrent-programs-in-java-thread-safety-from-an-object-oriented-perspective)
![](https://cdn.hackernoon.com/images/hxgB3A2KjtPk4sJXB1ezGnusKBx1-mi83gg5.jpeg)
A program that maintain its correctness in a multi-threaded environment is said to be a Thread-Safe program.

### [43. A Guide on How to Eliminate Thread Explosions in iOS: GCD and Swift Concurrency](https://hackernoon.com/a-guide-on-how-to-eliminate-thread-explosions-in-ios-gcd-and-swift-concurrency)
![](https://cdn.hackernoon.com/images/Ceus9O6pRZR4c9unqLNaigv0uzF3-3613ovs.jpeg)
Learn about thread explosion, how to manage it, and how modern Swift Concurrency addresses the issue.

### [44. A Simplified Comparison: Rust and Pointers](https://hackernoon.com/a-simplified-comparison-rust-and-pointers)
![](https://cdn.hackernoon.com/images/eUKH5kunlJgHBvQNpbjWn3R9CIM2-5e03a4c.jpeg)
Understand Rust's unique memory management system by comparing it to C/C++ pointers. Discover ownership, borrowing, references, and smart pointers.

### [45. Best Practices for Object Sharing in Multi-threaded Systems ](https://hackernoon.com/best-practices-for-object-sharing-in-multi-threaded-systems)
![](https://cdn.hackernoon.com/images/hxgB3A2KjtPk4sJXB1ezGnusKBx1-3q83gla.jpeg)
Your standard object sharing practices might totally fail in a multi-threaded environment. Learn about the ways to properly share objects across threads!

### [46. Mastering Object Visibility in Java](https://hackernoon.com/mastering-object-visibility-in-java)
![](https://cdn.hackernoon.com/images/hxgB3A2KjtPk4sJXB1ezGnusKBx1-0183gxe.jpeg)
Sharing variables across threads isn't as easy as it sounds. There are a number of interesting cases that might blow your mind when it comes to variable sharing

### [47. Here's What You Need to Know Before Using Event Sourcing](https://hackernoon.com/heres-what-you-need-to-know-before-using-event-sourcing)
![](https://cdn.hackernoon.com/images/YShPiCcB1XR4k0CEQh85HFrRmr73-hx03870.jpeg)
This article is useful for those interested in the concept of Event Sourcing and who want to decide if it's a good fit for their projects while avoiding common 

### [48. Go Concurrency Face-Off: Channels vs Mutexes](https://hackernoon.com/go-concurrency-face-off-channels-vs-mutexes)
![](https://cdn.hackernoon.com/images/qvl94vMr8gR0H57vXs5BZDfEfNs2-no020h0.jpeg)
Demystify when to use channels and when to use mutexes, and why blindly following "Go concurrency patterns" can backfire.

### [49. Swift Concurrency Explained: Actors, Executors, and Reentrancy](https://hackernoon.com/swift-concurrency-explained-actors-executors-and-reentrancy)
![](https://cdn.hackernoon.com/images/Ceus9O6pRZR4c9unqLNaigv0uzF3-rt83rxw.jpeg)
Explore Structured Concurrency in Swift: Actors, @MainActor, @GlobalActor, understanding the Swift Concurrency runtime, and actor reentrancy.  

### [50. Guide to Concurrency in React 18: How and Why](https://hackernoon.com/guide-to-concurrency-in-react-18-how-and-why)
![](https://cdn.hackernoon.com/images/TU75aLEAtQahH1ixBhcEmzyyikA2-aob34lc.jpeg)
Guide to concurrency, CPU- and IO-bound components, and other interesting stuff. Finally, learn wtf deferred value is.

### [51. Synchronization Challenges in Multithreading](https://hackernoon.com/synchronization-challenges-in-multithreading)
![](https://cdn.hackernoon.com/images/928A5MdLmkgtIlxpQv0Ir97p6BG3-vr03e8i.jpeg)
This is the sixth part of a series on Parallel Programming for Beginners. In this article, we’ll explore real-world scenarios and their solutions.

### [52. Streamlining Go Concurrency Using a Worker Pool](https://hackernoon.com/streamlining-go-concurrency-using-a-worker-pool)
![](https://cdn.hackernoon.com/images/2jqChkrv03exBUgkLrDzIbfM99q2-4202yib.jpeg)
Before you start spawning thousands of goroutines, let's take a step back and understand how to do this efficiently. 

### [53. Why Parallelism Isn't Always Concurrency (and Vice Versa)?](https://hackernoon.com/why-parallelism-isnt-always-concurrency-and-vice-versa)
![](https://cdn.hackernoon.com/images/8KGWNss2rIT5ieSmxoe0XLD4sac2_qt91bdi.jpeg)
An in-depth exploration of concurrency and parallelism in Go, covering key concepts.

### [54. Well-Known Concurrency Problems and How Go Handles Them ](https://hackernoon.com/well-known-concurrency-problems-and-how-go-handles-them)
![](https://cdn.hackernoon.com/images/8KGWNss2rIT5ieSmxoe0XLD4sac2-g5038zo.jpeg)
Explore classic concurrency problems in Go. Including producer-consumer, dining philosophers, and rate limiting with simple code examples and clear explanation.

### [55. Efficient Concurrency in Serverless Architectures with Go and AWS](https://hackernoon.com/lambda-isnt-made-for-parallelism-but-go-still-gets-the-job-done)
![](https://cdn.hackernoon.com/images/8vYCTIwQavWtBLs09yqFKiibfQQ2-ft12xqr.jpeg)
Goroutines let you run multiple operations in parallel within one request.

### [56. Swift Concurrency: Part 2 — Parent/child Relationship, Automatic Cancellation, Task Groups](https://hackernoon.com/swift-concurrency-part-2-parentchild-relationship-automatic-cancellation-task-groups)
![](https://cdn.hackernoon.com/images/Ceus9O6pRZR4c9unqLNaigv0uzF3-kv13os2.jpeg)
Explore Structured Concurrency in Swift: parent/child relationship, automatic cancellation, task groups, and more.

### [57. Project Loom Revolution - and How Not to Break Production in the Process](https://hackernoon.com/project-loom-revolution-and-how-not-to-break-production-in-the-process)
![](https://cdn.hackernoon.com/images/XAABEU8meidDRZoEexv1kqoGdLn2-qv33dp5.png)
A practical deep-dive into Project Loom, explaining how virtual threads and structured concurrency simplify Java’s concurrency model and enable high-throughput.

### [58. 3 Beginner Tips You Need to Know for async await in C#](https://hackernoon.com/3-beginner-tips-you-need-to-know-for-async-await-in-c)
![](https://cdn.hackernoon.com/images/FA4UT4FgGUfOjEjkcSYA2tYPEyG2-r6834yu.jpeg)
Learn essential tips for using async await in C# to write concurrent code more effectively. 

### [59. Inside Go Channels: Buffers, Locks, and the Runtime Memory Model](https://hackernoon.com/inside-go-channels-buffers-locks-and-the-runtime-memory-model)
![](https://cdn.hackernoon.com/images/cumbersome-code-displayed-on-a-laptop-screen-l2ry5s34lyplx52mkq5g42x5.png)
Go channels look simple, but under the hood they use buffers, queues, and scheduler tricks. Explore hchan, sudog, and Go’s concurrency model.

### [60. Why Would Anyone Call a Race Condition Nice?](https://hackernoon.com/why-would-anyone-call-a-race-condition-nice)
![](https://cdn.hackernoon.com/images/hxgB3A2KjtPk4sJXB1ezGnusKBx1-dj83gij.jpeg)
Every heard of a nice race condition? 

### [61. Singleton Beans and Debugging Nightmares 😲](https://hackernoon.com/singleton-beans-and-debugging-nightmares)
![](https://cdn.hackernoon.com/images/GWHX2lBFLbMSZ4olDc5OKN28T0h1-d60378b.jpeg)
A Spring bean. Sounds relatively harmless, doesn't it? What if I told you that this could be the source of many headaches in web servers, especially if you are 

### [62. How to Build a High-Performance Concurrent Leaderboard in Go](https://hackernoon.com/how-to-build-a-high-performance-concurrent-leaderboard-in-go)
![](https://cdn.hackernoon.com/images/5wpKgV75aONqkTJlafw2yQmK9yd2-dk03bo5.png)
Build a scalable, concurrent leaderboard in Go using sharding, heaps, and RWMutex to handle live updates and efficient Top-N queries.


