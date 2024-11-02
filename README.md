# Google Cloud Digital Leader Certification Exam Cheat Sheet

---

## Section 1: Digital Transformation with Google Cloud (~17% of the exam)

### 1.1 Why Cloud Technology is Transforming Business

**Definitions:**
- **Cloud:** A network of remote servers hosted on the Internet to store, manage, and process data.
- **Cloud Technology:** Utilization of cloud computing services for various IT resources, including storage and processing power.
- **Data:** Information that is processed or stored by a computer, essential for decision-making and analytics.
- **Digital Transformation:** The integration of digital technology into all areas of a business, leading to fundamental changes in operations and value delivery.
- **Cloud-Native:** Applications designed specifically to leverage the benefits of cloud computing architecture.
- **Open Source:** Software for which the original source code is made freely available and may be redistributed and modified.
- **Open Standard:** Publicly available specifications that ensure interoperability between different systems and software.
- **Hypervisor:** Software that creates and runs virtual machines (VMs).
- **Lightweight Directory Access Protocol (LDAP)** is an application protocol for accessing and managing directory services over a network, commonly used for user authentication, authorization, and storing hierarchical information about users and resources.

**Differences:**
- **Cloud Technology vs. Traditional Technology:**
  - **Cloud Technology:** Offers scalability, flexibility, and on-demand resources without the need for physical infrastructure.
  - **Traditional Technology:** Involves fixed, on-premises infrastructure requiring significant upfront investment and ongoing maintenance.

**Benefits of Cloud Technology:**
- **Scalable:** Easily increase or decrease resources based on demand.
- **Flexible:** Access applications and data from anywhere with an internet connection.
- **Agile:** Rapidly deploy and iterate applications to respond to market changes.
- **Secure:** Advanced security protocols and compliance measures.
- **Cost-effective:** Pay-as-you-go model reduces upfront costs and optimizes expenditure.
- **Strategic Value:** Enables innovation and focuses resources on core business objectives.

**Infrastructure Types:**
- **On-Premises Infrastructure:** Provides maximum control and customization but comes with high capital and operational costs.
- **Public Cloud:** Offers extensive services with lower costs but less control and customization.
- **Private Cloud:** Provides a dedicated environment for a single organization, balancing control and security.
- **Hybrid Cloud:** Combines public and private clouds for flexibility in resource management.
- **Multicloud:** Uses multiple cloud services from different providers to avoid vendor lock-in and optimize performance.

**Primary Benefits of Google Cloud:**
- **Intelligence:** Incorporates AI and ML for data analysis and decision-making.
- **Freedom:** Offers open-source tools and interoperability.
- **Collaboration:** Enhances teamwork through integrated tools like Google Workspace.
- **Trust:** Strong security measures and compliance certifications.
- **Sustainability:** Commitment to renewable energy and carbon neutrality.

**Implications of Not Adopting New Technology:**
- Organizations may face obsolescence, reduced competitiveness, and increased operational costs, potentially resulting in lost market share.

**Drivers and Challenges of Digital Transformation:**
- **Drivers:** Market demands, technological advancements, customer expectations, and competitive pressures.
- **Challenges:** Resistance to change, integration with legacy systems, and skills shortages.

**Transformation Cloud:**
- A framework that accelerates digital transformation through modernizing applications, democratizing data access, enhancing collaboration, and enabling trusted transactions.

---

### 1.2 Fundamental Cloud Concepts

**Impact of Transitioning to Cloud:**
- **Flexibility:** Resources can be adjusted in real-time based on needs.
- **Scalability:** Support for growth without significant upfront investment.
- **Reliability:** High availability and resilience through redundant systems.
- **Elasticity:** Automatic scaling of resources based on workload demands.
- **Agility:** Faster deployment times for applications and services.
- **Total Cost of Ownership (TCO):** Reduced long-term costs through efficient resource utilization.

**CapEx to OpEx Shift:**
- Transitioning to the cloud changes capital expenditures (hardware and infrastructure costs) to operational expenditures (ongoing service costs), enabling organizations to allocate resources more effectively.

**Infrastructure Types Application:**
- **Private Cloud:** Best for organizations with strict compliance and security needs.
- **Hybrid Cloud:** Suitable for businesses needing flexibility between on-premises and cloud deployments.
- **Multicloud:** Ideal for organizations wanting to leverage the best services from multiple vendors while avoiding dependency on a single provider.

