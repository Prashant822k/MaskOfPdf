# MaskOfPdf - PDF Chat Application

A full-stack chat application that allows users to upload PDF files and interact with an AI assistant to discuss the content.

## Technologies Used
- Next.js
- React
- TypeScript
- Tailwind CSS
- Clerk (Authentication)
- Drizzle ORM
- PostgreSQL
- AWS S3
- OpenAI API
- Stripe (Payments)
- Pinecone (Vector Database)

## Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Prashant822k/MaskOfPdf.git
   cd MaskOfPdf
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Set up environment variables
   Create a `.env` file in the root directory with required API keys for:
   - Clerk (Authentication)
   - AWS S3 (File Storage)
   - OpenAI (AI Chat)
   - Pinecone (Vector Database)
   - Stripe (Payments)
   - PostgreSQL (Database)

4. Run the development server
   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) in your browser.

## Features
- PDF upload and storage
- AI-powered chat with PDF content
- User authentication
- Subscription management

## Note
This project requires API keys from multiple services to function properly.