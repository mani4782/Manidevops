**Defining DevOps: Beyond Bookish Definitions**



**Common Misconceptions**: When asked "What is DevOps?", common internet definitions like "DevOps = Dev + Ops" (Development + Operations working together) are acknowledged but deemed insufficient. The instructor recalls being unconvinced by these definitions in 2015-2016 while working as a Java developer, as they failed to explain the real problem DevOps solves.



**The Real Problem DevOps Solves (Through Analogy):**School Management System (50 Years Back - "Waterfall Model"):Problem: Low pass percentages (20-30%) due to a single final exam. Students, teachers, and parents lacked day-to-day seriousness or engagement. Students were not used to the examination system.



**Stakeholders**: Students, Teachers (including staff, principal), Parents (funding).

Behavior: Students were "not serious from day one," teachers were "not serious to complete syllabus from day one," and parents, though worried, had limited intervention points.

Outcome: System resulted in low pass rates and overall dissatisfaction.

Our Generation (30 Years Back - "Agile Model"):Solution: Introduction of unit tests, quarterly, half-yearly, and pre-final exams.



**Behavioral Shift**: Students became serious "at least from one week" before unit tests. Teachers became serious "from day one to complete syllabus" due to accountability. Parents gained opportunities to understand their children's progress.



**Outcome**: Pass percentages drastically increased to "at least 80%." This showed that breaking down a large task into smaller, more frequent iterations improved outcomes and stakeholder engagement.

10 Years Back (Continuous Testing - "DevOps"):Further Refinement: Introduction of "slip tests" (daily quizzes).



**Benefits**: Daily testing ensures immediate feedback and correction. If a topic is discussed today and tested tomorrow, it's easier to answer than after a month.

Impact on Defects: Testing a product once might reveal one defect, but testing it a thousand times increases the chance of finding more. This is crucial as minor defects can have drastic business consequences (e.g., RedBus pricing error, Flipkart/Amazon competition).



**Automation \& Tools**: Manual daily testing for 100 students is tough, but online tools make it easy to conduct 200+ exams for 1000 members. This highlights that while tools aren't mandatory, they are essential for automating and perfecting processes, reducing human error, and increasing speed.



**Software Development Life Cycle (SDLC) and Its Evolution**

Traditional SDLC Stages: Requirements Gathering: Understanding client needs (e.g., online website for a restaurant).

**Planning**: Analyzing requirements and strategizing the solution.

**Design**: Creating detailed blueprints (like house construction).

**Developing**: Building the application (or constructing the house).

**Deployment**: Releasing the application.

**Testing \& Maintenance**: Ensuring functionality and ongoing support.

Water-Fall Model (Pre-10 Years Back):Problem: Long development cycles (e.g., 2 years for a project) with minimal intermediate feedback.

**Stakeholders**: Customers/Clients, Developers, Testers, Managers.

**Behavior**: Developers and Testers were "not serious from day one." Clients were "worried from day one" due to lack of visibility. Much time was wasted on analysis, meetings, and superficial development.



**Defect Resolution**: When testing finally occurred (e.g., after 1.5 years of development), a large number of defects (e.g., 100 defects, with 20 invalid) were found. This led to "rivalry," "fights," "emails," and "politics" between Development and Testing teams, wasting precious time.



**Outcome**: Stress for everyone, poor quality product delivered (e.g., "Ambassador car" instead of "Ferrari"). No one was happy.



Agile Model (Introduction of Sprints):Solution: Breaking down large applications into smaller modules (e.g., User Management, Product Management, Cart, Shipping, Payment, Order Management).



**Sprints**: Delivering modules in shorter cycles (e.g., 1-2 months).

Improved Behavior: Developers became "serious from day one" to meet sprint deadlines. Defects were found and resolved more quickly (e.g., 30 defects in 15 days, with 10 invalid, but easier to fix as code was recent).



**Outcome**: Improved product quality (e.g., "Fortuner" instead of "Ambassador"), but "rivalry" still existed.

DevOps Model (DevOps with Agile):Core Principle: "Day one developer writes some code, build the code, test it." The goal is to build and test code immediately after it's written (even daily).



**Benefits**: Reduced Invalid Defects: Testing small code changes frequently leads to fewer invalid defects.

**Faster Bug Fixes**: Developers can easily fix bugs identified immediately, as the code is fresh in their minds.

