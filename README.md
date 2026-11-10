# 🚀 CareerGuide – AI-Powered Career Guidance Platform

**CareerGuide** is an AI-powered career guidance platform designed to help students and job seekers discover suitable career opportunities based on their skills, academic background, and personal interests.

The platform uses Generative Artificial Intelligence to analyze user profiles, recommend personalized career paths, extract skills from resumes, and generate step-by-step career development roadmaps.

🌐 **Live Demo:** https://inspirzy.vercel.app

---

## ✨ Key Features

### 1. AI-Powered Career Recommendations
- Analyzes users' technical and professional skills.
- Evaluates academic qualifications and educational backgrounds.
- Identifies career opportunities based on personal interests.
- Recommends suitable job roles and industries.
- Generates career suitability and confidence scores.
- Provides actionable career development suggestions.

### 2. Resume Upload and Analysis
- Allows users to upload their resumes.
- Extracts relevant skills and academic information.
- Analyzes educational qualifications and professional experience.
- Uses AI to understand the user's career profile.
- Helps identify suitable career opportunities.

### 3. Personalized Career Roadmap
- Generates customized career development plans.
- Divides career preparation into different learning stages.
- Provides estimated completion durations.
- Suggests technical skills and knowledge to develop.
- Generates actionable tasks for achieving career goals.

### 4. AI-Based Resume Summary Generator
- Generates professional skill summaries.
- Highlights relevant skills and experiences.
- Customizes resume summaries according to selected career paths.
- Helps students present their qualifications effectively.

### 5. AI Chat Assistant
- Provides AI-powered conversational assistance.
- Answers programming and technical questions.
- Supports queries related to cybersecurity, cloud computing, AWS, and web development.
- Provides explanations and practical suggestions.

### 6. User Authentication
- User registration and login.
- Firebase Authentication integration.
- Email and password authentication.
- Password recovery functionality.
- Secure user session management.

---

## 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Frontend | React.js, Next.js 15 |
| Programming Language | TypeScript, JavaScript |
| Styling | Tailwind CSS |
| UI Components | Radix UI, Shadcn UI |
| Artificial Intelligence | Google Generative AI |
| AI Framework | Genkit |
| AI Language Model | Google Gemini 1.5 Flash |
| Authentication | Firebase Authentication |
| Database | Firebase Firestore |
| Form Management | React Hook Form |
| Data Validation | Zod |
| Icons | Lucide React |
| Deployment | Vercel |

---

## 🤖 Artificial Intelligence Models

### Google Gemini 1.5 Flash

The project integrates Google Gemini 1.5 Flash through the Genkit framework.

**Applications:**

1. **Career Recommendation:** Analyzes skills, academic background, and interests to generate suitable career recommendations.
2. **Resume Parsing:** Extracts skills and educational information from resume text.
3. **Career Roadmap Generation:** Creates personalized learning stages and actionable career development tasks.
4. **Resume Summary Generation:** Generates career-specific professional summaries.
5. **AI Chat Assistant:** Generates conversational responses to technical questions.

### AI Development Frameworks and Libraries

- **Google Genkit:** Integrates AI models and manages generative AI workflows.
- **Google AI Plugin:** Connects the application with Google's Gemini models.
- **Zod:** Validates AI input and output structures.

---

## 🏗️ System Architecture

The application follows a modern full-stack architecture.

**1. Presentation Layer**
- Next.js and React.js.
- TypeScript-based user interface.
- Tailwind CSS styling.
- Interactive user dashboards.

**2. Application Layer**
- Next.js server-side functionality.
- User authentication.
- Resume processing.
- Career recommendation processing.
- Roadmap generation.

**3. Artificial Intelligence Layer**
- Google Genkit framework.
- Gemini 1.5 Flash model.
- AI-powered resume analysis.
- Personalized career recommendations.
- Intelligent roadmap generation.

**4. Database and Authentication Layer**
- Firebase Authentication.
- Firebase Firestore integration.
- User authentication and session management.

---

## 📁 Project Structure

