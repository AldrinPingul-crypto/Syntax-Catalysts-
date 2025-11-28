# Smart Barangay Governance System

## About the Project

The Smart Barangay Governance System is a web-based platform developed for local Philippine barangays to streamline administrative services, enhance community communication, and improve governance efficiency. Built using Laravel, it addresses common challenges in manual barangay operations, such as document processing delays, limited feedback handling, and low resident engagement.

This system automates key tasks to promote transparency, accountability, and citizen participation, aligning with e-governance goals and Sustainable Development Goal 17 (Partnerships for the Goals). It supports barangay officials in managing requests, complaints, and announcements while providing residents with a user-friendly interface for accessing services.

Key benefits include:
- Reduced manual paperwork and processing time.
- Real-time updates and secure data handling.
- Data-driven insights through sentiment analysis and record filtering.
- Alignment with ISO 25010 quality characteristics for functionality, security, and usability.

The system was developed by Syntax Catalysts, IT students from Jose Rizal University, as part of a capstone project.

## Features

- **Online Document Request Module**  
  Residents can submit requests for barangay clearances, certificates, and permits online, with status tracking and secure payment integration (e.g., GCash QR codes shown only after admin approval).

- **Complaint and Feedback Management**  
  Residents can file complaints and provide feedback through a dedicated module. The system now evaluates resident comments for sentiment (positive, negative, or neutral) based solely on comment content. The star rating feature was removed to ensure that sentiment analysis is accurately performed using actual feedback.

- **Community Announcement Board**  
  Barangay officials can post real-time updates, announcements, advisories, and events, allowing residents to stay informed about barangay activities and important notices.

- **Administrative Dashboard**  
  A centralized dashboard enables barangay officials to monitor document requests, complaints, payments, and user accounts. Filters are available for all record lists (requests, complaints, collections), enabling administrators and staff to effectively search and manage entries.

- **Enhanced User Verification**  
  Account registration requires proof of residency (e.g., Barangay ID or utility bill with address). Senior Citizens and PWDs must upload valid supporting documents. When a user selects "Voter," the submission of a voter ID or certificate is mandatory during the registration process.

- **Payment and Record Management**  
  Online payments via GCash QR codes are allowed only after administrative approval of requests to ensure proper workflow and security. Approved transactions and collections are logged for transparency and auditing.

- **Machine Learning Integration (Sentiment Analysis)**  
  The system uses natural language processing to classify resident feedback into positive, negative, or neutral sentiment, helping barangay officials understand citizen satisfaction and prioritize improvements.

## Technology Stack

- **Framework**: Laravel (PHP)
- **Language**: PHP, Blade templates, JavaScript
- **Database**: MySQL
- **Frontend**: Blade, Bootstrap (or similar CSS framework)
- **Authentication**: Laravel authentication with role-based access (e.g., admin, staff, resident)
- **Tools & Integrations**:
  - GCash QR for digital payments
  - NLP-based sentiment analysis for resident comments
- **Architecture**: MVC pattern with Eloquent ORM and database migrations

## Installation and Setup

### Prerequisites

- PHP >= 8.1  
- Composer  
- MySQL or compatible database  
- Node.js and NPM (for frontend assets)  
- Git (optional but recommended)

### Steps

1. Clone the repository:
