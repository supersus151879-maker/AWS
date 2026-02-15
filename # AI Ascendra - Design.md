# AI Ascendra - Design Document

## 1. Design Philosophy

The design of AI Ascendra aims to be **luxurious**, **modern**, and **motivational**. The goal is to create a focused and inspiring environment where learners feel empowered to improve their coding skills. Key principles include:

- **Clarity and Focus**: The UI should minimize distractions and guide the user's attention to the learning task at hand.
- **Visual Feedback**: Progress should be visualized clearly through charts and achievements to keep users engaged.
- **Consistency**: A consistent design language, color palette, and component library should be used throughout the application.
- **Professional Aesthetic**: The look and feel should be polished and professional, suitable for a high-quality educational tool.

## 2. Color Palette & Theming

The application uses a dark theme by default, creating a focused environment that is easy on the eyes during long coding sessions.

- **Primary Color**: A vibrant purple (`hsl(262 84% 50%)`) is used for primary actions, highlights, and branding. It evokes creativity and ambition.
- **Background**: A very dark blue (`hsl(224 71% 4%)`) provides a deep, immersive background.
- **Card/Component Backgrounds**: Slightly lighter shades of the background color are used for cards (`hsl(224 71% 9%)`) to create a subtle sense of depth.
- **Accent Colors**: Used for charts and secondary information, providing visual contrast without overwhelming the user.
- **Glow/Shadow Effects**: Subtle glow and shadow effects on primary elements (like the main title and certain badges) add to the "luxurious" feel.

## 3. Layout & Architecture

The application is a Single Page Application (SPA) built with the Next.js App Router.

- **Main Layout**: A fixed sidebar for primary navigation and a main content area.
    - **Sidebar**: The sidebar is collapsible and provides quick access to the Dashboard, Challenges, Projects, and Learning Center. It uses icons for a minimal footprint, with tooltips for clarity.
    - **Header**: Contains the mobile menu trigger, AI Tutor access, and user profile menu.
- **Dashboard (`/`)**: The central hub.
    - It features a prominent "AI Ascendra" title.
    - The layout is a two-column grid on larger screens.
        - **Left Column**: The main interactive element, the `CodingSandbox`.
        - **Right Column**: Supporting information, including the `SkillRadar` and `Achievements` overview.
- **Content Pages (`/challenges`, `/projects`, `/learn`)**: These pages follow a consistent layout, with a clear heading and a grid of cards for displaying content.

## 4. Key Components

- **CodingSandbox**: A central component featuring a problem description and a large textarea for code input. It includes a primary button to trigger the AI assessment and displays the results directly below.
- **SkillRadar (ImprovementGraph)**: A radar chart visualizing the user's proficiency across different skills. It includes a feature to suggest a personalized project based on the user's weakest area.
- **ProgressOverview (Achievements)**: A grid of badges that visually represent user accomplishments. Unlocked badges are highlighted, while locked badges are grayscale, with tooltips providing hints.
- **Cards (`ChallengeCard`, `LearnCard`, Project Display)**: A consistent card design is used to present distinct items like challenges or learning subjects. Cards use a common structure with an icon, title, description, and call-to-action.
- **AI Tutor**: Implemented as a slide-out sheet, providing a conversational interface for users to ask questions without leaving their current context.

## 5. Typography

- **UI Text**: `Inter` is used for all UI text, providing excellent readability.
- **Code Text**: `Source Code Pro` is used for the coding sandbox and any code snippets, ensuring clear differentiation and a professional developer feel.
