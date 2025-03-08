# Centralized Resource Hub 

![Conceptual Image](https://github.com/VariableX-Community/Centralised-Resource/blob/main/Reource%20Hub.jpeg)

Centralized Resource Hub is a platform designed to allow students, faculty, and community members to share, organize, and access academic resources efficiently. The project is built with Django and Next.js, with a focus on user authentication, resource management, notifications, and a chat feature for collaboration.

This platform aims to serve as a one-stop destination for educational resources, including notes, assignments, cheat sheets, and other materials. Users can easily upload, download, rate, and comment on resources while staying updated on important events such as hackathons and college notifications.

# Features
## 1. User Authentication & Roles
Description: Users can register and log in with different roles (student, faculty, admin).
Tech Stack: Django Authentication, JWT for frontend authentication
## 2. Chat Functionality
Description: A real-time chat system for users to communicate, share resources, and discuss academic topics.
Tech Stack: Django Channels, WebSockets, React (Next.js)
## 3. Upload & Organize Resources
Description: Users can upload academic resources such as notes, papers, assignments, and organize them with metadata (tags, categories).
Tech Stack: Django File Storage, django-storages (for cloud storage), Next.js
## 4. Search & Filter
Description: A powerful search feature allows users to search for resources by title, tags, or categories. Filters allow sorting by relevance or date.
Tech Stack: Django ORM, Next.js dynamic search
## 5. Categories & Tags
Description: Resources can be categorized into subjects (Mathematics, Physics, etc.) and tagged for better organization.
Tech Stack: Django models (Many-to-Many relationships), Next.js frontend for filtering
## 6. User Dashboard
Description: A personalized dashboard where users can view and manage their uploaded resources, track downloads, and update their profile.
Tech Stack: Next.js, React
## 7. Admin Panel
Description: Admins can manage users, resources, and moderate content. The admin panel is built using Django’s default admin interface.
Tech Stack: Django Admin, Next.js (optional for custom views)
## 8. Blog for Notifications and Updates
Description: A blog feature allows admins to post important updates like hackathons, deadlines, and college events.
Tech Stack: Next.js, Markdown (or a CMS like Contentful for easy blogging)
## 9. Resource Downloading
Description: Users can download resources (PDF, Word, etc.) directly from the platform.
Tech Stack: Django File Storage, Next.js for frontend download links
## 10. Responsive UI
Description: The application is fully responsive, ensuring that users have a seamless experience on both mobile and desktop devices.
Tech Stack: TailwindCSS, Next.js for a responsive frontend
## 11. Event Calendar
Description: A calendar feature to display upcoming college events like hackathons, exam dates, and deadlines.
Tech Stack: React Calendar, Django API

# Tech Stack

## Frontend:

### Next.js – For building fast, scalable, and SEO-friendly web applications.
### React – For building reusable UI components.
### TailwindCSS – For utility-first CSS styling.
### Axios – For API requests.

##Backend:

### Django – High-level Python framework for building secure and scalable web applications.
### Django Rest Framework – For building RESTful APIs that connect the frontend and backend.
### Django Channels – For implementing real-time features like chat and notifications.
### Django Authentication – For handling user login and roles.
### Django ORM – For managing the database.

##Database:

### PostgreSQL – Powerful open-source relational database.
### SQLite (optional for development) – Lightweight database for development.

# Setup Instructions

## 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/VariableX-Community/Centralised-Resource.git
cd Centralised-Resource
```

## 2. Install Dependencies
Backend (Django)
Navigate to the backend folder:

```bash
cd backend
Install the necessary Python dependencies using pip:
```
```bash
pip install -r requirements.txt
```

Apply migrations:

```bash
python manage.py migrate
```
Create a superuser to access the Django admin panel:

```bash
python manage.py createsuperuser
```
Frontend (Next.js)
Navigate to the frontend folder:

```bash
cd ../frontend
```
Install the necessary Node.js dependencies:

```bash
npm install
```
Running the Development Server
Backend (Django)
Start the Django development server:
```bash
python manage.py runserver
```
Frontend (Next.js)
Start the Next.js development server:
```bash
npm run dev
```
Now the application should be running locally, and you can view it by navigating to http://localhost:3000.
