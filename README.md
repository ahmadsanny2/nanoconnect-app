# Nano Connect - SME & Nano Influencer Matching Platform

## Project Overview

**Concept**: "Tinder for UMKM & Nano Influencers"
Platform untuk mencocokkan UMKM/SME dengan nano influencers lokal berdasarkan budget, niche, dan target audience.

## Business Requirements

## Core Features
- **Matching Algorithm**: Budget-based, niche-specific, location-aware matching.
- **Target Users**: SMEs and local nano influencers.
- **Low Latency**: Real-time data using edge computing.

## Tech Stack & Infrastructure

### Frontend
- **Framework**: React.js + Vite
- **Deployment**: Tencent EdgeOne pages
- **Development**: VS Code, EdgeOne CLI, Google Antigravity, IDE Plugin

### Tools:
- **Code Editor**: VS Code / Google Antigravity
- **AI Assist**: Google Antigravity, IDE Plugin
- **LLM MOdel**: Gemini Flash/Pro
- **Other**: EdgeOne CLI

### Backeend & Storage
- **Database**: Supabase
- **Edge Storage**: KV Storage (cache)
- **Serverless**: Node Functions for business logic
- **AI Integration**: OpenAI for smart matching

### Authentication
- **Auth Service**: Supabase Auth
- **Method**: Third-party login integration

## Application Architecture

### Pages & Components
```
├── Home Page
├── About
├── Influencer Listing
├── Influencer Detail
├── Order/Booking System
├── AI Recommendation
├── Terms & Conditions
└── Authentication Page
```

### Data Models
- **Influencer Profile**: Niche, rates, location, portfolio
- **SME Profile**: Budget, target audience, campaign requirements
- **Matching Scores**: AI-Calculated compatibility rating