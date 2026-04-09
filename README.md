Contributors :
Mohammed Nawaz - PES2UG23CS347
N Veera Mahendra reddy - PES2UG23CS391
Naman Nagar        - PES2UG23CS361


#  Career Sphere – Job Portal System

A full-stack web application built using **Spring Boot, Thymeleaf, and MySQL** that connects **Students, Recruiters, and Admins** in a unified job portal.

---

##  Features

###  Student
- Register & Login
- Create and update profile (CGPA, skills, projects, certifications)
- View all available jobs
- Check job eligibility
- Apply for jobs
- Track application status (Pending / Approved / Rejected)

---

###  Recruiter
- Register & Login
- Post new job opportunities
- View all posted jobs
- View student applications
- Approve or Reject applications

---

###  Admin
- Register & Login
- View all users (Students, Recruiters)
- View all jobs and applications
- Monitor entire system
- Approve / Reject applications

---

##  Tech Stack

- **Backend:** Spring Boot (Java)
- **Frontend:** Thymeleaf + HTML + CSS
- **Database:** MySQL
- **ORM:** Spring Data JPA (Hibernate)
- **Build Tool:** Maven
- **IDE:** VS Code

---

## Project Architecture

This project follows:

###  MVC Pattern
- **Model:** User, Job, Application, AcademicProfile
- **View:** Thymeleaf HTML pages
- **Controller:** Handles requests & routing

---

###  GRASP Principles
- **Controller:** Handles system operations
- **Information Expert:** Services manage business logic
- **Low Coupling:** Layered architecture
- **High Cohesion:** Each class has a single responsibility

---

###  Design Patterns Used
- MVC Pattern
- Service Layer Pattern
- Repository Pattern

---

##  Database Structure

| Table | Purpose |
|------|--------|
| user | Stores all users (Student, Recruiter, Admin) |
| academic_profile | Stores student profile details |
| job | Stores job postings |
| application | Stores job applications |

---

##  System Workflow

```text
Recruiter → Post Job
        ↓
Student → View Jobs → Apply
        ↓
Recruiter/Admin → Approve/Reject
        ↓
Student → View Application Status
