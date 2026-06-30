PROJECT NAME:

1. Purpose
   What problem does this website solve?

2. Target Users
   Who will use it?

3. Features
   What can users do?

4. Sections
   List every section in order.

5. Components
   What elements does each section contain?

6. Wireframe
   Draw a rough layout (paper is perfectly fine).

7. HTML Structure
   Which semantic tags will you use?

8. CSS Plan
   Which layouts will use Flexbox?
   Which layouts will use Grid?
   Where might positioning be needed?

9. Responsive Plan
   How should it change on mobile?

10. Future Improvements

PROJECT NAME: Personal Profile Card

1. Purpose:

A) Display a professional profile card that introduces a person, highlights their profession, provides a short biography, and offers quick access to their social profiles and contact options.

B) Learning Objectives
Semantic HTML
CSS Flexbox
Typography
Color combinations
Basic responsive layouta

2. Target Users

Me as the developer of the project, learning coding skills, showing my condensed bio.

<!-- Recruiters on LinkedIn, students on GyanShikha website later, anyone who wants to know about me. -->

Primary Users

Recruiters
Clients
Students
Developers visiting GitHub

3. Features

<!-- Users can have a look at my bio, view my social media platforms including GitHub and LinkedIn -->

View profile
Read biography
Open LinkedIn
Visit GitHub
Send message
Follow profile

4. Sections

Profile Card

    Header

    Profile Information

    About

    Social Links

    Call To Action

5. Components and Scementic Tags

Header

    Profile Image

    Name

    Designation

About

    Paragraph

Social Links

    List

        GitHub

        LinkedIn

        Instagram

CTA

    Connect Button

    Message Button

6. Layout Planning

---

       Profile Image

       Name

       Designation

---

      About Me

      Paragraph

---

      GitHub

      LinkedIn

      Instagram

---

[Connect]

[Message]

---

7. HTML Structure

body
└── main
---└── article.profile-card
--------├── header
--------│ ├── img
--------│ ├── h1
--------│ └── p
--------├── section.about
--------│ └── p
--------├── section.social
--------│ └── ul
--------│ ├── li
--------│ ├── li
--------│ └── li
--------└── footer.actions
----------├── button
----------└── button

8. CSS Plan

main, header- display: flex; flex-direction: column; justify-content: centre; align-items: centre;
section social- display: flex; justify-content: space-between; align-items: centre;
