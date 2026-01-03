# Job Marketplace Platform

A comprehensive Django-based job marketplace connecting job seekers with employers, featuring real-time chat, video interviews, and job application tracking.

## 🚀 Features

- **Dual User Roles:** Job Seekers and Employers
- **Job Management:** Post, search, and apply for jobs
- **Real-time Chat:** WebSocket-based messaging system
- **Video Interviews:** Schedule and conduct video calls
- **Application Tracking:** Track job applications with status updates
- **User Profiles:** Detailed profiles with skills, experience, and location
- **Saved Jobs:** Bookmark favorite job postings
- **Interview Scheduling:** Built-in scheduling system

---

## 📄 Pages Documentation

### 1. Landing Page
**Description:** The main entry point of the application. Showcases platform features, call-to-action buttons, and navigation to login/registration.

![Landing Page](Page%20Screenshot/landingpage.JPG)

**Key Features:**
- Platform overview
- "Find a Job" / "Post a Job" CTAs
- Navigation bar
- Hero section

**User Role:** Public (All)

---

### 2. Choose Role
**Description:** First step in registration where users select their role (Job Seeker or Employer).

![Choose Role](Page%20Screenshot/roles%20j-e.JPG)

**Key Features:**
- Role selection buttons
- Role descriptions
- Next button

**User Role:** Public (All)

---

### 3. Register as Job Seeker
**Description:** Registration form for job seekers with personal and professional information.

![Seeker Registration](Page%20Screenshot/jseeker%20registration.JPG)

**Key Features:**
- Full name input
- Email input
- Date of birth
- Location
- Password setup
- Profile completion

**User Role:** Public (All)

---

### 4. Register as Employer
**Description:** Registration form for employers with company details and business information.

![Employer Registration](Page%20Screenshot/employer%20registration%20page.JPG)

**Key Features:**
- Company name
- Business email
- Company details
- Location
- Password setup
- Account verification

**User Role:** Public (All)

---

### 5. Job Seeker Dashboard
**Description:** Main hub for job seekers showing overview, recent jobs, and quick access to features.

![Seeker Dashboard](Page%20Screenshot/jseeker%20dashboard.JPG)

**Key Features:**
- Profile summary
- Recent job recommendations
- Applied jobs count
- Saved jobs count
- Quick navigation links
- Messages preview

**User Role:** Job Seeker

---

### 6. Employer Dashboard
**Description:** Main hub for employers showing job postings, applications, and analytics.

![Employer Dashboard](Page%20Screenshot/e%20dashboard.JPG)

**Key Features:**
- Posted jobs overview
- Recent applications
- Profile summary
- Quick actions (Post Job, View Applications)
- Messages preview
- Analytics/statistics

**User Role:** Employer

---

### 7. Search Jobs / All Jobs Page
**Description:** Browse all available jobs with filtering and search capabilities.

![All Jobs](Page%20Screenshot/seeker%20search%20jobs.JPG)

**Key Features:**
- Job listings
- Search bar
- Category filters
- Location filters
- Salary range filters
- Sort options (newest, most relevant)
- Save job button
- Quick view option

**User Role:** Job Seeker

---

### 8. All Jobs Listing
**Description:** Comprehensive job listing page showing all available positions.

![All Jobs Page](Page%20Screenshot/all%20jobs%20page.JPG)

**Key Features:**
- Job listings
- Search bar
- Category filters
- Location filters
- Sort options
- Save job button
- Quick view option

**User Role:** Job Seeker

---

### 9. Apply for Job
**Description:** Application form for job seekers to submit their interest and resume.

![Apply Job](Page%20Screenshot/apply%20for%20job.JPG)

**Key Features:**
- Resume upload/selection
- Cover letter textarea
- Skills highlighting
- Experience summary
- Submit application button
- Preview before submit

**User Role:** Job Seeker

---

### 10. Saved Jobs
**Description:** List of jobs bookmarked by the seeker for later review.

![Saved Jobs](Page%20Screenshot/saved%20jobs.JPG)

