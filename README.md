README.md: Smart Recruitment and Vacancy Management System
1. Project Overview
The Smart Recruitment and Vacancy Management System is a proposed web-based platform for TalentBridge Recruitment Ltd. It aims to connect employers, recruiters, and job seekers while simplifying recruitment through centralized vacancy management, online applications, CV parsing, and intelligent job matching.
2. Problem Statement
The current recruitment process relies on emails and Excel spreadsheets, making it difficult to track applications, prevent missing or duplicate records, shortlist candidates quickly, and generate accurate reports.
3. Project Objectives
- Automate and centralize recruitment activities.
- Provide secure access for different user roles.
- Simplify vacancy posting and online applications.
- Match candidates to jobs based on their qualifications and skills.
- Improve interview scheduling and communication.
- Generate recruitment reports for management.
4. User Roles
1. Administrator: Manages users, system data, and matching settings.
2. Recruiter: Reviews vacancies, screens candidates, and schedules interviews.
3. Employer: Provides vacancy details and monitors recruitment activities.
4. Job Seeker: Creates a profile, uploads a CV, and applies for jobs.
5. Main System Modules
- Authentication and User Management: Registration, login, and role-based access.
- Vacancy Management: Create, approve, publish, update, and close vacancies.
- Candidate and CV Management: Maintain profiles and upload CVs in PDF or DOCX format.
- Application Management: Track applications from submission to hiring or rejection.
- Intelligent Job Matching: Rank candidates and explain matching results.
- Interview and Notifications: Schedule interviews and send email or SMS alerts.
- Dashboard and Reporting: Display recruitment statistics and export reports.
- Administration and Audit Trail: Manage system records and track important actions.
6. Proposed Technology Stack
- Frontend: React
- Backend: Node.js and Express.js
- Database: MongoDB
- Matching service: Python
- Version control: Git and GitHub
- Testing: Jest/Vitest and Supertest, as appropriate
7. Intelligent Job Matching
The system proposes scoring candidates out of 100 based on these factors:
Factor	Weight
Skills match	50%
Experience	20%
Education	15%
Location and availability	10%
CV and job-description text similarity	5%
The system will show matched and missing skills. Personal attributes such as name, gender, age, photo, and ethnicity will be excluded from scoring. Recruiters will make the final hiring decisions.
8. Database Collections
The proposed system includes nine MongoDB collections:
1. Users
2. Employers
3. Vacancies
4. Candidate Profiles
5. Applications
6. Match Results
7. Interviews
8. Notifications
9. Audit Logs
9. System Workflow
1. An employer or recruiter creates a vacancy.
2. A recruiter approves and publishes it.
3. A job seeker registers and uploads a CV.
4. The candidate applies for a suitable vacancy.
5. The system extracts CV information and calculates matching scores.
6. The recruiter reviews and shortlists candidates.
7. Interviews are scheduled and notifications sent.
8. Management accesses recruitment reports.
10. Testing and Evaluation
The project plan sets the following targets:
- At least 85% correct CV information extraction on a test set of 100 CVs.
- Rank the top 10 candidates from 1,000 candidates in under 5 seconds.
- At least 70% overlap with recruiters' manual shortlists across 30 vacancies.
- At least 70% automated test coverage of server-side code.
These are proposed targets, not confirmed results.
11. Security and Privacy
The system will aim to protect candidate information through role-based access, HTTPS, secure password hashing, controlled CV access, consent procedures, data retention rules, and audit logs. The project plan identifies the Kenya Data Protection Act, 2019, as a relevant compliance consideration.
12. Project Schedule
The planned duration is 16 weeks, from 11 January to 30 April 2027, using eight two-week Agile Scrum sprints.
Major activities include requirements analysis, system design, development, intelligent matching, testing, deployment, user training, and handover.
13. Project Budget
The estimated project budget is Ksh 2,084,500, including a 10% contingency. Estimated annual running costs are approximately Ksh 200,000.
14. Project Limitations
The proposed system does not include:
- Automatic hiring or rejection decisions.
- Video interviewing.
- Payroll and invoicing.
- Native mobile applications.
- Payment processing.
15. Author and Course
- Systems Analyst: Victorious Chepchirchir Korir
- Course: INSY281 — System Analysis & Design
- Institution: University of Eastern Africa, Baraton (UEAB)
- Project: Smart Recruitment and Vacancy Management System with Intelligent Job Matching
- Repository: Add the actual GitHub repository URL.