```text
CareerGudiance/
│
├── docs/
│
├── public/
│
├── src/
│   ├── ai/
│   │   ├── flows/
│   │   │   ├── chat.ts
│   │   │   ├── parse-resume.ts
│   │   │   ├── generate-roadmap.ts
│   │   │   ├── generate-personalized-career-paths.ts
│   │   │   └── summarize-skills-for-resume.ts
│   │   │
│   │   ├── dev.ts
│   │   └── genkit.ts
│   │
│   ├── app/
│   │
│   ├── components/
│   │
│   ├── hooks/
│   │   └── use-auth.tsx
│   │
│   └── lib/
│       └── firebase.ts
│
├── .gitignore
├── firebase.json
├── firestore.rules
├── next.config.ts
├── package.json
├── package-lock.json
├── tailwind.config.ts
├── tsconfig.json
├── apphosting.yaml
└── README.md
```

---

## ⚙️ Installation and Setup

### Prerequisites

- Node.js
- npm
- Git
- Google AI Studio API Key
- Firebase Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/saidurga144/CareerGudiance.git
```

Navigate to the project directory:

```bash
cd CareerGudiance
```

### Step 2: Install Dependencies

```bash
npm install
```

### Step 3: Configure Environment Variables

Create a `.env.local` file in the project root directory.

```env
GEMINI_API_KEY=your_google_gemini_api_key
```

Generate your API key through Google AI Studio:

https://aistudio.google.com/

### Step 4: Configure Firebase

1. Create a Firebase project.
2. Enable Firebase Authentication.
3. Configure Email/Password authentication.
4. Configure Firebase Firestore if using database functionality.
5. Update Firebase configuration in `src/lib/firebase.ts`.

### Step 5: Run the Application

Start the development server:

```bash
npm run dev
```

Open the application in your browser:

```text
http://localhost:9002
```

### Step 6: Run the Genkit Development Environment

To run the Genkit development environment separately:

```bash
npm run genkit:dev
```

### Step 7: Build for Production

```bash
npm run build
```

Start the production server:

```bash
npm run start
```

---

## 🔄 Application Workflow

1. **User Registration:** Students create an account and log in.
2. **Profile Submission:** Users provide their skills, academic background, and interests.
3. **Resume Analysis:** Users can provide resume information for AI-based skill extraction.
4. **AI Processing:** Gemini 1.5 Flash analyzes the submitted information.
5. **Career Recommendations:** The system generates personalized career opportunities with suitability scores.
6. **Roadmap Generation:** The system generates structured career development stages and learning tasks.
7. **Career Development:** Users follow the recommended roadmap to achieve their career goals.

---

## ☁️ Deployment

The application is deployed using Vercel.

**Deployment Steps:**

1. Push the project to GitHub.
2. Connect the repository to Vercel.
3. Configure the required Gemini API environment variable.
4. Configure Firebase settings.
5. Deploy the Next.js application.
6. Access the application using the generated deployment URL.

---

## 🔮 Future Enhancements

- AI-based resume scoring and ATS optimization.
- Job recommendation based on real-time job market data.
- Integration with LinkedIn job opportunities.
- AI-powered mock interview preparation.
- Skill gap analysis and assessment.
- Personalized course and certification recommendations.
- Career progress tracking.
- Advanced student performance analytics.

---

## 🎯 Project Objective

The main objective of CareerGuide is to simplify career planning through Artificial Intelligence. The platform helps students identify suitable career opportunities, understand their existing skills, discover areas for improvement, and follow personalized career development roadmaps.

By combining AI-powered resume analysis, career recommendations, and intelligent roadmap generation, CareerGuide aims to support students in making informed career decisions and achieving their professional goals.

---

## 📄 License

No license file is currently specified in the repository. Add an appropriate open-source license if you intend to distribute the project.

---

**Developed with ❤️ using Next.js, TypeScript, Firebase, and Generative Artificial Intelligence.**

🚀 **CareerGuide – Navigate Your Career with Confidence.**
