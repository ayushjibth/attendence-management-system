# AttendX - Modern Attendance Management System

## Overview

AttendX is a comprehensive attendance management system built with Spring Boot and modern web technologies. It provides an intuitive dashboard for tracking student attendance, managing student records, and generating analytics reports. The application features a sleek glassmorphism UI design with responsive layouts suitable for educational institutions.

## Features

- **Dashboard Overview**: Real-time attendance statistics and trends
- **Student Management**: Add, update, and manage student information
- **Attendance Tracking**: Mark and monitor daily attendance records
- **Analytics & Reports**: Generate insights on attendance patterns
- **Modern UI**: Glassmorphism design with smooth animations
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## Technology Stack

- **Backend**: Spring Boot 3.3.4
- **Database**: MySQL with Spring Data JPA
- **Frontend**: HTML5, CSS3, JavaScript
- **Build Tool**: Maven
- **Java Version**: 21
- **Additional Libraries**: Lombok, Spring Boot Actuator

## Getting Started

### Prerequisites

- Java 21 or higher
- Maven 3.6+
- MySQL 8.0+

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/attendx.git
   cd attendx
   ```

2. Configure the database in `src/main/resources/application.properties`

3. Build the application:
   ```bash
   mvn clean install
   ```

4. Run the application:
   ```bash
   mvn spring-boot:run
   ```

5. Open your browser and navigate to `http://localhost:8080`

## Usage

- Access the dashboard to view attendance statistics
- Navigate through different sections using the sidebar
- Use the "Mark Attendance" button to record attendance
- Search for students using the search functionality

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.