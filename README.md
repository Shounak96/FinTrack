# FinTrack – Full-Stack Personal Finance Tracker

FinTrack is a full-stack personal finance web application that allows users to track expenses, manage monthly budgets, and visualize spending through an interactive dashboard. The project is built using a modern Next.js stack and follows real-world full-stack engineering practices.

---

## Features Implemented

- User authentication and protected routes
- Create, update, and delete financial transactions
- Monthly budget management
- Real-time calculation of monthly expenses
- Interactive dashboard with charts and insights
- Account-based balance tracking
- Receipt scanning and transaction extraction (optional feature)
- Rate limiting and request protection

---

## Technologies & Services Used

### Core Technologies
- Next.js (App Router)
- React
- TypeScript
- Tailwind CSS
- Prisma ORM
- PostgreSQL (Supabase)

### Authentication & Security
- Clerk (authentication and user management)
- Arcjet (rate limiting and request protection)
- Zod (input validation)

### Additional Services
- Supabase (database hosting)
- Inngest (background jobs)
- React Email + Resend (email workflows)
- Google Generative AI (receipt scanning)

---

## Project Structure

```text
actions/           # Server actions (transactions, budgets, accounts)
app/               # Next.js App Router pages and routes
components/        # Reusable UI components
hooks/             # Custom React hooks
lib/               # Prisma client and integrations
data/              # Static data and constants
emails/            # Email templates
prisma/            # Database schema and migrations
public/            # Static assets
middleware.js      # Authentication and route protection

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.
