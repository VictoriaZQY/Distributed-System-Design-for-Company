# Distributed System Design for Company
This project evaluated and designed a practical strategy considering the actual company conditions, including comparing Peer-to-Peer (P2P), Microservices Architecture & Client-Server Architecture; Hadoop Distributed File System (HDFS), Amazon S3 & Local Storage; gRPC, RabbitMQ & HTTP/HTTPS (REST APIs).


## Assignment Description:
For this assignment, you are to act as a consultant for a company that wishes to move its organization to a distributed system. You are asked to write a report for the company CEO who does not have any experience with any area of distributed systems. Describe factors that the company should consider in technical detail, the potential pros and cons of each, and, using real-world examples, suggest potential products or solutions that could match their needs. Finally, make a recommendation of what the final distributed system would look like and your opinion of the future of distributed systems. This should be a structured, methodical report with a clear understanding of the issues within each of the concepts.

## Planning the Solution
A distributed system offers this recruitment company the opportunity to overcome the limitations of a centralized setup, such as single points of failure, limited scalability, and reduced flexibility. With independent nodes working collaboratively, the system can enhance fault tolerance, improve availability, and enable scalability to meet growing operational demands.

Given the current conditions of the company: a rural, large-sized department recruitment company with a single office and no IT department, the solution must prioritize low-bandwidth dependency, ease of implementation, and operational reliability.

## Proposed System Design Architecture
Given the rural location and limited IT resources, this company requires a distributed system that balances simplicity, scalability, and resilience. After evaluating multiple architectures, the Client-Server model is recommended for its ease of implementation, with a transition toward Microservices for long-term scalability. Peer-to-Peer (P2P) can serve as a supplementary mechanism for decentralized storage and fault tolerance.

-----

For details, please check the files.
