Site Reliability Engineer (SRE) Interview Questions:
    1. What is the role of a Site Reliability Engineer?
        ○ Answer: SREs are responsible for maintaining the reliability, availability, and performance of production systems. They bridge the gap between software development and IT operations, applying software engineering practices to infrastructure and operations.
    2. What are SLIs, SLOs, and SLAs?
        ○ Answer:
            § SLI (Service Level Indicator): A metric that indicates the performance of a service (e.g., response time).
            § SLO (Service Level Objective): A target or goal for an SLI, such as a 99.9% uptime.
            § SLA (Service Level Agreement): A contract that defines the agreed-upon SLOs between a service provider and customer.
    3. How do you ensure high availability of a system?
        ○ Answer: High availability can be achieved through strategies like load balancing, failover systems, replication, distributed databases, and multi-region deployments. Monitoring and proactive incident management are also essential.
    4. What is the difference between a traditional operations engineer and a Site Reliability Engineer?
        ○ Answer: A traditional operations engineer focuses on managing and maintaining systems, whereas an SRE applies software engineering to ensure reliability, automate processes, and focus on scalability and performance. SREs prioritize proactive measures like automation and monitoring.
    5. How do you handle incidents in a production environment?
        ○ Answer: The first step is to identify and contain the incident. Then, perform a root cause analysis and restore the system to a stable state. Afterward, conduct a post-mortem to understand what went wrong and how to prevent it in the future.
    6. What is a "blameless post-mortem"?
        ○ Answer: A blameless post-mortem encourages a non-punitive environment where the team focuses on understanding what went wrong, learning from the incident, and improving the system instead of blaming individuals for the failure.
    7. What is capacity planning, and how do you perform it?
