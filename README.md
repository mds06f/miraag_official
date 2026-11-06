# MIRAAG — Official Band Website & Admin Studio

<p align="center">
  <strong>WHERE TRADITION MEETS DISTORTION.</strong>
</p>

<p align="center">
  A cinematic digital identity for MIRAAG — a five-piece band blending Bollywood rock with the depth and expression of Indian classical music.
</p>

---

## About MIRAAG

**MIRAAG** is born from the fusion of two timeless elements: **MIRA + RAAG**.

- **MIRA** represents Mirabai, whose devotion to Lord Shri Krishna found expression through music, poetry, and unconditional love.
- **RAAG** represents the soul of Indian classical music — a timeless framework of melody, emotion, and artistic expression.

Together, MIRAAG represents a musical identity where Indian classical heritage meets contemporary rock energy.

This project aims to translate that philosophy into a premium digital experience.

## Project Overview

The MIRAAG website is a static, responsive website designed to serve as the band's official digital presence.

It also includes a dedicated **Admin Studio**, allowing authorised band members to manage website-related content through a simple interface.

The project focuses on:
- Premium visual identity and user experience.
- Responsive design across desktop and mobile devices.
- A dedicated content management interface.
- A modular foundation for future backend and database integration.

## Features

### 1. Official Band Website

- Cinematic landing page.
- MIRAAG's philosophy and story.
- Core band members and their roles.
- Music and video showcase.
- Photo gallery.
- Upcoming live events.
- Contact and booking information.

### 2. Admin Studio

A dedicated administration interface with a minimal horizontal navigation system.

**Overview**
- Minimal landing section for the admin panel.

**Core Members**
- Add new band members.
- Edit member information and roles.
- Add or update member photographs.
- Delete member entries.

**Music Videos**
- Add videos using YouTube, Vimeo, or other hosted video URLs.
- Edit video links and information.
- Delete existing entries.

**Gallery**
- Select multiple images through the device's native file picker.
- Add photographs to the gallery.
- Manage and delete gallery images.

**Live Events**
- Add upcoming events.
- Edit event names, dates, and venues.
- Delete events.
- Reorder events using drag-and-drop functionality.

**Additional functionality**
- Responsive admin interface.
- Hover-based editing controls.
- Visit Website shortcut.
- Browser-based local data persistence using `localStorage`.

### 3. Member Login

The project includes a dedicated login page for accessing the Admin Studio.

- Email and password validation.
- Show/hide password functionality.
- Password format validation.
- Invalid login feedback.
- Redirect to the admin panel after successful validation.

> **Security notice:** The current login system is a frontend demonstration. Credentials are stored in client-side JavaScript and are not suitable for production authentication. Server-side authentication must be implemented before public deployment.

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| Tailwind CSS | Responsive styling |
| CSS3 | Custom animations and visual effects |
| JavaScript | Interactivity and admin functionality |
| LocalStorage | Browser-based content persistence |
| Google Fonts | Typography |

**External resources**
- Tailwind CSS CDN
- Google Fonts

## Design System

The visual identity follows a dark, cinematic, minimalist aesthetic.

| Element | Value |
|---|---|
| Obsidian Black | `#090909` |
| Charcoal | `#171717` |
| Deep Crimson | `#9D2929` |
| Antique Gold | `#C3A875` |
| Ivory | `#F4F0E9` |

**Typography**
- Cormorant Garamond — Editorial headings.
- Inter — Body text and interface elements.
- Oswald — Labels and condensed typography.

## Project Structure

```text
MIRAAG/
│
├── index.html
│
├── login.html
│
├── admin.html
│
├── assets/
│   ├── band-hero.jpg
│   ├── member-01.jpg
│   ├── member-02.jpg
│   ├── member-03.jpg
│   ├── member-04.jpg
│   ├── member-05.jpg
│   ├── gallery-01.jpg
│   ├── gallery-02.jpg
│   └── ...
│
└── README.md
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Navigate to the Project

```bash
cd YOUR-REPOSITORY
```

### 3. Check the File Structure

Make sure the following files are present in the project root:

- `index.html`
- `login.html`
- `admin.html`

Keep the `assets` folder alongside these files.

### 4. Run the Project

No build process or package installation is required.

Simply open `index.html` in your browser.

You can also use the **Live Server** extension in Visual Studio Code for local development.

### 5. Access the Admin Studio

Open:

```text
login.html
```

Use the demonstration credentials configured in the login page's JavaScript.

After successful validation, you will be redirected to:

```text
admin.html
```

## Current Limitations

The current implementation is a frontend prototype.

- Admin content is stored in the browser's `localStorage`.
- Content changes are not automatically synchronized across devices.
- Changes made in the admin panel do not automatically update the public website.
- There is no shared database or backend API.
- Login credentials are not securely authenticated.
- Gallery images are stored locally in the browser.

### Future Development

The next phase of development can include:

- Supabase or Firebase database integration.
- Secure authentication and role-based access.
- Cloud image storage.
- Dynamic website content powered by the database.
- Real-time synchronization between the Admin Studio and public website.
- Deployment with a custom domain.

## Project Status

**Frontend development:** In progress.

**Backend and database integration:** Planned.

## Contributing

Suggestions, improvements, and contributions are welcome.

For major changes, please open an issue first to discuss the proposed modifications.

## License

This project is currently maintained as a digital platform for MIRAAG.

A formal open-source license can be added when the repository's distribution terms are decided.

---

<p align="center">
  <strong>MIRAAG</strong><br>
  <em>WHERE TRADITION MEETS DISTORTION.</em>
</p>
