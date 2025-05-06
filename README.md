# GitCollab

## Project Description

The Gitcollab is a web application designed to connect developers, foster collaboration, and streamline open-source project management. Integrated with GitHub, it allows users to share and contribute to projects while matching their skills with relevant opportunities.

Key features include:
- Skill-based project matching
- Contributor request handling
- GitHub OAuth login
- Project listing and discovery
- Custom user profiles

Built with Django, Bulma CSS, and JavaScript, and deployed via Render, it offers a scalable, modern, and developer-friendly experience.

---

## How to List Your Project

1. Log In using your GitHub account.
2. Click “Create Project” on the homepage/dashboard.
3. Fill out the form:
   - GitHub repository URL (must match your username)
   - Requirements description
   - Number of contributors needed
   - Desired skills
   - Optional: Buy Me a Coffee, Patreon, or PayPal support
4. Submit the project.
5. Your project appears in the global list after validation.

---

## How Collaborators Join Projects

1. Browse the homepage for interesting projects.
2. Click on a project to view details.
3. Submit a contributor request (visible if allowed).
4. The project owner reviews and accepts/rejects your request.
5. Once accepted, you begin collaboration.

---

## How Everyone Can View Projects

- Visit the home page (/) to see all public projects.
- Projects include descriptions, skills needed, and contributor slots.
- Cached GitHub data (README, forks) enhances performance.
- Search & filter (planned) to help users find matching projects easily.

---

## How to Get Your Matching Projects

1. Log in and update your skills in your profile.
2. A “Matched Projects” section appears on the home page.
3. Uses a skill-matching algorithm.
4. Matching results are cached for 1 hour for better speed.

---

## Automating Collaborator Requests

- Requests are auto-stored as “pending”.
- Project owners receive a notification.
- Owner manually accepts or rejects requests.
- Future: auto-accept based on skill/reputation using Celery tasks/signals.

---

## Add Your GitHub Classic Token

1. Log in and go to Edit Profile.
2. Paste your GitHub Classic Token (40 characters).
3. Token is masked for security.
4. Used for enhanced API access (e.g., forks, issues).

---

## How to Clone This Repository

```bash
# Clone the repo
git clone https://github.com/abhirajadhikary06/GitCollab.git

# Navigate into the repo
cd GitCollab

# Create a virtual environment
python -m venv venv

# Activate it
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Configure environment variables (if needed)

# Run migrations
python manage.py migrate

# Start the server
python manage.py runserver

```
---

## Live Link

https://yourprojectname.onrender.com


---

## Tech Stack

Django: Backend framework for APIs and database interaction

Bulma CSS: Modern responsive CSS framework

JavaScript: Frontend interactivity

GitHub OAuth: Secure login and repository integration

Render: Hosting and deployment



---

## Contribution

Contributions are welcome! Clone the repo, explore the features, and help build the future of open-source collaboration.

