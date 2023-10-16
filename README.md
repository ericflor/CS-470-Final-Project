# CS-470-Final-Reflection

Conference Presentation Submission: Migrating to a Cloud-Native Web Application Using AWS Microservices 

Eric Florence 

Oct 15, 2023 

 

YouTube link: [Project Two Presentation ](https://www.youtube.com/watch?v=8vcZwH2xt24)

 
 

OUTLINE: 

 

Slide 1: Introduction 

Image: Professional photo 

Script: "Hello everyone, I'm Eric Florence, a recent Computer Science graduate. Today, I will share with you the journey of migrating a full-stack application to AWS serverless architecture, and the challenges and solutions we encountered along the way." 

 
 

Slide 2: Purpose of Presentation 

Image: Cloud with arrows showing movement from a traditional infrastructure 

Script: "The aim of this presentation is to detail the nuances of cloud development for both technical and non-technical audiences. Let's dive into the world of cloud!" 

 
 

Slide 3: Containerization and Orchestration 

Image: Screenshot of Docker Compose 

Script: "When moving to the cloud, we leveraged containerization using Docker. It provides a consistent environment and simplifies deployment. Docker Compose, in particular, enabled us to define and run multi-container applications seamlessly." 

 
 

Slide 4: The Serverless Cloud 

Image: UML diagram highlighting serverless components 

Script: "Serverless is the idea of building and running apps without thinking about servers. One advantage is that you only pay for the compute time you consume. We chose AWS S3 for our frontend as it offers scalable and durable object storage, making it a preferred choice over local storage." 

 
 

Slide 5: Integrating Frontend with Backend 

Image: UML diagram showcasing the connection between frontend (Angular) and backend (Lambda) 

Script: "Lambda provided the logic for our API. With a few scripts, we were able to connect our Angular frontend to the backend, ensuring seamless CRUD functionality for our questions and answers module." 

 
 

Slide 6: Data Models: MongoDB vs DynamoDB 

Image: Side-by-side comparison table or diagram for MongoDB and DynamoDB 

Script: "We migrated our data from MongoDB to DynamoDB. While MongoDB is document-oriented, DynamoDB is a key-value store. Adapting to the query differences was challenging, but with the right scripts, we made the transition smoothly." 

 
 

Slide 7: Cloud-Based Development Principles 

Image: graph comparing Capacity vs. Usage 

Script: "AWS promotes elasticity, automatically adjusting resources as per demand. Furthermore, the pay-for-use model ensures we only pay for the resources we use. This flexibility optimizes costs and performance." 

 
 

Slide 8: Securing Your Cloud Application 

Image: Diagram illustrating the secure connections between Lambda, Gateway, and S3 

Script: "Security is paramount. We implemented IAM roles and custom policies to ensure unauthorized access was averted. Connections between Lambda, Gateway, and our S3 bucket were also encrypted to ensure data integrity and security." 

 
 

Slide 9: Salient Points 

Image: Cloud icon with three key points highlighted around it 

Script: "1) Migrating to serverless simplifies scalability and operations. 2) Proper tools, such as Docker and AWS services, make the transition smoother. 3) Ensuring security and understanding cloud principles are key to a successful migration." 

 
 

Slide 10: Conclusion 

Image: Cloud with a check mark symbol 

Script: "In summary, migrating to a cloud-native application using AWS microservices has been a transformative experience. The lessons learned have been invaluable, and I hope my insights today assist others on their cloud journey." 

 
