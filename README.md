## Next.js Dashboard Application

A complete dashboard application built with **Next.js 14** and the App Router, developed following the official Next.js course.

### 🚀 Functionalities

- **Interactive dashboard** with charts and statistics
- **Invoice management** — viewing, creating, and editing
- **Customer management**
- **Authentication** with NextAuth.js
- **PostgreSQL** database for data persistence
- **Modern UI** with Tailwind CSS and Heroicons components

### 🛠️ Tech Stack

- **Framework**: Next.js 14 con App Router
- **Lang**: TypeScript
- **Styling**: Tailwind CSS
- **Authentication**: NextAuth.js (v5 beta)
- **Database**: PostgreSQL
- **Validation**: Zod
- **Package Manager**: pnpm

### 📁 Project Structure

| Directory | Description |
|-----------|-------------|
| `app/dashboard/` | Dashboard pages |
| `app/login/` | Login page |
| `app/lib/` | Utilities and helper functions |
| `app/ui/` | Reusable UI components |
| `app/ui/customers/` | Customer components |
| `app/ui/dashboard/` | Dashboard components (cards, charts, nav) |
| `app/ui/invoices/` | Invoice components |
| `app/layout.tsx` | Main layout |
| `app/page.tsx` | Homepage |

### 🏃 Getting Started

1. Install dependencies:
   ```bash
   pnpm install
   ```

2. Configure environment variables in the `.env` file

3. Start the development server:
   ```bash
   pnpm dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

### 📚 Credentials
   ```
  Email: user@nextmail.com
  Password: 123456
   ```