**Key Network Infrastructure Terms:**
- **IP Address:** Unique identifier for devices on a network.
- **ISP (Internet Service Provider):** Company providing internet access to users.
- **DNS (Domain Name Server):** Translates domain names into IP addresses for routing.
- **Regions/Zones:** Geographic divisions of cloud infrastructure to enhance availability and reduce latency.
- **Latency:** Delay in data transmission, affecting application performance.
- **Bandwidth:** The maximum rate of data transfer across a network.

**Google Cloud Infrastructure:**
- Google Cloud’s global network of data centers ensures high performance and low latency for users.

---

### 1.3 Cloud Computing Models and Shared Responsibility

**Definitions:**
- **IaaS (Infrastructure as a Service):** Provides virtualized computing resources over the internet, allowing users to rent IT infrastructure.
- **PaaS (Platform as a Service):** Offers a platform for developers to build, deploy, and manage applications without dealing with the underlying infrastructure.
- **SaaS (Software as a Service):** Delivers software applications over the internet on a subscription basis, eliminating the need for installation and maintenance.

**Benefits and Tradeoffs:**
- **IaaS Benefits:** High flexibility and control, but requires more management and expertise.
- **PaaS Benefits:** Simplifies deployment and management of applications, but offers less control over the underlying infrastructure.
- **SaaS Benefits:** Minimal management required, quick deployment, but limited customization options.

**Shared Responsibility Model:**
- **Cloud Provider Responsibilities:** Securing the cloud infrastructure, including physical security and foundational services.
- **Customer Responsibilities:** Managing data security, compliance, and access control for their applications and data.

---

## Section 2: Exploring Data Transformation with Google Cloud (~16% of the exam)

### 2.1 The Value of Data

**Data's Role in Digital Transformation:**
- Data drives insights, informs decision-making, and creates new revenue opportunities.

**Data Management Concepts:**
- **Databases:** Structured collections of data, typically managed by a Database Management System (DBMS).
- **Data Warehouses:** Central repositories optimized for reporting and analytical queries, integrating data from multiple sources.
- **Data Lakes:** Storage repositories that hold raw data in its native format, accommodating both structured and unstructured data.

**Unlocking Data Value:**
- Organizations can leverage existing datasets, gather new data from various sources, and integrate external data for enhanced insights.

**Cloud and Data Value:**
- The cloud enables organizations to analyze vast amounts of structured and unstructured data, unlocking new opportunities for innovation.

---

### 2.2 Google Cloud Data Management Solutions

**Google Cloud Data Management Options:**
- **Cloud Storage:** Object storage for unstructured data, designed for high availability.
  - Enabling "Requester Pays" on a Cloud Storage bucket shifts the cost of data access to the requester, allowing public access while reducing organization's expenses.
- **Cloud Spanner:** Globally distributed relational database service for mission-critical applications.
- **Cloud SQL:** Managed relational database service for SQL databases like MySQL and PostgreSQL.
- **Cloud Bigtable:** NoSQL database for large-scale analytical and operational workloads.
- **BigQuery:** Serverless, highly scalable data warehouse designed for analytics.
- **Firestore:** NoSQL document database that lets you store, sync, and query data for mobile and web apps.

**Key Data Management Concepts:**
- **Relational:** Data organized in tables with defined relationships.
- **Non-relational:** Data stored in formats other than tables, such as documents or key-value pairs.
- **Object Storage:** Storage architecture for managing data as objects rather than files or blocks.
- **SQL:** Structured Query Language used for managing and querying relational databases.
- **NoSQL:** A category of database that provides flexible schemas for unstructured data.

**BigQuery Benefits:**
- Serverless architecture, allowing for quick data analysis without infrastructure management, and optimized for high-performance queries.

**Storage Classes:**
- **Standard:** For frequently accessed data.
- **Nearline:** For data accessed less than once a month; lower cost.
- **Coldline:** For infrequently accessed data, ideal for backups.
- **Archive:** For long-term storage with the lowest cost.

---

### 2.3 Making Data Useful and Accessible

**Smart Analytics:**
- **Looker:** A business intelligence tool that enables users to create reports and dashboards to democratize data access.

**Value of BigQuery and Looker:**
- Integrating data from BigQuery into Looker allows for real-time analytics, helping businesses make informed decisions quickly.

