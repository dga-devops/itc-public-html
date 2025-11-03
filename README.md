# itc-public-html

DGA Project Management System - Public HTML Pages

## Pages

### 1. form-request-project.html
แบบฟอร์มลงทะเบียนโครงการใหม่ (Project Request Form)

A multi-step form for submitting new project requests with:
- Business information (project details, cost center, manager)
- Technical information (architecture, vendor, support model)
- Environment selection (Dev, Staging, Production)

### 2. approve-project-request.html
ระบบอนุมัติโครงการ (Project Approval System)

An approval dashboard for reviewing and managing project requests with:
- List view of all project requests
- Advanced filtering (status, support model, environment)
- Search functionality
- Detailed project view
- Approval/rejection workflow with comments
- Timeline and history tracking
- Statistics panel

## Usage

Open the HTML files directly in a web browser:

```bash
# For project request form
open form-request-project.html

# For approval system
open approve-project-request.html
```

Or serve them with a local web server:

```bash
python3 -m http.server 8080
# Then visit http://localhost:8080/form-request-project.html
# or http://localhost:8080/approve-project-request.html
```

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Bootstrap 5.3.3**: Modern UI components and styling
- **Thai Language**: Fully localized interface
- **No Backend Required**: Static HTML with JavaScript for interactivity
- **Sample Data**: Approval page includes demo data for testing

## Technologies

- HTML5
- CSS3 (Bootstrap 5.3.3)
- JavaScript (Vanilla)
- Bootstrap Icons 1.11.3