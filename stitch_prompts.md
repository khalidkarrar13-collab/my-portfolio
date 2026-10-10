# Master Stitch Prompts: Resume Template UI & Modern Portfolio UI/UX

This document provides two production-grade, copy-paste-ready prompts specifically engineered for **Google Stitch** (and modern AI design engines like v0, Claude Artifacts, or Tailwind UI generators).

---

## PROMPT 1: Stitch Prompt for 1-Page Executive Resume Template UI
> **Purpose:** Use this prompt in Stitch when you want to generate an ultra-clean, modern, print-ready 1-page executive resume template (A4 format: 210mm × 297mm) with zero overflow.

```text
Act as a Principal Design Systems Architect and Editorial UI Designer. Build a modern, ultra-clean, executive 1-page resume template using Tailwind CSS and semantic HTML5.

### TARGET SPECIFICATIONS:
- Format: Strictly 1 Page (Standard A4 / Letter format: 210mm x 297mm).
- Target User: Khalid Osman Omer, Commercial Operations & Business Development Associate.
- Output: Production-ready HTML with embedded Tailwind CSS classes and print media query styling.

### LAYOUT & ARCHITECTURAL GRID:
1. Container:
   - Fixed aspect ratio container (w-[210mm] min-h-[297mm] max-h-[297mm] mx-auto bg-white shadow-xl print:shadow-none print:w-full print:h-full overflow-hidden).
   - Padding: p-8 (or 24mm outer margin) to satisfy print-safe margins.
2. Grid System:
   - 2-Column Asymmetric Bento Grid:
     - Main Body Column (68% width / col-span-8): Header, Executive Summary, Chronological Experience with XYZ impact metrics.
     - Sidebar Column (32% width / col-span-4): Soft background (#F8FAFC / bg-slate-50), subtle rounded-lg border (border border-slate-200/80 p-5), housing Contact Channels, Core Competencies matrix, Google Certifications showcase, Education, and Languages.

### TYPOGRAPHY & MICRO-RHYTHM:
- Font Family: Inter, Plus Jakarta Sans, or Geist (clean geometric sans-serif).
- Name: 26px (text-2xl font-bold tracking-tight text-slate-900).
- Headline: 12px (text-xs font-semibold uppercase tracking-wider text-teal-700 mt-1).
- Section Titles: 11px (text-[11px] font-bold uppercase tracking-widest text-slate-500 border-b border-slate-200 pb-1 mb-2.5 flex items-center gap-1.5).
- Job Role Titles: 13px (text-[13px] font-bold text-slate-900).
- Subheadings/Companies: 11.5px (text-[11.5px] font-medium text-slate-600).
- Bullet Points: 10.5px (text-[10.5px] leading-relaxed text-slate-700). Metrics (e.g., 35+, 150+, 28%, 3.55 CGPA) MUST be wrapped in <strong class="text-slate-900 font-semibold">.

### COLOR PALETTE & VISUAL ACCENTS:
- Background: Pure White (#FFFFFF) for body; Soft Slate (#F8FAFC) for sidebar and badge backgrounds.
- Text: Slate-900 (#0F172A) for high-contrast titles; Slate-700 (#334155) for body copy; Slate-500 (#64748B) for labels and dates.
- Accent Color: Deep Teal / Emerald (#0D9488 / #0F766E) used selectively for title accents, date pills, and Google certification icons.
- Skill Badges: Pill design (bg-white border border-slate-200 text-slate-800 text-[9.5px] font-medium px-2 py-0.5 rounded shadow-2xs).
- Contact Metadata: Mini inline SVG icons (Phone, Mail, Pin, LinkedIn) with clickable anchor tags.

### DATA TO RENDER INSIDE THE TEMPLATE:
- Candidate Name: Khalid Osman Omer
- Target Title: Commercial Operations & Business Development Associate
- Contact: Bangsar, Kuala Lumpur | +60 17 510 0833 | khaledothman546@gmail.com | linkedin.com/in/khalid-osman-80b301287
- Summary: Bilingual Business Administration graduate (AIU, 3.55 CGPA) combining multi-market B2B business development, outbound client acquisition, and data analytics expertise. Proven track record in executing targeted outreach across Australia and APAC, managing CRM pipelines, and leveraging AI tools.
- Experience:
  1. QH Technology (May 2026 – Present) | International Sales & Operations Executive (Onsite)
     - Spearheaded B2B outbound acquisition campaigns targeting Australian commercial solar sector, securing 35+ qualified client opportunities.
     - Engineered structured market databases through multi-tier data filtering, improving prospect list accuracy and deliverability by 28%.
     - Managed end-to-end email outreach sequences, boosting lead-to-consultation response rates by 18%.
  2. Balkrushna Technologies (Jan 2026 – Apr 2026) | Sales & Business Development Intern (Remote)
     - Supported regional B2B market expansion, identifying 200+ high-potential enterprise accounts across key APAC verticals.
     - Executed personalized LinkedIn campaigns targeting C-level decision-makers, maintaining an average 24% response rate.
     - Streamlined CRM pipeline stages, improving sales cycle transparency and pipeline forecasting.
  3. TAKO (Oct 2025 – Apr 2026) | Digital Marketing & SEO Specialist
     - Authored and published 150+ search-optimized technical articles focused on industrial compliance, capturing top-3 SERP rankings.
     - Orchestrated multi-platform organic distribution campaigns (Reddit, Medium), boosting search impressions and traffic by 42%.
  4. Life Series Program (Aug 2024 – Dec 2025) | Co-Founder & Coordinator
     - Co-founded campus initiative; delivered 6 hands-on technical workshops for 120+ participants with a 94% satisfaction rating.
- Education: Albukhary International University (AIU) | Bachelor of Business Administration (Hons) | CGPA: 3.55 / 4.00 | Graduating 2026
- Certifications: Google AI Professional Certificate, Google Data Analytics Certificate, Google Project Management Certificate, Google Digital Marketing Certificate.
- Languages: Arabic (Native), English (Fluent), Spanish (Elementary A2).

### STRICT EXECUTION RULES:
- ZERO OVERFLOW: Must fit strictly inside 297mm height without vertical scrollbars or secondary pages.
- PRINT OPTIMIZATION: Include `@media print { @page { size: A4; margin: 0; } body { print-color-adjust: exact; -webkit-print-color-adjust: exact; } }`.
- Clean semantic HTML structure (header, main, aside, section, article).
```

