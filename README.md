# Hospital Management System

A full-stack Hospital Management System designed to simplify hospital operations and manage healthcare-related information through a web-based application. The project uses Next.js for the frontend and Supabase for backend services and database management.

## Live Demo

**Frontend:** [Hospital Management System](https://hospital-management-system-d2td.vercel.app/)

**Backend & Database:** Hosted on Supabase.

## Technologies Used

### Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS (if used in the project)

### Backend & Database

- Supabase
- PostgreSQL
- Supabase Authentication (if enabled)
- Row Level Security (RLS)

## Features

- User authentication and login
- Three user profiles: Admin, Doctor, and Patient
- Role-based access control for each user profile
- **Admin:** Manages hospital operations and oversees system activities.
- **Doctor:** Accesses doctor-related features and manages assigned responsibilities.
- **Patient:** Accesses patient-related features and views relevant information.
- Hospital dashboard management
- Patient information management
- Doctor management
- Billing and invoice management
- Payment records management
- Supabase database integration
- Responsive user interface

## Project Architecture

- **Frontend:** Next.js, deployed on Vercel.
- **Backend:** Supabase backend services.
- **Database:** PostgreSQL hosted on Supabase.
- **Authentication:** Supabase Authentication, if configured.

## Testing Credentials

Use the following accounts to explore the application.

### Admin

- **Email:** `admin@hms.com`
- **Password:** `Password123!`

### Doctor

- **Email:** `aqsatariq@gmail.com`
- **Password:** `Password123!`

### Patient

- **Email:** `fatima@gmail.com`
- **Password:** `Password123!`

## Getting Started

### Prerequisites

- Node.js
- npm
- Git
- A Supabase project

### Installation

#### 1. Clone the Repository

Replace the placeholder with your actual frontend repository URL.

```bash
git clone <your-frontend-repository-url>
```

#### 2. Navigate to the Project Directory

```bash
cd Hospital-Management-System
```

#### 3. Install Dependencies

```bash
npm install
```

#### 4. Configure Environment Variables

Create a `.env.local` file in the project root:

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY=your_supabase_publishable_key
NEXT_PUBLIC_SITE_URL=http://localhost:3000
```

#### 5. Start the Development Server

```bash
npm run dev
```

#### 6. Open the Application

Visit:

```text
http://localhost:3000
```

## Environment Variables

| Variable | Description |
|---|---|
| `NEXT_PUBLIC_SUPABASE_URL` | Supabase project URL |
| `NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY` | Supabase publishable key |
| `NEXT_PUBLIC_SITE_URL` | Application base URL, if used |

Never commit `.env.local` or expose Supabase service-role or secret keys in frontend code.

## Deployment

### Frontend — Vercel

The Next.js frontend is deployed on Vercel and accessible through the live demo link above.

### Backend & Database — Supabase

Supabase hosts the backend services and PostgreSQL database used by the application. The frontend connects to Supabase through its configured environment variables.

## Security

- Keep private credentials out of source control.
- Configure appropriate Row Level Security (RLS) policies.
- Protect patient and medical records through proper access controls.
- Keep privileged service-role credentials server-side.

## Author

**Ishrat Talib**
