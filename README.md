# Manuskript - Publish anything

A minimalist platform for sharing knowledge across business, technology, culture, and more.

## Features

- 📚 **Browse Articles**: Discover articles across 6 categories
- ✍️ **Publish Freely**: Share your knowledge without login requirements
- 🔍 **Search & Filter**: Find exactly what you're looking for
- 📱 **Responsive Design**: Works perfectly on all devices

## Categories

- Business
- Finance  
- Marketing
- Technology
- Sports
- Culture

## Getting Started

### Option 1: Deploy to Vercel (Recommended)

1. Push this code to a GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Import your GitHub repository
4. Deploy automatically

### Option 2: Run Locally

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run the development server:
   ```bash
   npm run dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) in your browser

## Tech Stack

- **Frontend**: Next.js 14 with App Router
- **Styling**: Tailwind CSS
- **Database**: Supabase (optional)
- **Deployment**: Vercel

## Project Structure

```
manuskript-working/
├── app/
│   ├── articles/
│   │   ├── [id]/page.tsx    # Article detail page
│   │   ├── new/page.tsx     # New article form
│   │   └── page.tsx         # Articles listing
│   ├── globals.css          # Global styles
│   ├── layout.tsx           # Root layout
│   └── page.tsx             # Home page
├── components/
│   ├── Footer.tsx           # Footer component
│   └── Header.tsx           # Header component
├── package.json
├── tailwind.config.ts
└── tsconfig.json
```

## Next Steps

1. **Set up Supabase** (optional):
   - Create a Supabase project
   - Run the SQL from `supabase-schema.sql`
   - Add environment variables

2. **Customize**:
   - Update branding and colors
   - Add more categories
   - Implement user authentication (if needed)

3. **Deploy**:
   - Push to GitHub
   - Deploy to Vercel
   - Share your knowledge platform!

## License

MIT License - feel free to use this for your own projects!
