# Homework 5: Case Study

## Objectives

Explore the challenges and requirements of a real-time collaborative platform.

## Important Dates

| Event   | Day | Date   | Time        |
|---------|-----|--------|-------------|
| Release | Tue | Apr 09 | 11:00 AM ET |
| Due     | Tue | Apr 16 | 11:00 PM ET |

## Description: EduBoard Platform 

Steve, the IT manager responsible for the VidVersity app at Jeans Popkins College, has come forward with a new request. He needs assistance in designing a high-level architecture for EduBoard, an online whiteboard application that connects instructors and students in a dynamic, real-time collaborative environment. He has sent you an email with the requirements of this application.

1. **Real-time Collaboration:** Users should be able to see each other's changes on the whiteboard in real-time.

2. **Read-only Mode:** Educators should have the ability to set the whiteboard to read-only mode to prevent students from making changes during a lecture.

3. **Write Access Control:** Educators should be able to grant write access selectively to users (e.g., a teaching assistant or a specific student).

4. **Dual Whiteboard Modes:** EduBoard will provide two types of whiteboards:

   - **Ephemeral Whiteboard:** This allows for temporary whiteboarding without the need for session persistence.

   - **Persisted Whiteboard:** The state of the whiteboard will be saved, allowing it to be revisited or resumed in future sessions.

5. **Security:** To prevent unauthorized access and ensure privacy, it is important to securely handle user data and whiteboard contents. EduBoard should make use of the existing Learning Management System (LMS) capabilities for user authentication and authorization. This will ensure that only enrolled or authorized users can access the whiteboard sessions.

6. **Interoperability:** EduBoard should be designed to scale and potentially serve the broader education community, beyond just Jeans Popkins College. By aligning with Learning Tools Interoperability (LTI) standards, EduBoard aims to become the leading whiteboarding solution with seamless integration into Learning Management Systems (LMS), filling a gap in the current educational technology market.

7. Performance, Availability, and Scalability:

   - **Initial use:** The application should be highly available and capable of scaling to support hundreds of concurrent whiteboard sessions nationwide, with minimal latency.

   - **Broader adoption:** If the application is adopted by the broader community as an LMS whiteboarding solution, EduBoard should maintain high availability, resilience, and the ability to handle a significant number of concurrent sessions worldwide. It should handle high traffic and user interactions with minimal latency, providing a responsive and smooth experience.

8. **Cost Consideration:** Due to the uncertainty of user adoption, it is important for EduBoard to be built on an architecture that allows for cost-effective scaling. This ensures that infrastructure costs remain aligned with actual usage.

## Requirements

1. **Length & Format**: Your report should be written in Markdown format, in the `REPORT.md` file in this repository. Please adhere to the constraints put in place on the length of each section.
2. **Resources:** Make sure to list any resources you used to research the topic and write the report. These may include online resources like blog posts and YouTube videos, as well as more rigorous resources such as textbooks, papers, or lecture notes.
3. **Originality**: Collaboration and the use of resources, including AI-powered tools like ChatGPT, are encouraged for understanding and brainstorming. However, the content you submit should be written entirely on your own. Do not copy and paste from any source. Plagiarism will not be tolerated. Please note, the topics covered in this assignment may appear in future quizzes. Take this opportunity to thoroughly comprehend the subject matter.
4. **Clarity**: Your report should be written in clear, concise language. Avoid jargon unless it's necessary, and if used, ensure you provide explanations.

## Submission

Please submit your work on Gradescope by the deadline.