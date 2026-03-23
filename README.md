# AI-Powered Real Estate CRM Automation Platform

An intelligent CRM automation web application for real estate agents, built with Next.js, Supabase, and Drizzle ORM.  
This platform integrates AI voice agents, telephony, and CRM systems to streamline lead management and client communication.

## Features (MVP – Iteration 1)

This initial release focuses on core functionality connecting CRM systems, AI voice automation, and call routing.

- CRM Lead Import  
  Securely import contacts from Follow Up Boss using an API key.

- AI Voice Agents (ElevenLabs)  
  Automatically create personalized conversational AI agents per user.

- Twilio Integration  
  Generate isolated subaccounts for secure and scalable call routing.

- AI-Powered Outbound Calls  
  Initiate voice calls using AI agents integrated with telephony infrastructure.

- Lead Management Dashboard  
  View, filter, and manage leads in an intuitive React-based UI.

- Secure Authentication & Storage  
  Powered by Supabase authentication and PostgreSQL with Drizzle ORM.

## How It Works

1. User signs in via Supabase authentication  
2. User enters their CRM API key in the settings panel  
3. Leads are imported from Follow Up Boss and stored in PostgreSQL  
4. Clicking “ElevenLabs Agent” creates a personalized AI agent  
5. “Twilio Setup” provisions a subaccount for call routing  
6. User selects leads and initiates AI-driven outbound calls  

## Tech Stack

| Layer     | Technology                        |
|-----------|----------------------------------|
| Frontend  | Next.js (React, TypeScript)      |
| Backend   | Next.js API Routes               |
| Database  | Supabase (PostgreSQL)            |
| ORM       | Drizzle ORM                      |
| AI Voice  | ElevenLabs Conversational AI API |
| Telephony | Twilio Voice API                 |
| CRM       | Follow Up Boss API               |

## Phased Agile Development

This project follows a phased agile methodology, delivering incremental improvements across iterations.

### Phase 1 – MVP (Iteration 1)

- Core integrations with Follow Up Boss, ElevenLabs, and Twilio  
- Lead import and management interface  
- Individual AI agent setup  
- Twilio subaccount creation  
- AI-powered outbound call initiation  
- Persistent user settings via Supabase  

### Phase 2 – Iteration 2 (Enhancements)

#### 1. Onboarding Wizard
- Multi-step guided setup experience  
- Combines:
  - CRM API key configuration  
  - AI agent setup  
  - Twilio subaccount provisioning  
- Includes real-time feedback and automation  

#### 2. Batch Calling
- Trigger batch calls using ElevenLabs batch endpoint  
- Supports sequential or parallel execution  
- Includes progress tracking and error handling  

#### 3. Call History & Transcripts
- Dedicated dashboard for:
  - Call logs  
  - Conversation transcripts  
  - Agent summaries  
  - Lead interaction context  
- Stored in Supabase via Drizzle ORM schema  

#### 4. Enhanced Analytics (Future)
- Call success rate tracking  
- Call duration metrics  
- Sentiment analysis  
- Team-level dashboard insights  

## Tools and Integrations

- Supabase — Authentication and PostgreSQL hosting  
- ElevenLabs API — Conversational AI voice generation  
- Twilio API — Voice call automation  
- Follow Up Boss API — CRM integration  
- Drizzle ORM — Type-safe database layer  
- Next.js (App Router) — Full-stack framework  

## Security and Data Isolation

- Each user has dedicated Twilio subaccounts and isolated AI agents  
- Authentication handled via Supabase  
- Supports Row-Level Security (RLS) for strict per-user data access  

## Development Philosophy

This project follows a phased agile approach focused on:

- Rapid prototyping and validation  
- Continuous user feedback integration  
- Delivering functional increments over perfection  
- Scalable architecture with minimal refactoring  

## Authors

Nadeem Imani   
Rania Alvi  

