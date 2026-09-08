# AI-Assisted Learning Management System (LMS)

A modern, full-featured Learning Management System powered by AI to enhance online education and training.

## Features

### 🎓 Core LMS Features
- **Course Management**: Create, manage, and organize courses
- **Student Management**: Track student progress and performance
- **Assessment Tools**: Create quizzes, assignments, and exams
- **Progress Tracking**: Real-time monitoring of student learning progress
- **Certificates**: Automated certificate generation upon course completion

### 🤖 AI-Powered Features
- **AI Tutor**: Personalized tutoring and instant question answering
- **Smart Content Generation**: Auto-generate course materials and summaries
- **Intelligent Grading**: AI-assisted automated grading with feedback
- **Personalized Learning Paths**: AI recommends customized learning sequences
- **Content Analysis**: Analyze student responses for improved learning outcomes

### 📊 Analytics & Reporting
- Comprehensive student performance analytics
- Course engagement metrics
- Learning progress visualization
- Customizable reports and dashboards

### 👥 User Management
- Role-based access control (Admin, Instructor, Student)
- User authentication and authorization
- Profile management and preferences

## Tech Stack

### Frontend
- **React 18**: UI library
- **TypeScript**: Type safety
- **Tailwind CSS**: Styling
- **Vite**: Build tool
- **Framer Motion**: Animations

### Backend (To be integrated)
- **Node.js/Express**: API server
- **MongoDB**: Database
- **OpenAI API**: AI features
- **JWT**: Authentication

### AI Integration
- **OpenAI GPT-4**: Intelligent tutoring and content generation
- **Claude API** (Optional): Alternative AI provider

## Project Structure

```
ai-lms-platform/
├── src/
│   ├── components/        # Reusable React components
│   ├── pages/             # Page components
│   ├── store/             # State management (Zustand)
│   ├── services/          # API and external services
│   ├── hooks/             # Custom React hooks
│   ├── types/             # TypeScript types
│   ├── utils/             # Utility functions
│   ├── App.tsx            # Main app component
│   └── main.tsx           # Entry point
├── public/                # Static assets
├── vite.config.ts         # Vite configuration
├── tailwind.config.js     # Tailwind configuration
└── package.json           # Project dependencies
```

## Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn
- OpenAI API key (for AI features)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/kikijuniyanto/ai-lms-platform.git
cd ai-lms-platform
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env.local` file:
```
VITE_OPENAI_API_KEY=your_openai_api_key
VITE_API_URL=http://localhost:3000/api
```

4. Start the development server:
```bash
npm run dev
```

5. Open [http://localhost:5173](http://localhost:5173) in your browser

## Development

### Build for production:
```bash
npm run build
```

### Preview production build:
```bash
npm run preview
```

### Lint code:
```bash
npm run lint
```

### Format code:
```bash
npm run format
```

## Key Components

### Pages
- **Dashboard**: Overview and quick statistics
- **Courses**: Browse and enroll in courses
- **Classroom**: Access course materials and lessons
- **Assignments**: Submit and track assignments
- **AI Tutor**: Chat with AI for learning assistance
- **Analytics**: Performance and progress analytics
- **Admin Panel**: Course and user management

### AI Services
- **AI Tutor Service**: Handles tutoring conversations
- **Content Generator**: Generates course materials
- **Grading Service**: Automated assessment grading
- **Recommendation Engine**: Suggests learning paths

## API Endpoints

### Authentication
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - Login user
- `POST /api/auth/logout` - Logout user

### Courses
- `GET /api/courses` - List all courses
- `GET /api/courses/:id` - Get course details
- `POST /api/courses` - Create course (admin only)
- `PUT /api/courses/:id` - Update course
- `DELETE /api/courses/:id` - Delete course

### Enrollments
- `POST /api/enrollments` - Enroll in course
- `GET /api/enrollments/my` - Get my enrollments
- `GET /api/courses/:id/students` - List course students

### AI Features
- `POST /api/ai/tutor` - Chat with AI tutor
- `POST /api/ai/generate-content` - Generate course content
- `POST /api/ai/grade` - Grade assignment with AI
- `GET /api/ai/recommendations` - Get learning recommendations

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, email support@ailms.com or create an issue in the GitHub repository.

---

**Built with ❤️ for educators and learners worldwide**
