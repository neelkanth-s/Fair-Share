# Fair Share

Fair Share is a receipt expense splitting application that simplifies sharing bills between users. It uses Generative AI to extract receipt data, allowing users to quickly split expenses without manually entering each item.

## Features

### Receipt Processing
- Upload receipt images and automatically extract item names, prices, and categories.
- Converts receipt images into structured expense data using Google Gemini.

### Expense Splitting
- Select items and assign expenses between users.
- Automatically calculates each user's share of a bill.

### Authentication
- User authentication through Firebase Authentication.
- Personalized expense tracking for each user.

### Real-Time Updates
- Expense data is synchronized across users in real time using Firebase Realtime Database.

### Expense Entry Options
- Supports both receipt-based expense creation and manual entry.

## Tech Stack

- **Frontend:** Next.js (App Router), React, TypeScript, Tailwind CSS
- **Backend & Database:** Firebase Authentication, Firebase Realtime Database
- **AI Processing:** Google Gemini 1.5 for receipt parsing and structured data extraction
- **Deployment:** Vercel

## Getting Started

### Clone the Repository

```bash
git clone <repository-url>
cd fair-share
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env.local` file and add your Firebase configuration values.

### Run the Development Server

```bash
npm run dev
```

The application will be available at:

```
http://localhost:3000
```
