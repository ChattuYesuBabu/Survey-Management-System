# Survey Management System

The **Survey Management System** is a web-based application developed using Java to facilitate the creation, management, and analysis of surveys. It provides two distinct roles: **Admin** and **User**, where admins can create and manage surveys, while users can participate by filling out and submitting the forms. The system efficiently stores and analyzes responses in real-time.

## Features

### Admin Features
- **Form Creation**: Create dynamic forms with multiple question types such as:
  - Multiple-choice (single selection)
  - Checkbox (multiple selections)
  - Text input and Textarea (open-ended responses) and so on...
- **Form Management**: View, edit, and delete forms via a dropdown list.
- **Response Analysis**: Analyze user responses through bar charts, pie charts, and other visual formats for structured data (radio-group and checkbox-group).
- **Role-Based Access**: Admins have full control over survey creation and analysis.

### User Features
- **Form Submission**: Users can log in, view available forms, and submit their responses.
- **Real-Time Response Storage**: User responses are stored in a secure Oracle database for admin analysis.
  
## Technologies Used
- **Java**: Backend logic for handling roles, forms, and response analysis.
- **JSP/Servlets**: Dynamic web pages for form creation, submission, and analysis.
- **Oracle Database**: Storage of form data and user responses.
- **HTML/CSS/JavaScript**: Frontend design and interactivity.
  
## Installation and Setup

### Prerequisites
- Java 8 or higher
- Oracle Database 21c (or equivalent)
- Apache Tomcat (for running JSP/Servlets)
