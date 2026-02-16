# Aesthetic Launch Berlin

Aesthetic Launch Berlin is a web app concept that helps doctors become self-employed in aesthetic medicine in Berlin, Germany.

## Problem the app solves
Many doctors want to start offering aesthetic treatments but struggle with:
- finding trusted training pathways,
- understanding certification expectations,
- setting up a compliant practice model,
- and navigating German legal and regulatory requirements.

This app provides a guided pathway from "interested doctor" to "ready-to-launch practitioner."

## Target users
- Licensed doctors in Germany (or relocating to Germany)
- Doctors in Berlin transitioning from hospital/employed roles to private practice
- Early-stage aesthetic practitioners who need structured compliance guidance

## Core app modules

### 1) Training Navigator
- Curated catalog of aesthetic medicine courses (Botulinum toxin, fillers, skin boosters, devices)
- Filters by city, language, level, format (online/in-person), and cost
- Personalized learning plans based on prior experience and goals
- Progress tracking and reminders

### 2) Certification Tracker
- Checklist of recommended and required certifications/documents
- Upload and store certificates
- Expiry and renewal alerts
- Readiness score for launching services

### 3) Legal & Compliance Guide (Germany/Berlin)
- Step-by-step setup guides for self-employment in Berlin
- Business registration workflow and required authorities
- Tax and insurance overview (high-level, non-legal advice)
- Medical documentation, informed consent, advertising boundaries, and data protection reminders
- Downloadable templates (consent forms, treatment notes, policy checklists)

### 4) Practice Setup Planner
- Business model builder (solo practice, subletting, partnership)
- Cost calculator (rent, devices, consumables, insurance, software)
- Break-even estimator and pricing templates
- 90-day launch roadmap with milestones

### 5) Mentor & Community Layer
- Expert Q&A sessions with legal/tax/compliance professionals
- Mentor matching with experienced aesthetic physicians
- Peer group accountability and launch cohorts

## Suggested MVP (first version)
A practical MVP can include:
1. Onboarding questionnaire (specialty, experience, timeline, budget)
2. Berlin-specific compliance checklist
3. Training directory + simple recommendation engine
4. Document vault for certificates and key paperwork
5. Milestone dashboard with deadlines and reminders

## Key workflows
1. User signs up and completes onboarding.
2. App generates a personalized launch plan.
3. User books/marks trainings and uploads certificates.
4. User follows legal and setup checklist for Berlin.
5. User reaches "Launch Ready" status and exports a final dossier.

## Data model (high-level)
- `UserProfile`
- `TrainingProgram`
- `CertificationRecord`
- `LegalTask`
- `BusinessPlan`
- `Milestone`
- `Document`

## Compliance and trust principles
- Show clear disclaimers: educational support, not legal/tax advice.
- Keep legal content versioned and reviewable by qualified German professionals.
- Apply strict privacy standards for personal and professional data.
- Use role-based access and encrypted document storage.

## Success metrics
- Time-to-launch reduction for users
- Percentage of users completing legal/compliance checklist
- Training completion rate
- Number of users reaching "Launch Ready"
- User satisfaction and referral rate

## Recommended next steps
1. Validate with 10-15 target doctors in Berlin via interviews.
2. Partner with 2-3 trusted training providers.
3. Obtain legal review for checklist accuracy.
4. Build MVP with a simple web stack (e.g., Next.js + Supabase).
5. Pilot with a closed beta cohort and iterate monthly.

---
If you want, I can also draft:
- a clickable MVP feature map,
- user stories and acceptance criteria,
- and a complete 12-week build plan.
