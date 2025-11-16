WasteZero – Full Stack Waste Management System

A full-stack web application designed to streamline waste pickup scheduling, volunteer coordination, opportunity management, and user communication. The platform includes role-based access (Admin & Volunteer), real-time messaging, analytics dashboards, and a modern responsive UI with theme toggling.

1. Setup Steps
    Clone or Download
    git clone <your-repo-url>
    cd project-folder

Or download the ZIP and extract it.

Backend Setup
    cd backend
    npm install
    npm start

    Runs on http://localhost:5000
    (or your configured port)

Requires MongoDB connection URL in .env

Frontend Setup
    cd frontend
    npm install
    ng serve

    Runs on http://localhost:4200

    Update API base URL inside environment.ts if needed

2. Tech Stack Used
   
Frontend

    Angular

    TypeScript

    Tailwind CSS / Custom styles

    Chart.js (for analytics visualizations)

Backend

    Node.js

    Express.js

    MongoDB + Mongoose

    JWT authentication

Database

    MongoDB (Cloud or Local)

3. Application Workflow
   Login Credentials for Testing

Admin

    Email: gayu@gmail.com

    Password: test@123

Volunteers

    shiv@gmail.com
    — test@123

    krithi@gmail.com
    — test@123

(Use Admin in normal browser and Volunteer in Incognito for real-time testing.)

Dashboard

    Displays analytics related to the waste management workflow

    Admin: Sees upcoming pickups awaiting volunteer acceptance

    Volunteer: Sees their assigned upcoming pickups

Schedule Pickup

    Admin schedules pickups and assigns a volunteer

    Data is stored in:

    Admin → Pickup History

    Volunteer → Assigned Pickups

    Volunteers can track all assigned pickups across dates

Opportunities

    Admin: Create, edit, delete, and manage public opportunities

    Volunteers: View and apply via email or messaging

Messages

    Search users and communicate instantly

    Volunteers can message Admin regarding opportunities

My Profile

    Update name, contact info, skills

    Change password

Help & Support

    Shows organization details for user queries

Theme Toggle

    Light/Dark mode for accessibility

Admin Panel

    Admin-only access

    View overall analytics, logs, and download reports

4. Screenshots / Recording

    Add screenshots inside a /screenshots folder:

    /screenshots/dashboard.png
    /screenshots/schedule-pickup.png
    /screenshots/opportunities.png
    /screenshots/messages.png
    /screenshots/profile.png
    /screenshots/admin-panel.png

Demo Screenshots: <https://drive.google.com/drive/folders/1LAioYJeijd4fKPuTbTyQtPaopERVoYFX?usp=sharing>

5. Assumptions

    Admin manages scheduling, volunteer assignment, and opportunity creation

    Volunteer roles are fixed; no dynamic role creation

    Messaging system is meant for direct text communication

    Pickup acceptance is handled through assigned volunteer workflow

6. Bonus Features Implemented

    Dark/Light Theme Toggle

    JWT-Based Login & Role Authentication

    Role-Based Authorization (Admin & Volunteer)

    Analytics Dashboard with Charts

    Real-Time Styled Messaging System

    Tailwind CSS Responsive UI

    Clean & Modular Service-Based Architecture
