# Requirement Analysis in Software Development
The Requirement Analysis Project focuses on crafting a comprehensive foundation for software development by documenting, analyzing, and structuring requirements

# What is Requirement Analysis?
Requirement analysis is a critical phase in the software development lifecycle where the Project team gathers, analysis and defines the functional and non-functional
requirements that the software should meet. With this, stakeholders and the development team are on the same page and know exactly what the outcome should look like.
It also prevents scope creep by clearly defining the scope of the project.

# Why is Requirement Analysis Important?
- Clarity and Understanding: It helps in understanding what the stakeholders expect from the software, reducing ambiguity.
- Cost and Time Estimation: Facilitates accurate estimation of project cost, resources, and time.
- Quality assurance: Ensures that the final product meets the desired requirements, leading to higher customer satisfaction

# Key Activities in Requirement Analysis
- Requirement Gathering: This includes organizing workshops with stakeholders to gather requirements, distributing surveys for feedback from larger audience,
  conducting interviews with stakeholders to get their needs and expectations.

- Requirement Elicitation: brainstorming sessions to create new requirements, focus group sessions with selected stakeholders to gather detailed requirements,
  prototyping for stakeholders to visualize the product's look and performance.
  
- Requirement Documentation: creating a detailed document that lists all functional and non functional requirements, documenting user stories to view product from user's
  perspective.
  
- Requirement Analysis and Modeling: priortizing requirements based on their importance, analysing the feasibility of requirements in terms of cost and technical
  constraint.
  
- Requirement Validation: Reviewing the documented requirements with stakeholders to ensure accuracy and completeness, drafting clear acceptance criteria.

# Types of Requirements
## Functional requirements
Describes what the system should do
Examples: 
- Hotel Management Service: In this managers can manage their hotel's related information. Here managers have a separate portal to access the data and update it.
- View Booking Service:  In this customers can search and book a hotel.

## Non functional requirements
Describes how the system should perform
Examples:
- Performance: The booking service communicates with Redis and the booking database cluster. Redis is caching system, that’s stores temporary data so that data need not fetched database and which could eventually reduce the load in the database also reduce the response time of API.
- Scalability: Whenever an API is triggered from the hotel manager app the initial request is been sent to the load balancer, then the load balancer distributes the requests to the desired server to process. The load balancer makes it scalable for increased traffic.

# Use Case Diagrams
Use case diagrams show how different users (actors) interact with the system to achieve specific goals (use cases). It provides a clear visual representation of system functionalities.

<img width="626" height="491" alt="alx-booking-uc(1)" src="https://github.com/user-attachments/assets/2e276433-5227-4941-a4d6-acde743d0925" />

# Acceptance Criteria
Acceptance criteria are conditions that a feature must meet to be accepted by the stakeholders.
Benefits

- Ensure all parties have a clear understanding of feature requirements.
- Provide a basis for testing and validation.
- Help in maintaining quality and meeting user expectations.

Example
Users should be able to select available dates, confirm booking, and receive a confirmation email within 2 minutes
