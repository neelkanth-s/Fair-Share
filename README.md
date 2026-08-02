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

**Frontend**
- Next.js (App Router)
- React
- TypeScript
- Tailwind CSS

**Backend**
- Firebase Authentication
- Firebase Realtime Database

**AI**
- Google Gemini 1.5 for receipt parsing and structured data extraction

**Deployment**
- Vercel

## How It Works

1. Upload a receipt image.
2. Gemini extracts the receipt contents into structured data.
3. Review and select items to split.
4. Fair Share calculates each user's portion.
5. Expenses are updated automatically across users.

## Getting Started

Clone the repository:

```bash
git clone <repository-url>
cd fair-share