**Key Features:**
- Saved job listings
- Remove from saved
- Job preview
- Apply directly button
- Sort/filter options

**User Role:** Job Seeker

---

### 11. Job Seeker Profile
**Description:** User profile page for job seekers to view and update personal information.

![Seeker Profile](Page%20Screenshot/jseeker%20profile.JPG)

**Key Features:**
- Profile picture
- Personal information
- Skills section
- Experience timeline
- Education details
- Location and contact
- Edit profile button
- Resume management

**User Role:** Job Seeker

---

### 12. Post a Job (Employer)
**Description:** Form for employers to create and publish new job postings.

![Post Job](Page%20Screenshot/e%20post%20a%20job.JPG)

**Key Features:**
- Job title input
- Description editor
- Requirements section
- Salary range
- Job category selection
- Location
- Experience level
- Job type (Full-time, Part-time, etc.)
- Preview before publish
- Save as draft option

**User Role:** Employer

---

### 13. Edit Job Post
**Description:** Form to modify existing job postings.

![Edit Job](Page%20Screenshot/edit%20job%20post.JPG)

**Key Features:**
- All posting fields editable
- Delete job option
- Pause/Resume job posting
- View applications count
- Last edited timestamp

**User Role:** Employer

---

### 14. Apply for Job Detail
**Description:** Detailed view of application details and application checking.

![Applicant Application Check](Page%20Screenshot/applicant%20application%20check.JPG)

**Key Features:**
- Applicant information
- Application status
- Resume view
- Cover letter display
- Action buttons
- Interview scheduling option

**User Role:** Employer

---

### 15. Employer Job Posting
**Description:** Employer's view of their job postings and management interface.

![Employer Jobs](Page%20Screenshot/admin%20side%20jobs.JPG)

**Key Features:**
- Posted jobs list
- Edit job button
- Delete job button
- View applications count
- Job status
- Publication date

**User Role:** Employer

---

### 16. View Job Applicants
**Description:** List of applicants for a specific job posting with their details.

![Job Applicants Admin](Page%20Screenshot/job%20applicants%20at%20admin%20side.JPG)

**Key Features:**
- Applicant list
- Application status (Pending, Accepted, Rejected)
- Applicant profile preview
- Resume view
- Action buttons (Accept, Reject, Message)
- Filter by status
- Sort options

**User Role:** Employer

---

### 17. Admin Page
**Description:** Administrative dashboard and control panel for system management.

![Admin Page](Page%20Screenshot/admin%20page.JPG)

**Key Features:**
- System overview
- User management
- Content management
- Analytics and reports
- System settings
- Moderation tools

**User Role:** Admin

---

## 📁 Folder Structure

```
mysite/
├── README.md (this file)
├── Page Screenshot/
│   ├── 01_landing.png
│   ├── 02_login.png
│   ├── 03_choose_role.png
│   └── ... (other page screenshots)
├── jobs/
│   ├── templates/
│   ├── static/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── ...
├── mysite/
│   ├── settings.py
│   ├── urls.py
│   └── ...
└── manage.py
```

---

## 🛠️ Technology Stack

- **Backend:** Django
- **Real-time Communication:** Django Channels (WebSockets)
- **Database:** SQLite (Development)
- **Frontend:** HTML, CSS, JavaScript
- **Authentication:** Django User Model
- **Video:** WebRTC

---

## 📸 Screenshot Naming Convention

When adding screenshots, use the following naming format:

`NN_page_name.png`

- **NN:** Sequential number (01, 02, 03, etc.)
- **page_name:** Descriptive page identifier in lowercase with underscores

**Examples:**
- `01_landing.png`
- `06_seeker_dashboard.png`
- `19_video_call.png`

---

## 📝 Notes

- Add screenshot files to the `Page Screenshot` folder
- Update screenshot paths in this README if you reorganize files
- Keep descriptions concise and user-focused
- Update this README when new pages are added

---

**Last Updated:** January 3, 2026
