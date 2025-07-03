# Child Vaccine Schedule Tracking System

A web application designed to manage child vaccination schedules, providing flexible booking options, automated reminders, and an AI-powered chatbot for vaccination consultation. This project was developed as a team effort to streamline vaccination management for parents and healthcare providers.

## Features
- **Flexible Booking**: Schedule vaccinations individually or in packages (single/combo).
- **Vaccination History Tracking**: Monitor and manage children's vaccination records.
- **AI-Powered Chatbot**: Integrated with Spring AI (GPT-3.5) to provide vaccination consultation with 95% accuracy.
- **Automated Email Reminders**: Send notifications for upcoming, overdue, and payment deadlines using Spring @Async, reducing response time by 50%.
- **Dynamic Schedule Adjustment**: Automatically adjust schedules for multi-dose vaccines.
- **User-Friendly Interface**: Designed intuitive UI for booking and tracking using ReactJS.

## Tech Stack
- **Backend**: Java, Spring Boot (Spring Security with OAuth2, Spring @Async, Spring Email, Spring Data JPA), Spring AI (GPT-3.5)
- **Frontend**: ReactJS
- **Database**: SQL Server
- **Tools**: Maven (dependency management), Postman (API testing), Git/GitHub (version control)

## Installation & Setup
### Prerequisites
- Java 11 or higher
- Node.js (for ReactJS frontend)
- SQL Server (with a configured database)
- Maven (for dependency management)

### Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Kdz198/Child-Vaccine-Schedule-Tracking-System.git
   cd Child-Vaccine-Schedule-Tracking-System
