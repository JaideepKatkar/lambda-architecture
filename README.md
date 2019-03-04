# lambda-architecture
Study of lambda architecture
Publication Date
Fall 2015

Degree Type
Master's Project

Degree Name
Master of Science (MS)

Department
Computer Science

Abstract
The lambda architecture introduced by Marz is generic, scalable and fault-tolerant data processing architecture. It aims to satisfy the needs for a robust system that is faulttolerant, both against hardware failures and human mistakes, being able to serve a wide range of workloads and use cases. The architecture proposal decomposes the problem into three layers: a) the batch layer focuses on fault tolerance and optimizes for precise results b) the speed layer is optimized for short response-times and only takes into account the most recent data and c) the serving layer provides low latency views to the results of the batch layer. The reason to divide the architecture into three layers is the flexibility it offers to the potential applications. The fast but possibly inaccurate results of the speed layer are eventually replaced by the precise results of the batch layer. The evaluation of the designed architecture measured its capabilities based on the DEBS grand challenge 2014 and percentile calculation for milestones task. As part of the project we implement the lambda architecture in different ways (i.e. using different systems). We compare these different implementations and derive the strengths and weaknesses of each different system used in the lambda architecture.

https://scholarworks.sjsu.edu/etd_projects/458/
