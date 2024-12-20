![Project Banner](https://res.cloudinary.com/cocoder/image/upload/v1731096003/Projects/SyncPad/www.sync-pad-pro.vercel.app_1_et5rm3.gif)

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Tech Stacks](#tech-stacks)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Architecture and Core Concepts](#architecture-and-core-concepts)
  - [1. **Real-Time Collaboration with Liveblocks**](#1-real-time-collaboration-with-liveblocks)
  - [2. **Authentication with Clerk**](#2-authentication-with-clerk)
  - [3. **Rich-Text Editing with Lexical**](#3-rich-text-editing-with-lexical)
- [Screenshots \& Demonstrations](#screenshots--demonstrations)
  - [1. **Home Page**](#1-home-page)
  - [2. **Real-Time Editing**](#2-real-time-editing)
- [Challenges \& Solutions](#challenges--solutions)
  - [Challenge 1: Real-Time Synchronization](#challenge-1-real-time-synchronization)
  - [Challenge 2: Rich-Text Editing with Performance](#challenge-2-rich-text-editing-with-performance)
  - [Challenge 3: Responsive Design](#challenge-3-responsive-design)
- [Future Improvements](#future-improvements)
- [License](#license)
- [Contact \& Contributions](#contact--contributions)

---

## Project Overview

Live Docs is a full-featured, real-time collaborative document editor designed to empower teams to work together seamlessly. This project brings together advanced real-time collaboration features, secure authentication, responsive design, and rich-text editing capabilities—all powered by a modern tech stack, including Next.js, Liveblocks, Clerk, Tailwind CSS, and Lexical.

With Live Docs, you can create, edit, and share documents with multiple users in real-time, leveraging powerful features like live cursors, nested comments, tagging, and more.

---

## Key Features

- **Real-Time Collaboration**: Live, multi-user document editing with live cursors showing collaborator activity.
- **Markdown Editor**: Full support for rich-text formatting and markdown.
- **Flexible Document Sharing**: Invite collaborators with different access levels (viewers, editors).
- **Responsive UI**: Native-like, fully responsive design for desktop and mobile.
- **Authentication & Security**: Hassle-free user authentication with Clerk.
- **Advanced UI/UX Features**:
    - Nested comments, tagging, and emoji reactions.
    - Floating comments and instant notifications.
    - User presence indicators for collaborative environments.

---

## Tech Stacks

- **Frontend**: [React](https://reactjs.org/), [Next.js](https://nextjs.org/)
- **Real-Time Collaboration**: [Liveblocks](https://liveblocks.io/)
- **Rich-Text Editor**: [Lexical](https://lexical.dev/)
- **Authentication**: [Clerk](https://clerk.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Performance Monitoring**: [Sentry](https://sentry.io/)

---

## Getting Started

To get started with Live Docs on your local machine:

### Prerequisites

Ensure you have Node.js and npm installed.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Arafat-alim/sync-pad.git
cd sync-pad
```

2. Install dependencies:

```bash
npm install
```

3. Configure environment variables:

- Create a `.env.local` file in the root directory.
     - Add your Clerk API keys, Liveblocks keys, etc. (Refer to the example `.env.example`).

4. Run the development server:

```bash
npm run dev
```

5. Visit `http://localhost:3000` in your browser.

---

## Architecture and Core Concepts

### 1. **Real-Time Collaboration with Liveblocks**

- **Room Management**: Each document session is represented as a "room".
- **Live Cursors & User Presence**: See collaborator activity in real-time.
- **Data Synchronization**: All changes are instantly synchronized across users.

### 2. **Authentication with Clerk**

- Easy-to-use user management and authentication.
- Customizable sign-in, sign-up, and user management flows.

### 3. **Rich-Text Editing with Lexical**

- Advanced text formatting options with a modern markdown editor.
- Extensible with custom plugins for additional functionality.

---

## Screenshots & Demonstrations

### 1. **Home Page**

![Home Page Screenshot](https://res.cloudinary.com/cocoder/image/upload/v1731096654/Projects/SyncPad/Screen_Shot_2024-11-09_at_01.40.25-fullpage_lavmaj.png) <!-- Add a screenshot of your home page -->

### 2. **Real-Time Editing**

![Real-Time Editing GIF](https://res.cloudinary.com/cocoder/image/upload/v1731097108/Projects/SyncPad/kFy3vUSyTT_u65xmk.png) <!-- Add a GIF showing real-time editing and collaboration -->

---

## Challenges & Solutions

### Challenge 1: Real-Time Synchronization

**Solution**: Leveraged Liveblocks to provide seamless, real-time data synchronization, ensuring all user changes are instantly reflected.

### Challenge 2: Rich-Text Editing with Performance

**Solution**: Implemented Lexical, a performant text editor by Meta, and customized it with plugins for markdown support.

### Challenge 3: Responsive Design

**Solution**: Used Tailwind CSS utility classes for a mobile-first, fully responsive layout.

---

## Future Improvements

- **Advanced Permissions System**: Granular control over document access and user roles.
- **Offline Support**: Implement caching mechanisms for offline editing.
- **Enhanced Commenting System**: Support for threaded conversations and reactions.

---

## License

This project is licensed under the [MIT License](<[https://rem.mit-license.org](https://rem.mit-license.org)>).

---

## Contact & Contributions

For suggestions, contributions, or to report issues, please feel free to [open an issue](https://github.com/Arafat-alim/sync-pad/issues) or [contact me](mailto:arafat.aman.alim@gmail.com).

---
