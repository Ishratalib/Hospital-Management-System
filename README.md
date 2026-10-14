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
- Tailwind CSS

### Backend & Database

- Supabase
- PostgreSQL
- Supabase Authentication
- Row Level Security (RLS)

## Features

- User authentication and login
- Role-based access control
- Three user profiles: Admin, Doctor, and Patient
- Hospital dashboard management
- Patient information management
- Doctor management
- Billing and invoice management
- Payment records management
- Supabase database integration
- Responsive user interface

## User Profiles

The Hospital Management System includes three user profiles with role-based access.

### Admin

- Accesses administrative features.
- Manages hospital operations and relevant system activities.

### Doctor

- Accesses doctor-related features.
- Manages assigned responsibilities and relevant patient information.

### Patient

- Accesses patient-related features.
- Views relevant personal and healthcare information.

## Project Architecture

- **Frontend:** Next.js, deployed on Vercel.
- **Backend:** Supabase backend services.
- **Database:** PostgreSQL hosted on Supabase.
- **Authentication:** Supabase Authentication.
- **Security:** Row Level Security (RLS), where configured.

## Project Structure

For the complete folder and file structure, see [PROJECT_STRUCTURE.txt](https://github.com/Ishratalib/Hospital-Management-System/blob/main/PROJECT_STRUCTURE.txt).

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

Follow these steps to run the project locally.

### Prerequisites

- Node.js
- npm
- Git
- A Supabase project with the required database configuration

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/Ishratalib/Hospital-Management-System.git
```

**2. Navigate to the project directory**

```bash
cd Hospital-Management-System
```

**3. Install dependencies**

```bash
npm install
```

**4. Configure environment variables**

Create a `.env.local` file in the project root and add the following variables:

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY=your_supabase_publishable_key
NEXT_PUBLIC_SITE_URL=http://localhost:3000
```

Replace the placeholder values with your own Supabase project URL and publishable key.

**5. Start the development server**

```bash
npm run dev
```

**6. Open the application**

Visit [http://localhost:3000](http://localhost:3000) in your browser.

## Environment Variables

| Variable | Description |
|---|---|
| `NEXT_PUBLIC_SUPABASE_URL` | Supabase project URL |
| `NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY` | Supabase publishable key |
| `NEXT_PUBLIC_SITE_URL` | Application URL |

Never commit your actual `.env.local` file or expose secret keys in a public repository.

## Deployment

- **Frontend:** Deployed on Vercel.
- **Backend & Database:** Hosted on Supabase.

Configure the required environment variables in the Vercel project settings before deploying.

## Security

- Use Row Level Security (RLS) policies to protect database records.
- Apply role-based access controls for Admin, Doctor, and Patient profiles.
- Keep service-role keys and other sensitive credentials server-side.
- Never commit secrets or private environment variables to GitHub.

## Author

**Ishrat Talib**
