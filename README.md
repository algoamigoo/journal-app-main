**Reflect** is a full-stack journaling application built with modern web technologies. It provides users with a secure and user-friendly platform to capture their thoughts, track their moods, and reflect on their journeys. The app emphasizes data privacy, security, and a seamless user experience.

## Features

- **User Authentication:**
  - Sign up and sign in using **Google** or **email/password** via **Clerk**.
  - Secure account management (update profile picture, name, email, etc.).
  - Protected routes to ensure only authenticated users can access sensitive data.

- **Rich Text Editor:**
  - Utilize a powerful **React Quill New** editor to format text, embed links, and add bullet points.
  - Save entries as drafts and continue editing later.

- **Mood Tracking:**
  - Select from a variety of moods to associate with each journal entry.
  - View mood analytics on the dashboard, including mood trends over time.

- **Collections:**
  - Organize journal entries into customizable collections (e.g., "Personal", "Work").
  - Create, view, update, and delete collections as needed.

- **Daily Prompts:**
  - Receive a new writing prompt every 24 hours to inspire your journaling.
  - Prompts are fetched from a public API and cached for efficiency.

- **Analytics Dashboard:**
  - View statistics such as total entries, average mood score, and most frequent mood.
  - Interactive mood timeline chart powered by **Recharts**.

- **Security:**
  - **Rate Limiting:**  Limits API requests to prevent abuse.
  - **Bot Protection:**  Blocks malicious bots while allowing search engine crawlers.
  - **Shield:**  Protects against common web attacks.

## Technologies Used

- **Frontend:**
  - **Next.js 15** (App Router)
  - **React 19**
  - **Shadcn UI** (Component library built on Tailwind CSS)
  - **Tailwind CSS** (Utility-first CSS framework)
  - **React Hook Form** (Form state management)
  - **Zod** (Form validation)
  - **React Quill New** (Rich text editor)
  - **Recharts** (Data visualization)

- **Backend:**
  - **Next.js API Routes** (Server-side rendering and API endpoints)
  - **Prisma** (ORM for PostgreSQL)
  - **NeonDB** (PostgreSQL database)
  - **Clerk** (Authentication)
  - **Arcjet** (Security and rate limiting)
