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


