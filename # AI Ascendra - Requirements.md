# AI Ascendra - Requirements

## 1. Functional Requirements

### 1.1. Core Learning Loop
- **Coding Sandbox**: Users must be able to write and execute code in a sandbox environment.
- **AI Assessment**: Users must be able to submit their code for assessment by an AI.
- **Feedback**: The AI must provide detailed feedback, including correctness, score, and suggestions for improvement.
- **Skill Tracking**: The system must track user progress across different skill categories (e.g., Algorithms, Security).

### 1.2. Personalized Learning
- **Friction Point Identification**: The system should analyze assessment results to identify specific areas where the user is struggling.
- **Personalized Project Generation**: Based on identified weaknesses, the AI should be able to generate personalized coding projects.
- **AI Tutor**: Users must have access to an AI tutor to ask questions about code or concepts.

### 1.3. Gamification and Engagement
- **Achievements/Badges**: The system will have a badging system to reward users for reaching milestones (e.g., solving their first problem, achieving high scores).
- **Skill Radar**: A visual representation (radar chart) of the user's skills and progress must be displayed on the dashboard.

### 1.4. Content and Exploration
- **Challenges**: A curated list of coding challenges with varying difficulty levels must be available.
- **Learning Center**: A section with learning resources (videos, docs, examples) organized by subject must be provided.

## 2. Non-Functional Requirements

### 2.1. User Interface & Experience
- **Modern & Luxurious UI**: The application must have a polished, visually appealing, and professional user interface.
- **Responsive Design**: The UI must be fully responsive and work seamlessly on desktop and mobile devices.
- **Intuitive Navigation**: Navigation should be clear and easy to use, with a persistent sidebar.

### 2.2. Performance
- **Fast Load Times**: The application should load quickly.
- **Responsive AI Interactions**: AI-powered features (assessment, project generation, tutor) should provide responses in a timely manner, with loading states to manage user expectations.

### 2.3. Technology Stack
- **Frontend**: Next.js, React, TypeScript, Tailwind CSS, ShadCN UI components.
- **AI/Backend**: Genkit for AI flows.

### 2.4. Scalability
- The architecture should be designed to handle a growing number of users and features.
