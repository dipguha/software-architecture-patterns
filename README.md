# software-architecture-patterns

What is Execution orchestrator pattern software architecture Pattern. provide High level descriptions, Use cases and problems it solves, Core principles, Implementation techniques, Implementation considerations and Observations, best practices and code examples

# Lecture 1: Cloud Computing SA Patterns
1. Why do we need Software Architecture patterns
  1. Solution to common problem and non-functional requirements 
3. Differnece bwtween design patterns vs cloud software architecture patterns
4. System requirements
   1. Functional requirements - dictate the features of the product. Business logic and user experience.
   2. Quality attributes - scalability, reliability, availability, performance, security and cost, organizational scalability/extensibility, developer productivity
   3. System constraints - limit the design choices
 5. Design patterns (factory, 
    1. Better code organization
    2. reusability
    3. extensibility
    4. Developer productivity
    5. Mostly for Object oriented programming languages
    6. limited to single apps/library
  7. Cloud computing pattern
     1. Access to infinite computation, storage, network - IaaS
     2. Tools and features to improve
        1. Performance - multi region deployment - close to users
        2. Scalability - multi zone deployment - 
        3. Reliability and availability
     3. Platform with services like Database, Message Brokers, Load Balancers, Monitoring, Log services, FaaS
     4. Drawback
       1. Cost awareness
       2. Built for failure
       3. Building reliable system using unreliable components

# Lecture 2: Scalability patterns
- This pattern allows to architect and deploy a highly scalable system that enables handle billions of requests/day and process petabytes of data in cost effective way.
- **What is load balancing pattern and how it works**
	- Dispatching every request from a sender to only one worker
- Technique to apply load balancing in Cloud environment
 - Problem statement
 	- How millions of users access the same resource at the same time?
- Use cases
- Implementation technique
	- Cloud load balancing service
 	- Message broker/distributed message queue - the main purpose isn't load balancing
  		- One way and internal services
- Implementation considerations
	- Which algorithm to use for routing requests to downstream. Stateless/Stateful, duration of the connection
 		- Round-Robin
   		- Stick session / Session affinity
     	- Least connection
	- Combine Auto scaling and load balancing
- Pipes and Filters patterns
	- 
- Scatter Gather Pattern
	- High level descriptions
 	- Use cases and solved problems
  	- Core principles
  	- Implementation techniques
  	- Implementation considerations
  	- Observations
  	- Best practices
  	- Code examples
- Execution orchestrator pattern
	- What is Execution orchestrator pattern software architecture Pattern. provide High level descriptions, Use cases and problems it solves, Core principles, Implementation techniques, Implementation considerations and Observations, best practices and code examples




    