---

## PROMPT 2: Stitch Prompt for Modern UI/UX Interactive Portfolio / Digital CV
> **Purpose:** Use this prompt in Stitch when you want to design a modern, interactive web portfolio showcasing Khalid's case studies, certifications, and commercial metrics with modern UI/UX design trends.

```text
Act as a Lead UI/UX Product Designer at a top-tier digital product studio (Linear, Apple, or Vercel aesthetic). 

Design a high-converting, modern, interactive Personal Portfolio & Executive CV Web Application for Khalid Osman Omer (Commercial Operations & B2B Business Development Specialist).

### DESIGN PHILOSOPHY & VISUAL LANGUAGE:
- Aesthetic: Modern Minimalist Executive Tech (Bento Grid, subtle glassmorphism, micro-interactions, clean monochrome foundation with Emerald/Teal accents).
- Color System:
  - Dark Theme Mode: Background #090D16, Card Surfaces #111827 with 1px border #1F2937, Text #F9FAFB, Muted #9CA3AF, Brand Accent #10B981 (Emerald).
  - Light Theme Mode: Background #FAFAFA, Card Surfaces #FFFFFF with 1px border #E5E7EB, Text #0F172A, Muted #64748B, Brand Accent #0D9488 (Teal).
- Typography: Inter Display / Geist Sans with crisp tabular numerals (font-mono for metrics and percentages).

### PAGE STRUCTURE & SECTIONS:

1. Dynamic Sticky Navigation Bar:
   - Candidate monogram logo ("KO").
   - Nav links: Overview, Impact Metrics, Experience, Google Credentials, Case Studies, Contact.
   - Action Items: "Download 1-Page PDF Resume" button (ghost button with download icon) and "Get in Touch" primary CTA button.

2. Hero Section (High-Impact Value Proposition):
   - Status Badge: Live pulse indicator ("Available for APAC & International Roles - Bangsar, KL").
   - Headline: "Scaling B2B Market Opportunities Through Data Intelligence & Relentless Execution."
   - Subtitle: 2-sentence executive summary emphasizing AI productivity, cross-border prospecting (Australia & APAC), and Quadruple Google Certification.
   - Quick Action Row: Schedule Call button, Email Copy widget (one-click copy with toast notification), LinkedIn redirect button.

3. Bento Grid - Executive Proof Points & Metrics:
   - Card A: 35+ Qualified B2B Solar Deals (Outbound Pipeline Growth).
   - Card B: 150+ Technical Compliance Articles (Organic Inbound Growth).
   - Card C: 3.55 CGPA (Albukhary International University, BBA Hons).
   - Card D: 4x Google Certified Badges with verification links (AI, Data Analytics, Project Management, Digital Marketing).

4. Interactive Experience Timeline:
   - Segmented toggle: All Roles | B2B Commercial | Operations & Data | Leadership.
   - Interactive role cards displaying:
     - Company logo placeholder, Role title, Employment dates & location badge.
     - Expandable accordion for Key Contributions and Methodologies.
     - Tech stack pills (e.g., Salesforce, LinkedIn Sales Nav, Excel Analytics, GA4).

5. Google Professional Credentials Showcase:
   - 4-column modern credential cards with Google brand color accents, course completion highlights, and downloadable badge preview.

6. Skills Matrix & Tooling Ecosystem:
   - Categorized into 3 interactive tabs:
     - Commercial & Sales Ops: B2B Prospecting, Lead Scoring, Negotiation, CRM Architecture.
     - Data & Business Intelligence: Market Intelligence, Excel Modeling, Google Data Analytics.
     - Modern Workflow & AI: Generative AI for Workflows, SEO Engineering, Agile Coordination.

7. Interactive Contact & Lead Capture Drawer:
   - Direct meeting booking widget preview.
   - Clean contact form with validation states.
   - One-click copy email button and WhatsApp quick link (+60 17 510 0833).

### UI/UX INTERACTION REQUIREMENTS:
- Smooth CSS transitions (`transition-all duration-300 ease-out`).
- Hover states on cards: subtle border illumination (`hover:border-teal-500/50 hover:shadow-lg`).
- Fully responsive across Desktop (1440px), Tablet (768px), and Mobile (375px).
- Deliver complete, valid Tailwind CSS HTML structure with SVG icons.
```

---

## PROMPT 3: Meta-Prompt for LLM Resume Customization & Job Tailoring
> **Purpose:** Use this prompt with any LLM (Claude, ChatGPT, Gemini) whenever you want to automatically tailor Khalid's resume for a specific Job Description (JD) without losing formatting.

```text
You are an Elite Executive Headhunter and Certified Professional Resume Writer (CPRW).

<task>
Analyze the candidate profile in <candidate_data> against the target job description in <job_description>.
Produce an optimized, ATS-tailored, single-page resume that achieves a 95%+ ATS keyword match while strictly following the Google XYZ formula.
</task>

<rules>
1. DO NOT fabricate qualifications, companies, or degrees.
2. STRICT 1-PAGE LIMIT: Total output must remain between 420 and 460 words.
3. Every bullet point must use the format: Accomplished [X] as measured by [Y] by doing [Z].
4. Align the candidate's headline and core competencies directly with the key requirements in <job_description>.
</rules>

<candidate_data>
[Paste Khalid Osman Omer's 1-page resume content from khalid_osman_resume_1page.md]
</candidate_data>

<job_description>
[Paste the specific job description here]
</job_description>
```
