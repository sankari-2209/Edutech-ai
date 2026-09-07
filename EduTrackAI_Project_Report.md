# EduTrackAI — Project Report

**AI-Powered Learning & Progress Tracking Platform**

## 1. Overview
EduTrackAI is a web application (built in React) that combines a structured e-learning course, an AI tutor/chatbot, self-assessment tools, and a teacher-facing analytics dashboard into one platform. It supports two roles — **Student** and **Teacher** — each with a dedicated interface and feature set.

## 2. Core Modules

**Learning & Content**
- Full course ("Computer Science Fundamentals") organized into 5 modules and 21 lessons, covering topics from computing basics to networks.
- Lesson viewer with reading content, AI-generated summaries, and progress marking.
- Personal notes: create, search, and manage notes tied to lessons.
- "General Learning" tool: type any topic and get an AI-generated explanation on demand.

**AI Tutor**
- Conversational chatbot that answers questions about the current topic or lesson.
- Quick-action prompts (e.g., "Explain simply," "Give an example") that trigger contextual AI explanations.
- Multi-language response support.

**Assessment Tools**
- Auto-generated quizzes per topic (configurable difficulty/question count) with a full quiz engine (timing, scoring, retry, exit confirmation).
- Flashcards generated per topic for quick review.
- Automated feedback/performance messages based on quiz results.

**Placement Preparation**
- Aptitude practice organized by topic, with inline quizzes.
- Communication skills practice (written response prompts).
- Interview preparation (Q&A practice).
- Coding practice module.
- Dedicated placement-readiness progress tracking.

**Student Progress Tracking**
- Dashboard showing overall course progress, learning streaks (current & longest), quiz average, and completed lessons.
- Reminders system for study scheduling.
- Profile view with personal stats and language preference.

**Teacher Dashboard**
- Class-wide overview: student list with search, individual student profiles (progress, streak, quiz average, weak topics, placement readiness).
- **Reports**: generates 6 report types — Student Progress, Class Performance, Quiz Performance, Module Completion, At-Risk Students, and Placement Preparation — with print/export options.
- **AI Teaching Insights**: automated observations (e.g., students struggling with a topic, inactive students, top performers) derived from class data.

## 3. Technical Highlights
- Built with **React** (hooks-based state management: `useState`, `useMemo`, `useEffect`).
- Data visualization via **Recharts** (line, bar, and pie charts) for progress and performance analytics.
- Icon system via **lucide-react**; fully responsive UI with light/dark mode support.
- Modular component architecture: reusable `Card`, `Modal`, `ProgressBar`, `Toast`, and `SectionTitle` components used throughout.
- Currently powered by **demo/simulated data and responses** (e.g., simulated AI chat, generated quizzes/flashcards) rather than a live backend or LLM API — a strong prototype/demo ready for backend and real AI integration.

## 4. Summary
EduTrackAI demonstrates an end-to-end vision for an AI-assisted learning platform: structured content delivery, personalized AI tutoring, self-testing tools, placement/career prep, and rich analytics for both learners and educators — all within a single, cohesive, responsive interface.