**Streaming Analytics:**
- Processes real-time data feeds to provide immediate insights, enhancing responsiveness to customer needs.

**Modern Data Pipelines:**
- Tools like **Pub/Sub** (for messaging) and **Dataflow** (for stream and batch data processing) facilitate efficient data movement and processing.
- Dataflow is a fully managed streaming data processing service that can handle large amounts of data from continuous sources. It is serverless, so you do not need to provision infrastructure or create server cluster

---

## Section 3: Innovating with Google Cloud Artificial Intelligence (~16% of the exam)

### 3.1 AI and ML Fundamentals

**Definitions:**
- **AI (Artificial Intelligence):** Machine capabilities to perform tasks that typically require human intelligence.
- **ML (Machine Learning):** A subset of AI focused on the development of algorithms that allow systems to learn from data.

**AI/ML vs. Analytics:**
- AI and ML automate decision-making processes, while analytics primarily focuses on interpreting historical data for insights.

**Types of Problems Solved by ML:**
- Classification (categorizing data), regression (predicting continuous values), and clustering (grouping similar data).

**Business Value of ML:**
- Enhances decision-making capabilities, processes vast datasets, scales operations, and provides insights from unstructured data.

**Importance of High-Quality Data:**
- Accurate and reliable data is crucial for training effective ML models; poor data leads to inaccurate results.

**Explainable and Responsible AI:**
- Emphasizes transparency in AI processes and ethical considerations to ensure fair and accountable AI outcomes.

---

### 3.2 Google Cloud’s AI and ML Solutions

**Selection Considerations:**
- Organizations should assess speed, effort, differentiation, and the expertise required when choosing AI/ML solutions.

**Applicable Google Cloud AI/ML Solutions:**
- Pre-trained APIs for quick implementation, **AutoML** for custom model development, and **Vertex AI** for comprehensive AI toolkit.

---

### 3.3 Building and Using Google Cloud AI and ML Solutions

**BigQuery ML:**
- Enables users to build and execute ML models directly within BigQuery using SQL, simplifying model development for analysts.

**Pre-trained APIs:**
- **Natural Language API:** Analyzes and understands text for sentiment and entity recognition.
- **Vision API:** Identifies objects within images and performs facial recognition.
- **Cloud Translation API:** Translates text between languages.
- **Speech-to-Text API:** Converts spoken language into text.
- **Text-to-Speech API:** Converts written text into spoken words.

**Custom Models with AutoML:**
- Allows organizations to train models on their datasets, tailoring solutions to specific business needs.

**Vertex AI:**
- A unified platform for developing, deploying, and managing ML models, providing a streamlined workflow for data scientists and developers.

**TensorFlow:**
- An open-source framework for building and training ML models, optimized for performance with Google’s Cloud Tensor Processing Unit (TPU).

---

## Section 4: Modernize Infrastructure and Applications with Google Cloud (~17% of the exam)

### 4.1 Cloud Modernization and Migration

**Benefits of Modernization:**
- Enhances operational efficiency, reduces costs, and promotes innovation.

**Main Migration Terms:**
- **Workload:** An application or service running on an IT infrastructure.
- **Retire:** Discontinue a workload or service.
- **Retain:** Keep an application on-premises.
- **Rehost:** Move an application to the cloud without modification (lift-and-shift).
- **Replatform:** Make minimal changes to optimize for the cloud.
- **Refactor:** Redesign an application to take full advantage of cloud capabilities.
- **Reimagine:** Redefine and innovate new applications or services.
- **Google Cloud Directory Sync**: to provision Google accounts and groups to access Google Cloud resources based on on-premises LDAP database, you can set up Google Cloud Directory Sync.
---

### 4.2 Computing in the Cloud

**Main Cloud Compute Terms:**
- **VMs (Virtual Machines):** Emulated computers running on a physical server.
- **Containerization:** Packaging applications and their dependencies into containers for portability.
- **Microservices:** Architectural style that structures an application as a collection of loosely coupled services.
- **Serverless Computing:** Allows developers to build applications without managing servers, automatically scaling based on demand.
- **Preemptible VMs:** Short-lived VMs that offer lower costs but can be terminated by Google at any time.
- **Kubernetes:** An open-source platform for automating the deployment, scaling, and management of containerized applications.
- **Autoscaling:** Automatically adjusts the number of active servers based on load.
- **Load Balancing:** Distributes incoming traffic across multiple servers to ensure high availability.

