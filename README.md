### Project Description: Job Portal Application

**Project Title:** Job Portal Application

**Overview:**
The Job Portal Application, built using **Spring Boot** and **Spring Security**, is designed to connect job seekers and recruiters. It provides a platform for job listings, applications, and the management of recruitment processes. The application includes various functionalities for different types of users, such as administrators, recruiters, and job seekers. With features like job bookmarking, freelance opportunities, and a feedback system, it aims to be a comprehensive tool for the modern job market.

**Technologies Used:**
- **Backend:** Java, Spring Boot, Spring Security
- **Frontend:** Thymeleaf/React (or Angular)
- **Database:** MySQL
- **Other:** JPA/Hibernate for ORM, REST APIs

**Key Features and Controllers:**

1. **Admin Controller:**
   - **Features:**
     - User management (activation, deactivation, role assignment)
     - Job post approvals
     - System settings and configurations
     - Viewing and managing feedback and reports
   - **Endpoints:**
     - `/admin/users`
     - `/admin/jobs`
     - `/admin/settings`
     - `/admin/feedback`

2. **Bookmark Controller:**
   - **Features:**
     - Job bookmarking for users
     - Viewing and managing bookmarked jobs
   - **Endpoints:**
     - `/bookmarks`
     - `/bookmarks/{userId}`

3. **Freelance Controller:**
   - **Features:**
     - Posting freelance jobs
     - Searching and applying for freelance opportunities
     - Managing freelance job postings
   - **Endpoints:**
     - `/freelance/jobs`
     - `/freelance/applications`

4. **Feedback Controller:**
   - **Features:**
     - Submitting feedback about jobs, recruiters, and the platform
     - Viewing feedback and ratings
     - Responding to feedback
   - **Endpoints:**
     - `/feedback`
     - `/feedback/{jobId}`
     - `/feedback/{recruiterId}`

5. **Job Controller:**
   - **Features:**
     - Posting and managing job listings
     - Searching for jobs based on various criteria
     - Viewing job details
   - **Endpoints:**
     - `/jobs`
     - `/jobs/{jobId}`
     - `/jobs/search`

6. **Recruiter Controller:**
   - **Features:**
     - Recruiter registration and profile management
     - Posting and managing job listings
     - Viewing applications for posted jobs
   - **Endpoints:**
     - `/recruiter/profile`
     - `/recruiter/jobs`
     - `/recruiter/applications`

7. **Job Application Controller:**
   - **Features:**
     - Submitting job applications
     - Viewing and managing user applications
     - Tracking application status
   - **Endpoints:**
     - `/applications`
     - `/applications/{applicationId}`
     - `/applications/status`

8. **Freelancer Controller:**
   - **Features:**
     - Freelancer registration and profile management
     - Searching for freelance opportunities
     - Applying for freelance jobs
     - Managing freelance job applications
   - **Endpoints:**
     - `/freelancers/profile`
     - `/freelancers/jobs`
     - `/freelancers/applications`

**Project Goals:**
- **Create an intuitive and efficient platform for job seekers and recruiters:** The application is designed to be user-friendly and efficient, ensuring a smooth experience for both job seekers and recruiters.
- **Facilitate easy management of job applications and recruitment processes:** The platform simplifies the job application and recruitment processes, making it easier for users to manage their activities.
- **Provide a secure and scalable system for job listings and user data:** Built with **Spring Security**, the application ensures that user data and job listings are secure. The system is also scalable to handle increasing amounts of data and users.
- **Enhance user experience with features like job bookmarking and feedback:** Features such as job bookmarking and feedback enhance the overall user experience, making the platform more engaging and useful.

This Job Portal Application aims to streamline the job search and recruitment process, offering a robust and user-friendly platform for all involved parties.
