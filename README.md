# SkillAsess

## Overview
The AI-Powered Quiz Generator is a web application that allows users to generate customized quizzes based on uploaded documents or specified topics. Leveraging AI, the system generates relevant quiz questions, making it an ideal tool for educators, trainers, and self-learners.

## Features
- **User Authentication:** Secure login using GitHub authentication.
- **AI Integration:** Uses the Gemini API for intelligent quiz generation.
- **Database Management:** Stores data efficiently using PostgreSQL and Drizzle ORM.
- **Responsive UI:** Built with Next.js and Shadcn UI for an intuitive user experience.
- **Data Display:** Utilizes TanStack Table for structured quiz presentation.
- **Deployment:** Hosted on Vercel for seamless access.

## Tech Stack
- **Frontend:** Next.js, Shadcn UI, TypeScript
- **Backend:** GitHub Authentication, Drizzle ORM, PostgreSQL, Supabase
- **AI Integration:** Gemini API
- **Deployment:** Vercel
- **Additional Tools:** TanStack Table, Zod

## Setup & Installation
### Prerequisites
Ensure you have the following installed:
- Node.js (v16+)
- Git
- PostgreSQL (if running locally)

### Installation Steps
1. **Clone the Repository**
   ```sh
   git clone https://github.com/mounishaa-k/SkillAsess/main
   cd your-repository
   ```

2. **Install Dependencies**
   ```sh
   npm install
   ```

3. **Set Up Environment Variables**
   Create a `.env.local` file and add the required API keys and database credentials:
   ```sh
   NEXT_PUBLIC_GITHUB_CLIENT_ID=your_github_client_id
   NEXT_PUBLIC_GITHUB_CLIENT_SECRET=your_github_client_secret
   DATABASE_URL=your_database_url
   GEMINI_API_KEY=your_gemini_api_key
   ```

4. **Run Database Migrations**
   ```sh
   npx drizzle-kit migrate
   ```

5. **Start the Development Server**
   ```sh
   npm run dev
   ```
   The application should now be running at `http://localhost:3000`

## Usage
- **Login with GitHub:** Authenticate securely using your GitHub account.
- **Generate a Quiz:** Upload a document or specify a topic to generate a quiz.
- **View & Manage Quizzes:** Access previous quizzes stored in the database.

## Deployment
- Deploy the application on **netify** 

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to your branch (`git push origin feature-branch`)
5. Open a pull request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, feel free to reach out:
- **Email:** mounisha.ks9@gmail.com 
- **GitHub:** [mounishaa-k](https://github.com/mounishaa-k)

Happy Coding! 🚀