**Business Value of Cloud Computing:**
- Reduces infrastructure costs, enhances scalability, and improves operational efficiency.

---

### 4.3 Serverless Computing

**Benefits of Serverless Computing:**
- Eliminates server management, automatically scales based on demand, and allows developers to focus on code instead of infrastructure.

**Key Serverless Products:**
- **Cloud Run:** Deploys and manages containerized applications without managing servers.
- **App Engine:** Platform for building and hosting applications in multiple programming languages.
- **Cloud Functions:** Event-driven serverless compute service for lightweight functions.

---

### 4.4 Containers in the Cloud

**Advantages of Containerization:**
- Increases portability, efficiency, and consistency across different environments.

**Benefits of Containers and Microservices:**
- Enables rapid development, deployment, and scaling of applications, enhancing resilience and reducing time to market.

**Google Cloud Container Products:**
- **Google Kubernetes Engine (GKE):** Managed Kubernetes service for deploying and managing containerized applications.
- **Cloud Run:** Ideal for running stateless containers in a serverless environment.

---

### 4.5 The Value of APIs

**API Definition:**
- A set of protocols and tools for building software applications, allowing different systems to communicate.

**Creating Business Opportunities:**
- By exposing public-facing APIs, organizations can foster partnerships, monetize services, and enhance customer engagement.

**Business Value of Apigee API Management:**
- Provides tools for managing APIs, ensuring security, and analyzing usage to improve performance.

---

### 4.6 Hybrid and Multi-cloud

**Reasons for Hybrid and Multi-cloud Strategies:**
- Flexibility to choose the best platforms, risk management, and compliance with various regulatory requirements.

**Business Value of Anthos:**
- A platform that provides consistent management of applications across hybrid and multi-cloud environments, simplifying operations.

---

## Section 5: Trust and Security with Google Cloud (~17% of the exam)

### 5.1 Trust and Security in the Cloud

**Top Cybersecurity Threats:**
- Include data breaches, ransomware, insider threats, and DDoS attacks, all of which can have significant business implications.

**Cloud Security vs. Traditional Security:**
- Cloud security encompasses advanced technologies and practices designed to protect data and applications in cloud environments, while traditional security focuses on physical infrastructure security.

**Importance of Security Principles:**
- **Control:** Ensuring only authorized access to sensitive data.
- **Compliance:** Adhering to industry standards and regulations.
- **Confidentiality:** Protecting sensitive information from unauthorized access.
- **Integrity:** Ensuring data accuracy and consistency.
- **Availability:** Guaranteeing that data and applications are accessible when needed.

---

### 5.2 Google’s Trusted Infrastructure

**Defense-in-Depth Approach:**
- A multilayered strategy to secure data and applications from multiple angles, including physical security, network security, and application security.

**Role of Encryption:**
- Protects data at rest, in transit, and during processing, safeguarding it against unauthorized access.

**Authentication, Authorization, and Auditing:**
- **Authentication:** Verifying user identity.
- **Authorization:** Granting access to resources based on user roles.
- **Auditing:** Monitoring and logging access and changes to data.

**Two-Step Verification (2SV) and IAM:**
- 2SV adds an extra layer of security by requiring a second form of identification; IAM (Identity and Access Management) controls user access and permissions.

**Network Attack Protection:**
- Google Cloud Armor protects against DDoS attacks by providing infrastructure defense mechanisms.

---

### 5.3 Google Cloud’s Trust Principles and Compliance

**Trust Principles:**
- Google Cloud's commitment to transparency, accountability, and security in managing customer data.

**Transparency Reports and Audits:**
- Keeping customers informed and demonstrating compliance through regular audits and reports increases trust.

**Data Sovereignty and Residency:**
- Organizations can control where their data is stored to meet legal and regulatory requirements.

**Compliance Resource Center:**
- Provides access to compliance information and tools to help organizations meet industry and regional standards.

---

# Section 6: Scaling with Google Cloud Operations (~17% of the exam)

---

## 6.1 Financial Governance and Managing Cloud Costs

### Cloud Financial Governance Best Practices