Improved Collaboration: Eliminates idle time for different teams and reduces inter-team conflicts. "The previous fighting environment is not here."

Automated Communication: Automated email notifications for defects replace personal confrontations, fostering better coordination.

**DevOps Role**: DevOps engineers create the environment for developers and operations (testing, build \& release) to work together seamlessly. "DevOps means creating an environment where developers and operations work together."

**CI/CD**: Continuous Integration (integrating all written code) and Continuous Deployment (deploying the code) are crucial processes enabled by tools, replacing manual, time-consuming tasks.



**Impact**: Eliminated "server down" issues and maintenance delays in banking, enabling digital transformation.

Universal Applicability: DevOps engineers can establish this process for "any programming language" (Java, .NET, Python), making it a highly versatile and in-demand skill.

Environments: Multiple environments (Dev, Test, Prod, QA, UAT, Pre-Prod) are mandatory for rigorous testing and feedback collection before public release, similar to how Coca-Cola learned from a mistake by not testing a new taste extensively.



**Speed \& Accuracy**: DevOps ensures "faster releases but less defects" – achieving both speed and accuracy, critical for competing businesses like Flipkart and Amazon.

Continuous Improvement: DevOps is "by definition continuous improvement." It welcomes change (unlike Waterfall or Agile) and is adaptable to future innovations like DevSecOps (integrating security), Shift Left, AI/MLOps, and GitOps.



**GitOps**: Emphasizes that "our entire process should be in Git," ensuring everything is automated and version-controlled. Git becomes the "source of truth."



**IP Enabled Devices**: Any device with the four core computer characteristics can be assigned an IP address and become part of a network, allowing access to applications.



**Client-Server Architecture** :Core Idea: Simple concept often confused. The "server" serves information, and the "client" requests it.



**Examples**: Mobile transferring files to computer: Mobile is Server (giving files), Computer is Client (receiving files).

Mobile accessing Facebook: Facebook servers are Server (giving information), Mobile is Client (requesting information).

Browser is the client (Edge, Chrome, Firefox).



**Debugging**: Understanding client-server relationships is crucial for effective troubleshooting.

**Operating Systems for Servers**: Unix vs. Windows (Historical Context):Unix: Earlier popular server OS.

**Windows Server**: Gained popularity, but has disadvantages:

Not Open Source (Microsoft controls it).

High Graphics Consumption (consumes lots of memory/resources).

High Cost.

Less Security (closed source means vulnerabilities are harder to detect by the community).

The Microsoft Azure Outage (Recent Example): This highlights a recent Azure outage as a direct consequence of Microsoft's closed-source OS and potential lack of rigorous internal testing, affecting numerous services globally, even Linux-based VMs running on Azure's underlying Microsoft OS infrastructure. This reinforces the need for open-source and transparent systems.



**Linux (The Preferred Solution)**:No Graphics (console-based, less resource consumption).

Free \& Open Source (community-driven security patches, inherent security).

Cost-Effective. Speed (direct commands to hardware, unlike Windows clicks).



**Origin**: Developed by a Unix developer who wanted to create an OS without the hardware lock-in common with Unix (similar to Apple's macOS). He built it from scratch using C and released it to the public.



**Derivatives**: Ubuntu, CentOS, Fedora, Solaris, Android, Red Hat are all based on the Linux kernel.



**Importance for DevOps**: DevOps engineers constantly deal with servers, making Linux proficiency essential. "Applications will all be on Linux servers," making it a mandatory skill for developers and database professionals as well.



**Distributions**: Red Hat (enterprise-level support, paid), CentOS/AlmaLinux (community versions, free), Ubuntu, etc. All are 99% similar.



**DevOps and Cloud Integration (AWS):**

**Dynamic Environment:** DevOps requires a dynamic environment where servers can be automatically created as traffic increases. This is primarily achieved through Cloud platforms.



**On-Premise Limitations**: On-premise environments cannot scale automatically like the cloud.



**Synergy**: "Cloud and DevOps are like two wheels to a bike." Combining DevOps processes with Cloud (specifically AWS) leads to "super-speed" applications.



**Real-World Example**: The "Aha" platform outage during a popular interview (Prabhas) is cited as an example of poor cloud strategy, where servers failed to scale adequately with increased viewers. This course will cover how to deal with such issues.



**AWS Account Requirement**: An AWS account is mandatory for the course to practice real-world projects. It's considered more important than a Facebook or Instagram account for a DevOps engineer.

