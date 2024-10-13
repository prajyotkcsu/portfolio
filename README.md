# Software Engineer
*Hi, I’m a backend engineer with close to 5 years of experience. My formal education in computer science, dedication to daily coding practice, and passion for writing technical blogs equip me to tackle challenges head-on and continually grow as an engineer.*

### What technologies I use
- I code in Java but I also written programs in Python, Node.js, Javascript, C++ at some point in history, and now I'm learning Go on the side. *example code: [https://github.com/prajyotkcsu/leetcode-solutions]*
- I'm a Spring Boot neard, it's a Java-based web framework. *example code: [https://github.com/prajyotkcsu/remind-gpt]* 
- REST API, GraphQL, and gRPC protocol to build APIs and expose backend services.
- Kubernetes, Docker, Linux, Harness, GitLab as part of deployment strategies.
- Kafka, Flink, Spark, RabbitMQ, Elasticsearch for processing, searching, and streaming data.
- AWS cloud and it's most 

### Education
- M.S.; Business Analytics; California State University, East Bay (May 2023)
- B.S.; Information Technology; Mumbai University (May 2017)

### Work Experience
**Software Engineer @ Dish Network (March 2024 - Present)**
*I’m a developer on this epic team called ‘Events’  that handles communication on behalf of other teams. This involves receiving close to 10 million events and notifications in a single day and routing them to their respective targets.*

### Projects I have built or contributed to independently so far

###### 1.	Unified Deployment with Harness
We traditionally used GitLab for code deployment across repositories and CloudFormation for AWS-based software. As pipeline issues arose—code inconsistently deploying across environments and delayed approvals due to inaccessible files—we conducted R&D to find a better solution. This led to adopting Harness, unifying deployments on a single platform for better tracking and consistency.
###### 2.	Scaling Event Processing to 5 Million Without Lambda Throttling
We scaled event processing from 1 million to 5 million without crashing AWS Lambda by introducing AWS SQS as a pseudo buffer between AWS EventBridge and Lambda. This effectively prevented Lambda throttling, enabling smooth and efficient scaling.
######  3.	API for Safe Event Stream Management
We designed an API to shut off the stream of events from specific sources flagged as unsafe, ensuring the rest of the workflow continued uninterrupted.
###### 4.	Customizable Delays for Event Delivery
In scenarios requiring delayed event delivery (e.g., 15, 25, or 45 minutes), we developed an endpoint that accepts a customizable delay value. AWS Scheduled Events were used to manage these delays with precision.


**Software Engineer @ Financial Software & Systems (March 2018 - March 2021)**
- Built numerous features for a data platform that routes over 1M events daily, including mechanisms such as retry, replay, incident creation, and delay management, using Java Spring Boot and AWS Lambdas.
- Enhanced platform storage by introducing AWS DynamoDB, enabling high query volumes and supporting key features like automatic archival and Capture Data Change with DynamoDB Streams.
- Engineered Apache Kafka infrastructure and servers to stream messages from various sources with 12% reduced cost.
- Improved developer experience by 35 % with gRPC, GraphQL APIs to expose backend databases, enhancing API reusability and speeding up preference retrieval with Redis caching.
