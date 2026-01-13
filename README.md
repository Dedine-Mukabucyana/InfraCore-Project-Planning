
# MoMo SMS Transaction Analyzer
Team:InfraCore

Team Members:
- Mukamukiza Milliam- Github: mmukamukiza21
-  Umutoni Nada - Github: Umutoni123-aa
-  ukabucyana Dedine - Github:Dedine-Mukabucyana

Project Overview

This project is an enterprise-level fullstack application designed to process Mobile Money (MoMo) SMS data provided in XML format. The system extracts raw SMS data, cleans and normalizes it, categorizes transactions, stores the results in a relational database (SQLite), and presents insights through a frontend dashboard.

The application is built using a modular ETL (Extract, Transform, Load) pipeline and follows Agile and collaborative development practices. It enables users to analyze transaction such as incoming funds, outgoing payments, fees, and balances.

This project demonstrates skills in:

- Backend data processing (Python)
- Database design and management (SQLite)
- Frontend development (HTML, CSS, JavaScript)
- System architecture design
- Agile teamwork and GitHub collaboration

Objectives:

- Clean and normalize transaction data (amounts, dates, phone numbers)
- Categorize transactions using rule-based logic
- Store structured data in a relational database
- Generate processed JSON outputs for frontend use
- Build a simple dashboard to visualize analytics
- Practice collaborative development using GitHub and Scrum

High-Level System Architecture

The system follows a layered architecture:

- Input Layer – Raw MoMo XML SMS data
- ETL Layer – Parsing, cleaning, categorization, and loading
- Storage Layer – SQLite relational database
- API Layer (Optional Bonus) – FastAPI endpoints for data access
- Frontend Layer – Static dashboard for analytics and visualization

 Architecture Diagram:https:https://app.diagrams.net/#G1xHlqE2nJ76NpQQUFHjheOVsuLMVtMwWJ#%7B%22pageId%22%3A%22-d79H1NVxJkwPVFQFf-x%22%7D

Dashboard Features:
- Total transactions summary
- Incoming vs outgoing money
- Transaction categories (payments, transfers, fees)
- Time-based trends
- Clean and readable tables and charts

*Scrum Board Link
- Scrum Board: https://github.com/users/Dedine-Mukabucyana/projects/1/views/1

Board Columns:

To Do – Planned tasks
In Progress – Active work
Done – Completed tasks

Initial tasks include:

.Repository setup
.Architecture design
.XML research
.ETL module development
.Frontend dashboard setup

Future Improvements:
.Full REST API with authentication
.Advanced analytics and filters
.Interactive charts
.Deployment to cloud platform
.Support for multiple XML files

Contact

For questions or collaboration, contact any team member via GitHub or through our emails
- m.mukamukiz@alustudent.com
- U.nada@alustudent.com
- d.mukabucya@alustudent.com
