# Smart Barangay Governance System

A web-based barangay management platform designed for Barangay Pitogo to streamline document processing, complaint handling, business permit management, online services, and citizen feedback. The system supports local governance by digitizing manual processes, integrating basic machine learning features, and improving communication between residents and barangay officials. [attached_file:68]

## System Overview

The Smart Barangay Governance System (Barangay Pitogo Smart Management System) provides a centralized online portal where residents can request documents, file complaints, view announcements, and receive updates, while barangay officials manage requests, permits, and feedback through an admin dashboard. [attached_file:68]

The system aims to:
- Reduce long queues and manual paperwork at the barangay hall.
- Provide real-time, transparent updates on requests and complaints.
- Enhance community engagement through timely announcements and feedback channels. [attached_file:68]

## System Components

### 👥 Resident Portal

A web interface where residents can:
- Register and log in with verified accounts.
- Request clearances, permits, and certifications.
- Submit complaints and feedback.
- View community announcements and the status of their requests. [attached_file:68]

### 🏛️ Admin & Staff Portal

A management interface for barangay officials and staff to:
- Approve or reject document and permit requests.
- Manage complaints and feedback records.
- Post announcements and advisories.
- Monitor system activity and generate basic reports. [attached_file:68]

### 📊 Machine Learning & Analytics

- Text classification to categorize complaint/blotter entries based on content (e.g., theft, conflict, injury). [attached_file:68]
- Time series forecasting for business permit applications to anticipate peak periods. [attached_file:68]
- Sentiment analysis of citizen feedback (positive, negative, neutral) to understand satisfaction and priority issues. [attached_file:68]

## Key Features

### 📝 Online Document & Permit Requests

- Residents can apply online for:
  - Barangay clearances
  - Permits
  - Certifications
- Requests are stored in the system and visible to barangay staff via the admin dashboard.
- Residents can track request status (e.g., pending, processing, approved). [attached_file:68]

### 📣 Complaint & Feedback Module

- Residents submit complaints and feedback using structured online forms.
- System records details and allows officials to update status (pending, under review, resolved).
- Text classification is used to group complaints by category and support faster resolution.
- Feedback is analyzed using sentiment analysis to identify common concerns and service satisfaction. [attached_file:68]

### 📌 Community Announcement Board

- Barangay officials can post:
  - Announcements
  - Advisories
  - Events
  - Emergency information
- Residents see announcements in their dashboard, improving awareness and participation. [attached_file:68]

### 👤 User Registration & Verification

- Residents register with:
  - Personal information and complete address
  - Proof of residency (e.g., barangay ID or utility bill)
- Senior Citizen / PWD users upload supporting documents.
- Voter status requires voter ID or certificate during registration.
- Role-based access control for Residents, Staff, and Admins. [attached_file:68]

### 🧾 Record Management & Filtering

- Admin dashboard to:
  - View and filter document requests
  - Manage complaints and feedback records
  - Monitor business permit applications
- Filters support efficient searching and organization of records. [attached_file:68]

### 🔐 Quality & Evaluation (ISO 25010:2023)

The system was evaluated using ISO 25010:2023 on:
- Functional Suitability
- Performance Efficiency
- Compatibility
- Interaction Capability (Usability)
- Reliability
- Security
- Maintainability
- Flexibility
- Safety [attached_file:68]

Beta testing results showed “Strongly Agree” ratings for functional suitability, performance efficiency, compatibility, and usability. [attached_file:68]

## Tech Stack

### Frontend

- **HTML5**, **CSS3**, **JavaScript**
- **React.js** for dynamic, component-based UI
- **Bootstrap** (or similar) for responsive and mobile-friendly design [attached_file:68]

### Backend

- **PHP** for server-side logic and handling requests
- **Node.js** (optional) for asynchronous tasks such as notifications and real-time updates
- **RESTful APIs** for communication between frontend and backend modules [attached_file:68]

### Database

- **MySQL** as the relational database to store:
  - Users and roles
  - Document and permit requests
  - Complaints and feedback
  - Announcements and logs [attached_file:68]

### Hosting & DevOps

- Deployed on platforms such as **AWS** or **Heroku**
- **Docker** for containerization and easier deployment
- **CI/CD tools** (e.g., GitLab CI, Travis CI) for continuous integration and deployment [attached_file:68]

### Data Analysis Tools

- **Microsoft Excel** and **Google Sheets** for survey data encoding and visualization
- **SPSS** for statistical analysis and reliability testing during system evaluation [attached_file:68]

## Project Structure (High-Level)
