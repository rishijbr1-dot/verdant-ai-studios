# VERDANT AI STUDIOS

**Autonomous AI Content Intelligence & Production Company**

A production-grade web application featuring a fully realized, interactive, cinematic 3D virtual AI company headquarters. The 3D office IS the product, not an animation sitting on top of a dashboard.

## Vision

When users open VERDANT AI STUDIOS, the immediate impression must be:

> "This is a living AI company."

Users experience 81 specialized AI agents researching, thinking, writing, designing, producing, reviewing, translating and publishing content in real-time across a physical 3D virtual office.

## Core Features

### 🏢 3D Virtual Headquarters
- Cinematic, futuristic AI production facility
- Premium, dark visual identity (black, deep red, dark metallic, smoked glass)
- Multiple departments with unique architecture, lighting, and props
- Fully explorable environment with multiple camera modes

### 🤖 81 Specialized Agents
- **Research Intelligence Lab** (10 agents): Web, YouTube, trends, competitor, curriculum research
- **Content Intelligence Studio** (10 agents): Ideas, story architecture, scripts, dialogue
- **Creative Studio** (10 agents): Characters, worlds, scenes, visual concepts
- **Production Floor** (10 agents): Voice, music, SFX, animation, video assembly
- **Global Localization Hub** (10 agents): Multi-language translation and adaptation
- **Quality & Trust Lab** (10 agents): Fact-checking, safety, copyright, policy compliance
- **Publishing & Growth Center** (10 agents): SEO, scheduling, analytics, optimization
- **Continuous Retention Lab** (10 agents): Hook engineering, curiosity, pacing, engagement
- **Evidence Integrity Agent** (1 agent): Claims verification and source validation

### 📊 Master Orchestrator
- Central AI command center with holographic displays
- Live agent activity tracking
- Production workflow visualization
- Real-time task routing and state management

### 🎬 Production Pipeline
- Research-first content creation
- Hyper-research validation engine
- Retention engineering across entire video
- Knowledge gain architecture
- Curiosity loop engineering
- Comprehension and humor engines

### 🌍 Real-Time Production Demo
- Live demo production showing all agents in action
- Event-driven state system
- Cinematic camera transitions
- Live event stream from application state

## Technology Stack

### Frontend
- **React 18** with TypeScript
- **Vite** for fast development and builds
- **Three.js** for 3D rendering
- **React Three Fiber** for React-Three.js integration
- **Drei** for 3D helpers and abstractions
- **GSAP** for cinematic animations
- **Zustand** for state management

### Backend
- **Node.js** with TypeScript
- **Express** for HTTP server
- **Modular architecture** with clear separation of concerns

### AI Provider
- **Gemini** (Google AI Studio) with provider abstraction
- **Demo Mode** for execution without API key

## Project Structure

```
verdant-ai-studios/
├── src/
│   ├── 3d/                 # Three.js scene, environments, models
│   ├── agents/             # Agent system and logic
│   ├── departments/        # Department configurations
│   ├── orchestrator/       # Master orchestrator and task routing
│   ├── production/         # Production pipeline and workflows
│   ├── research/           # Research engine and evidence system
│   ├── content/            # Content generation and scripting
│   ├── retention/          # Retention engineering
│   ├── localization/       # Translation and localization
│   ├── qa/                 # Quality assurance
│   ├── publishing/         # Publishing and distribution
│   ├── analytics/          # Analytics and learning loop
│   ├── components/         # React UI components
│   ├── state/              # Zustand stores
│   ├── services/           # API and provider services
│   ├── types/              # TypeScript types and schemas
│   ├── config/             # Configuration files
│   ├── App.tsx             # Root component
│   └── main.tsx            # Entry point
├── server/
│   ├── index.ts            # Server entry point
│   ├── routes/             # API routes
│   ├── agents/             # Agent execution logic
│   ├── orchestrator/       # Orchestration logic
│   ├── providers/          # AI providers (Gemini, Demo)
│   ├── services/           # Business logic
│   └── types/              # Shared types
├── public/                 # Static assets
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

## Development Phases

1. **PHASE 1**: Project foundation (React, TypeScript, Vite, Node)
2. **PHASE 2**: 3D headquarters environment
3. **PHASE 3**: Departments and floor map
4. **PHASE 4**: Generic agent system
5. **PHASE 5**: Agent movement and state
6. **PHASE 6**: Master Orchestrator
7. **PHASE 7**: Production workflow
8. **PHASE 8**: Research + Evidence Integrity
9. **PHASE 9**: Content + Hyper-Research
10. **PHASE 10**: Retention Engineering
11. **PHASE 11**: Creative + Production
12. **PHASE 12**: Localization
13. **PHASE 13**: QA
14. **PHASE 14**: Publishing
15. **PHASE 15**: Gemini integration
16. **PHASE 16**: Analytics learning loop

## Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation

```bash
git clone https://github.com/rishijbr1-dot/verdant-ai-studios.git
cd verdant-ai-studios
npm install
```

### Configuration

Copy `.env.example` to `.env` and configure:

```bash
cp .env.example .env
```

Set your Gemini API key (optional for demo mode):

```
AI_PROVIDER=gemini
GEMINI_API_KEY=your_key_here
```

### Development

```bash
# Start both frontend (Vite) and backend (Express)
npm run dev

# Frontend only (http://localhost:5173)
npm run client

# Backend only (http://localhost:3001)
npm run server
```

### Build

```bash
npm run build
```

### Type Checking

```bash
npm run type-check
```

## API Documentation

### Core Endpoints

```
GET  /api/projects           # List projects
POST /api/projects           # Create new project
GET  /api/projects/:id       # Get project details

GET  /api/agents             # List all agents
GET  /api/agents/:id         # Get agent details
POST /api/agents/:id/tasks   # Assign task to agent

GET  /api/tasks              # List tasks
GET  /api/events             # Stream live events

POST /api/production/start   # Start new production
GET  /api/production/status  # Get production status
GET  /api/production/:id     # Get production details

GET  /api/research           # Research pipeline
GET  /api/script             # Script generation
GET  /api/retention          # Retention analysis
GET  /api/storyboard         # Storyboard generation
GET  /api/translation        # Localization status
GET  /api/qa                 # QA reports
GET  /api/publishing         # Publishing status
GET  /api/analytics          # Analytics data
```

## Design Principles

1. **3D World First**: The environment communicates the company's intelligence. UI supports the world, not the reverse.

2. **Real State**: Every button performs a real state change. No decorative fake buttons.

3. **Configuration-Driven**: New agents are addable through configuration without rewriting core system.

4. **Evidence-Based**: All claims are verified. Research is hyper-researched. No fabricated shocking facts.

5. **Retention Engineering**: Genuine engagement through curiosity, knowledge, discovery, and meaningful payoff—not clickbait.

6. **Demo Mode**: Full architecture works without API key. Demo mode is simulated execution of real architecture, not fake UI.

7. **Modular Architecture**: Clear separation of concerns. Each department, agent, and system is independently testable.

## Performance

- Supports 80+ visible agents simultaneously
- Instancing and LOD for optimization
- Event-driven state updates
- Memoization and throttled updates
- Cinematic quality without frame rate compromise

## License

MIT
