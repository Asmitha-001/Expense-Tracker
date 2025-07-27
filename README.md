# Expense Tracker

A full-stack expense tracking application built with Next.js, Tailwind CSS, and MySQL.

## Features

- ✅ Add, view, and delete expenses
- ✅ Categorize expenses with predefined categories
- ✅ View expense statistics and summaries
- ✅ Responsive design with Tailwind CSS
- ✅ Real-time updates
- ✅ Category-based expense breakdown
- ✅ Monthly expense tracking

## Tech Stack

**Frontend:**
- Next.js 15 (App Router)
- React 19
- Tailwind CSS
- shadcn/ui components
- Lucide React icons

**Backend:**
- Node.js
- Next.js API Routes
- MySQL database
- mysql2 driver

## Getting Started

### Prerequisites

- Node.js 18+ installed
- MySQL server running
- npm or yarn package manager

### Installation

1. Clone or download the project
2. Install dependencies:
   \`\`\`bash
   npm install
   \`\`\`

3. Set up your MySQL database:
   - Create a new MySQL database
   - Run the SQL script in `scripts/setup-database.sql`

4. Configure environment variables:
   - Copy `.env.example` to `.env.local`
   - Update the database credentials

5. Start the development server:
   \`\`\`bash
   npm run dev
   \`\`\`

6. Open [http://localhost:3000](http://localhost:3000) in your browser

### Database Setup

The application includes a SQL script to set up your database:

1. Connect to your MySQL server
2. Run the script in `scripts/setup-database.sql`
3. This will create the database, tables, and sample data

### Environment Variables

Create a `.env.local` file with the following variables:

\`\`\`env
DB_HOST=localhost
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_NAME=expense_tracker
DB_PORT=3306
\`\`\`

## API Endpoints

- `GET /api/expenses` - Get all expenses
- `POST /api/expenses` - Add new expense
- `DELETE /api/expenses/[id]` - Delete expense
- `PUT /api/expenses/[id]` - Update expense
- `GET /api/expenses/stats` - Get expense statistics

## Usage

1. **Add Expenses**: Fill out the form with expense details
2. **View Expenses**: See all your expenses in the list
3. **Delete Expenses**: Click the trash icon to remove expenses
4. **View Stats**: Check your spending statistics at the top
5. **Category Breakdown**: See spending by category at the bottom

## Deployment

1. Build the application:
   \`\`\`bash
   npm run build
   \`\`\`

2. Deploy to your preferred platform (Vercel, Netlify, etc.)
3. Set up your production database
4. Configure environment variables in your deployment platform

## Contributing

Feel free to submit issues and enhancement requests!
