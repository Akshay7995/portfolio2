# Portfolio2

**Portfolio2** is a  one-page portfolio website built using **Django**. This project is designed to showcase a personal profile, with sections for a brief introduction, social media links, and a well-organized layout. The website leverages Django's templating engine and Bootstrap for responsive and visually appealing design.

## Project Setup

### Django Installation and Project Initialization
- Installed Django using pip:  
  `pip install Django`
- Created a new Django project and app.
- Configured project settings and set up the development server.

### Templates and Views Configuration
- Created a Django app named **base** to handle templates and static files.
- Set up URL routing to render custom templates.
- Developed HTML templates for different sections of the site, using **Bootstrap** for responsive styling.

### Static Files Management
- Initialized a **staticfiles** directory for organizing **CSS** and **image assets**.
- Configured **Django settings** to serve static files effectively.
- Included **Bootstrap** via CDN to enhance the website's design and responsiveness.

### Design and Styling
- Structured the website layout using **Bootstrap’s grid system** for a responsive, mobile-friendly design.
- Custom-styled the **profile image** and text to give a personalized touch to the site.
- Addressed layout inconsistencies and implemented universal styling rules across all sections.

### Finalizing the Website
- Fixed any layout discrepancies to ensure all components were aligned and visually consistent.
- Applied **Bootstrap** styles for a uniform visual theme across the website.
- Reviewed the final layout to identify potential improvements and polished the overall design.

## How to Run the Project
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/portfolio2.git

2. Activate the project
   ```bash
   venv\Scripts\activate
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
4. Run the Django development server:
   ```bash
    python manage.py runserver
  The site will be accessible at http://127.0.0.1:8000/ in your browser.