**Definition:**
- **Cloud Financial Governance:** The set of practices and policies that ensure an organization’s cloud spending is aligned with its strategic goals and budgetary constraints.

**Key Practices:**
1. **Budgeting:**
   - Establish clear budgets for each department or project using cloud resources.
   - Regularly review and adjust budgets based on actual usage and projected needs.

2. **Monitoring:**
   - Utilize tools like Google Cloud’s **Billing Reports** and **Cost Management** features to track expenses.
   - Set alerts for budget thresholds to prevent unexpected overspending.

3. **Optimization:**
   - Regularly analyze usage data to identify underutilized resources.
   - Implement strategies such as rightsizing instances, scheduling workloads, and using committed use contracts to reduce costs.

### Key Cost-Management Concepts

1. **Resource Hierarchy:**
   - Organizes resources into a hierarchy: Organization > Folders > Projects > Resources. This structure helps manage permissions and billing effectively.

2. **Quotas:**
   - Limits set on resource consumption to prevent unexpected spikes in usage and costs. These quotas can be adjusted based on business needs.

3. **Budgets and Alerts:**
   - Create budgets in the Google Cloud Console to track spending against predefined limits. Set alerts that notify stakeholders when spending approaches or exceeds budgets.

### Cost Visualization

- **Cloud Billing Reports:**
  - Provides visibility into spending patterns, allowing users to filter costs by project, service, or location. 
  - Utilize **BigQuery** to analyze billing data for more nuanced insights and custom reports.

- **Recommendations:**
  - Google Cloud offers recommendations for cost savings based on usage patterns, such as switching to lower-cost storage classes or resizing VM instances.

---

## 6.2 Operational Excellence and Reliability at Scale

### Modern Operations Benefits

1. **Streamlined Processes:**
   - Implementing automation tools reduces manual intervention, leading to faster deployments and fewer errors.

2. **Improved Efficiency:**
   - Use of orchestration tools (e.g., **Google Kubernetes Engine**) to manage workloads, leading to better resource utilization.

3. **Reduced Downtime:**
   - Continuous monitoring and automated recovery processes improve system reliability and minimize downtime.

### Key Operations Terms

1. **Reliability:**
   - The ability of a system to consistently perform its required functions under stated conditions for a specified period.

2. **DevOps:**
   - A cultural and technical movement that emphasizes collaboration between software development and IT operations to improve efficiency, speed, and reliability in delivering software.

3. **SRE (Site Reliability Engineering):**
   - A discipline that incorporates aspects of software engineering to build and run scalable and reliable systems. SRE focuses on automation, monitoring, and improving system reliability.

### Designing for Resilience

- **High Availability:**
  - Use multiple instances across different regions and zones to ensure application availability even in case of failure.
  
- **Disaster Recovery:**
  - Implement strategies such as regular backups, data replication, and failover systems to ensure business continuity.

- **Service Level Objectives (SLOs) and Agreements (SLAs):**
  - Define clear SLOs for availability, performance, and error rates, and establish SLAs with customers to set expectations for service reliability.

### Google Cloud Customer Care

- **Support Plans:**
  - Google Cloud offers various support plans (Basic, Standar, Enhanced, and Premium) to cater to different organizational needs, providing access to technical support, account management, and training resources.

- **Resources and Documentation:**
  - Comprehensive documentation, tutorials, and community forums to help organizations troubleshoot issues and optimize their cloud environments.

---

## 6.3 Sustainability with Google Cloud

### Commitment to Sustainability

**Corporate Responsibility:**
- Google Cloud is committed to minimizing its environmental footprint by using renewable energy sources and implementing energy-efficient practices in its data centers.

### Products Supporting Sustainability Goals

1. **Carbon Footprint Reporting:**
   - Tools to measure and report the carbon impact of cloud workloads, helping organizations assess their environmental impact.

2. **Sustainable Resource Management:**
   - Services that enable organizations to optimize resource usage, such as using preemptible VMs for non-critical workloads to reduce costs and energy consumption.

3. **Google Cloud Sustainability Reports:**
   - Regular reports detailing Google Cloud's sustainability efforts, including energy consumption, renewable energy usage, and carbon neutrality initiatives.

4. **Tools for Optimizing Workloads:**
   - Recommendations for optimizing workloads to be more energy-efficient, such as scheduling jobs during off-peak hours when the grid may be using more renewable energy.

---
