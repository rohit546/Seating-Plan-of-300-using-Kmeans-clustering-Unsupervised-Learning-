# Seating-Plan-of-3000 Students-using-Kmeans-clustering-Unsupervised-Learning-
The university has 30 rooms available for conducting exams, and there are approximately 2400 to 2500 students across batches 19, 20, 21, and 22 in various domains, including computer science, artificial intelligence, business analytics, software engineering, and electrical engineering. Each room has a capacity of 30 to 35 students, 

you are required to design and implement an automated exam management system that can efficiently manage the
seating plan and faculty allocation for the computer science, artificial intelligence, business analytics, software
engineering, and electrical engineering students in batches 19, 20, 21, and 22. The project aims to efficiently assign
duties to faculty members and create an optimal seating plan for students during exams. The system should use the k-
means clustering technique to automate the seating plan and faculty allocation. The k-means clustering technique is a
popular machine learning algorithm used to group similar data points together. In this case, the data points are the
students and their respective domains.


Problem Statement:
The university has 30 rooms available for conducting exams, and there are approximately 2400 to 2500 students
across batches 19, 20, 21, and 22 in various domains, including computer science, artificial intelligence, business
analytics, software engineering, and electrical engineering. Each room has a capacity of 30 to 35 students, with a few
rooms having a capacity of 25 seats. There are also faculty members available for each domain.
The challenge is to automate the process of assigning duties to faculty members and creating an efficient seating plan
for the students during exams, taking into account the batch distribution, domain of study, room capacities, and
faculty availability.

The system should be able to perform the following tasks:
1. Data Collection: Collect data about number of students from batches 19, 20, 21,22 and 23 in each domain
(computer science, artificial intelligence, business analytics, software engineering, and electrical
engineering). Collect information on the capacity of each room, including rooms with varying seat capacities.

3. Data Preprocessing: Clean and preprocess the data to ensure it is suitable for the k-means clustering
algorithm.

4. K-Means Clustering: Use the k-means clustering algorithm to group the students based on their domains
and batch numbers. Use the number of students from each domain and batch as features for clustering.
Determine the optimal number of clusters based on domain and batch distribution.


6. Seating Plan: Generate a seating plan for each room based on the clusters formed. Ensure that the capacity
of each room is not exceeded. Optimize seating arrangements to minimize disruptions and ensure a
conducive exam environment. Account for any special requirements or accommodation for certain students.


8. Faculty Allocation: Allocate faculty members to each room based on the clusters formed. Ensure that each
room has at least one faculty member from each domain. Assign faculty members to each cluster based on
their domain expertise. Ensure that each faculty member is assigned to a cluster with students from relevant
domains.


10. Reporting: Generate a report that summarizes the seating plan and faculty allocation for each exam.
Project Goals:
The goal of the project is to develop an automated system that:
1. Uses K-means clustering to group students based on their domains of study, ensuring that students from the
same domain are seated together.
2. Group up the students based on batch distribution and room capacities, ensuring that each room is filled to its
maximum capacity without exceeding the limit and groups should be based on different exams in same room.
3. Assigns faculty members to each exam room based on their expertise in the corresponding domain of study.


Project Deliverables:
The project should deliver the following components:
1. An algorithm or program that implements the K-means clustering technique to group students based on their
domains of study.
2. An algorithm or program that generates an optimized seating plan, considering batch distribution, room
capacities, and student clusters.
3. An algorithm or program that assigns faculty members to each exam room based on their domain expertise.
4. A user-friendly interface that allows administrators to input student and faculty data and view the generated
seating plan and faculty assignments.
