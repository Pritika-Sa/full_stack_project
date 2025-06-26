AptiTrack – Aptitude Tracker & Progress Dashboard

AptiTrack is a full-stack aptitude preparation and tracking platform that helps users monitor their performance across various topics, attempt smart quizzes, and visualize progress over time. Designed for students and job seekers aiming to improve aptitude skills with measurable insights.

## Features

-  **User Authentication** (JWT-based login and secure routes)
-  **Topic-Wise Practice** – Curated questions with topic filters
-  **Timed Quizzes** – Interactive multi-question quizzes with navigation
-  **Visual Analytics**:
  - Topic-wise scores (Bar Chart)
  - Accuracy Summary (Pie Chart)
  - Daily Quiz Attempts (Area Chart)
-  **Date & Topic Filters** – Drill down your stats
-  **PDF Export** – Download charts and insights for personal tracking
-  **Average Time Analysis** – Time taken per quiz shown with breakdown
-  **User-specific Data** – Each user sees their own data only


## Tech Stack

### Frontend
- React.js
- Recharts (for data visualizations)
- Bootstrap + Custom CSS (for styling and responsive UI)
- html2pdf.js (for PDF export)

### Backend
- Node.js + Express.js
- MongoDB Atlas
- JWT for secure auth
- CORS, bcryptjs, dotenv
