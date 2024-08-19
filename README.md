# Performance Testing Fundamentals

According to the ISTQB Syllabus — CTPT 1.0. Some of the performance tests have similar definitions. It is important to know the concepts of each test separately. In order to have a broader and more assertive analysis of the performance quality of a system, it is also important to combine several of these tests, considering the context and the performance criteria defined for each system. Develop a performance testing plan with the types of tests that can highlight defects in the performance quality according to the established criteria.

In this repository, we will briefly address what will be discussed during the event on Performance Testing where this document is an integral part of the event **QA Solidário - RS Second Edition**
![image](https://github.com/user-attachments/assets/6fabf60c-f607-4ca0-a6f2-08b4bca4c96d)

By understanding that Non-Functional Testing evaluates aspects of an application that are not directly linked to the main functionality, but are essential to the overall quality of the software, verifying how the system behaves under different conditions, focusing on characteristics such as performance, security, usability and reliability. We can understand that these tests help to ensure that the software not only works correctly, but also offers a good user experience, is secure and robust, and works well in different situations and contexts according to the established business rules and market demands.

Performance tests, which are a specific type of non-functional test, measure the speed, responsiveness and stability of an application under various load conditions. These tests are applied to various types of applications, such as websites, mobile applications, corporate systems, client-server systems, databases, among others, to ensure that they can have:

  1. Speed: The application responds quickly to user requests, even when many access it at the same time.
  2. Stability: The application continues to function correctly even under heavy load or during long periods of use.
  3. Scalability: The application can be scaled (increased in terms of resources) to handle more users or larger volumes of data without losing performance.

**These tests are vital to ensure that an application delivers high reliability, security and ease of use, offering a positive experience to end users.**

In order to be assertive in determining the focus and prioritization of tests, we must first map out the application's risks and needs, based on the user experience. After analyzing the test results, other risk areas may be identified and need to be addressed. Thus, performance has three distinct and simplified sub-characteristics in addition to those presented above, making the two triads merge into one:

### - Time behavior
Time behavior measurements can range from the end-to-end period used by the system to respond to user input, to the number of CPU cycles required by a software component to perform a specific task. For example, response time for a request sent to an API endpoint

### - Resource utilization
When implementing a new feature in a system (for example, a user credentials and permissions manager such as Keycloack), it is important to verify that the resources available for the use of this feature are sufficient and allow for adequate performance without compromising other existing features.

### - Capacity
the system or resource is subjected to a peak in data volume or user access close to or above the planned limit to be supported, in order to verify the behavior of the system.

## What performance metrics should I monitor closely?

Here are some of the performance metrics that we can monitor closely to know if our application is performing well within the expectations of management, business, engineering and, of course, the end customer. To ensure that a performance test is truly efficient, it is crucial to monitor a series of metrics that provide detailed insights into the behavior of the system under different workloads. Here are some of the main metrics to monitor:

**Response Time**

Response time is a fundamental metric that indicates how long the system takes to respond to a request. This includes the time from when the request is sent until the complete response is received. Monitoring response time helps to identify whether the system is fast enough to meet user expectations. Ideally, response time should be as low as possible, even under maximum load.

**Throughput**

measures the amount of data processed by the system in a given period of time. It can be expressed as the number of transactions per second (TPS) or the number of requests per second.

**Resource Utilization**

This metric measures the use of system resources such as CPU, memory, disk, and network.

**Error Rate**

The error rate indicates the percentage of requests that fail compared to the total requests. A high error rate can be a sign that the system is not handling the load well, resulting in failures or incorrect responses. It is essential to keep the error rate as low as possible to ensure system reliability.

**Latency**

Latency refers to the delay in communication between the client and the server. It is the time it takes for a message to travel from one end to the other. High latency can significantly impact the user experience, especially in applications that require fast responses. Monitoring latency helps ensure that the system can provide fast responses even under loaded conditions.

**Scalability**

measures the system's ability to grow and handle an increasing load efficiently. This may include adding more users, transactions, or data.

**Capacity**

Capacity indicates the maximum number of users or transactions that the system can support while still meeting performance requirements.

**Reliability**
Reliability measures the ability of the system to function correctly without failure for a given period of time. This includes uptime analysis and the ability of the system to recover from failures. Monitoring reliability is essential to ensure that the system can provide continuous, high-quality service.

**There are other metrics, but these give us a clinical view into the context of delivering quality to any application with incredible delivery!**

## What are the requirements for running the performance test?

In order to perform performance tests, it is important to have in mind a pre-defined sequence of steps to follow, so that we can guarantee the accuracy and usefulness of the results. Below are the main requirements that, in my understanding, are important for performing performance tests:

1. Clear Definition of Objectives
2. Appropriate Test Environment
3. Appropriate Test Tools
4. Detailed Test Plans
5. Realistic Data
6. Continuous Monitoring
7. Analysis of Results
8. Repeatability and Validation
9. Documentation and Reporting

**Benefits of Monitoring Metrics** 

By monitoring these metrics during performance testing, we will have a comprehensive view of the health and efficiency of the system. This allows companies to:
  • Identify Performance Bottlenecks
  • Optimize Resource Usage
  • Improve User Experience (UX)
  • Plan for Scalability    

## And last but not least, we can mention some of the challenges in performance testing:

  - Test Environment Configuration
  - Definition of Realistic Test Scenarios
  - Realistic Load Generation
  - Monitoring and Data Collection
  - Analysis and Interpretation of Results
  - Maintenance of Test Scripts
  - Test Scalability
  - Cost and Time
