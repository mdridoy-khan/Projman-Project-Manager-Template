# 🚀 Projman - Modern Project Management System Dashboard Template

<p align="center">
  <img src="assets/img/logo-icon.svg" alt="Projman Logo" width="100" height="100">
</p>

<p align="center">
  <b>A modern, responsive, and feature-rich HTML5 & Bootstrap 5 Admin Template designed for Project Management, Team Collaboration, and Task Tracking.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white" alt="Sass">
  <img src="https://img.shields.io/badge/Bootstrap-5.x-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap 5">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</p>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Tech Stack & Third-Party Libraries](#-tech-stack--third-party-libraries)
- [Template Pages & Modules](#-template-pages--modules)
- [Folder Structure](#-folder-structure)
- [Getting Started](#-getting-started)
- [Customization & SCSS Workflow](#-customization--scss-workflow)
- [Browser Compatibility](#-browser-compatibility)
- [Author & Credits](#-author--credits)
- [License](#-license)

---

## 🌟 Overview

**Projman** is a comprehensive, production-ready frontend HTML UI template tailored specifically for building modern SaaS Project Management platforms, Agile/Scrum workspaces, ERP dashboards, and team collaboration applications.

Engineered with clean semantic **HTML5**, modular **SCSS (7-1 architecture)**, and **Bootstrap 5**, it provides an intuitive user experience with pre-built interactive components like drag-and-drop Kanban boards, Gantt charts, timelines, calendars, and live chat interfaces.

---

## ✨ Key Features

- 📊 **Interactive Analytics Dashboard**: Visual KPI widgets, task progression bars, and responsive charts powered by Chart.js.
- 🗂️ **Multiple Project & Task Views**:
  - **Kanban Board**: Drag-and-drop task workflow management with SortableJS.
  - **Gantt Chart & Timeline**: Project scheduling and milestone visualization.
  - **Task Calendar**: Month and week schedule view for deadlines and team meetings.
  - **DataTables View**: Searchable, sortable, and paginated task and project lists.
  - **Grid & List Views**: Flexible views for projects and digital assets/resources.
- 💬 **Integrated Team Chat UI**: Direct messaging, group channels, active status indicators, and file attachments interface.
- 👥 **Team & Member Profiles**: Member directories, role badges, contribution tracking, and member profile detail views.
- 🔐 **Authentication & Onboarding**: Complete login, registration, multi-step onboarding wizard (jQuery Steps), and splash/loader screens.
- 📁 **Resource / Asset Manager**: Grid, list, and empty state layouts for managing project files, media, and documents.
- 📱 **Fully Responsive Layout**: Optimized for mobile devices, tablets, laptops, and ultra-wide desktops.
- 🎨 **Modular SCSS Architecture**: Easily customizable design tokens, colors, typography, and spacing variables.

---

## 🛠️ Tech Stack & Third-Party Libraries

| Technology / Library | Purpose |
| :--- | :--- |
| **HTML5 & CSS3** | Semantic markup and modern UI styling |
| **Bootstrap 5** | Responsive layout grid, modals, dropdowns, and utility classes |
| **SASS / SCSS** | Modular stylesheet pre-processing (`assets/sass/`) |
| **jQuery (v3.6.0)** | DOM manipulation, UI interactions, and event handling |
| **SortableJS** | Drag-and-drop interaction for the Kanban task board |
| **Chart.js** | Dynamic data visualizations and dashboard analytics |
| **DataTables** | Advanced sortable, filterable, and paginated data tables |
| **Select2 & Nice Select** | Searchable and styled custom select dropdowns |
| **jQuery Steps** | Multi-step form wizards for project setup and onboarding |
| **FontAwesome 5 Pro** | Comprehensive vector iconography throughout the system |

---

## 📄 Template Pages & Modules

### 1. 📊 Dashboard & Analytics
- `dashboard.html` – Primary dashboard with project metrics, charts, task summaries, and notification tray.

### 2. 📁 Projects & Task Management
- `projects.html` – Projects grid view with progress indicators.
- `projects-table.html` – Tabular view with advanced filtering options.
- `add-project.html` – Multi-step project creation wizard.
- `project-created.html` – Project creation confirmation & success screen.
- `project-kanban.html` – Drag-and-drop Agile/Kanban task board.
- `project-tasklist.html` – Standard checklist-style task view.
- `project-tasktable.html` – Detailed task table with status tags.
- `project-taskcalendar.html` – Project-specific calendar schedule.
- `project-taskgantt.html` – Project roadmap and Gantt scheduling.
- `project-timeline.html` – Historical project activity timeline.

### 3. 💬 Communication & Schedule
- `chats.html` – Team chat and real-time messaging UI.
- `calendar.html` – Full-featured interactive event calendar.

### 4. 👥 Team Management
- `team-members.html` – Team member cards with roles and contact actions.
- `team-members-list.html` – Team member directory list view.
- `team-member-details.html` – Individual member performance and profile page.

### 5. 📂 Resource & Asset Repository
- `resource-grid.html` – Grid view for shared files and documentation.
- `resource-list.html` – List view for file downloads and version info.
- `resource-blank.html` – Clean empty-state view for zero-data states.

### 6. 🔐 Auth & Onboarding Flow
- `index.html` / `login.html` – Sign in screen.
- `signup.html` / `register.html` – User account registration.
- `onboard-screen.html` – User workspace setup & onboarding wizard.
- `welcome-screen.html` & `loader-screen.html` – Splash/loading screens.

---

## 📂 Folder Structure

```plaintext
projman/
├── assets/
│   ├── css/                  # Compiled CSS files & third-party vendor stylesheets
│   │   ├── bootstrap.min.css
│   │   ├── datatables.min.css
│   │   ├── fontAwesome5Pro.css
│   │   ├── nice-select.css
│   │   ├── select2.min.css
│   │   └── style.css
│   ├── font/                 # Custom typography & web fonts
│   ├── img/                  # Logos, icons, banners, and sample avatar images
│   ├── js/                   # Scripts and vendor plugins
│   │   ├── canban.js         # Kanban drag-and-drop initialization
│   │   ├── chart.min.js      # Chart rendering
│   │   ├── datatables.min.js # DataTables integration
│   │   ├── script.js         # Core application JavaScript
│   │   └── Sortable.min.js   # Drag-and-drop library
│   └── sass/                 # Modular SCSS source files
│       ├── animations/
│       ├── base/
│       ├── components/
│       ├── layouts/
│       ├── mixins/
│       ├── pages/
│       ├── variables-site/
│       └── style.scss
├── *.html                    # All HTML page templates
└── README.md                 # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
You only need a modern web browser (Google Chrome, Firefox, Edge, Safari). No backend installation is required to preview the templates.

### Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/projman.git
   cd projman
   ```

2. **Open in Browser:**
   - Simply double-click `dashboard.html` or `index.html` to open it in your browser.
   - **Recommended:** If using VS Code, right-click `dashboard.html` and select **"Open with Live Server"**.

---

## 🎨 Customization & SCSS Workflow

The styling is structured with SASS in `assets/sass/` for effortless customization:

1. **Change Colors & Theme Variables:**
   Modify the color palette, fonts, and border radii in `assets/sass/variables-site/`.
2. **Compile SCSS to CSS:**
   Using Sass CLI or Live Sass Compiler in VS Code:
   ```bash
   sass --watch assets/sass/style.scss:assets/css/style.css
   ```

---

## 🌐 Browser Compatibility

- ✅ Google Chrome (Latest)
- ✅ Mozilla Firefox (Latest)
- ✅ Microsoft Edge (Latest)
- ✅ Apple Safari (Latest)
- ✅ Opera (Latest)

---

## 👨‍💻 Authors & Credits

- Developed by **IT Transmit Ltd.**
- Built with standard open-source libraries (Bootstrap 5, jQuery, SortableJS, Chart.js, Select2).

---

## 📜 License

This project is licensed under the [MIT License](LICENSE) - feel free to customize and integrate it into your own applications!
