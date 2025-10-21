Ah, that's the artifact interface metadata bleeding through. Let me give you the clean text to copy:
markdown# Provenance and Authorship

**Author:** Tom Smolinsky / VITSO  
**Work:** PHI/PII Identification & Handling — Technical Training  
**Initial drafting:** Jan 2025  
**Major enhancements:** Aug-Oct 2025

## Public Releases

### v3.0 — Major Content Expansion (2025-10-19)
**Module 3 Complete Rewrite - "When Safe Data Becomes PHI"**
- Expanded from basic scenarios to 6 comprehensive subsections with 20+ minutes of expert-level content
- New subsections: Basic Context Rules, Database Design & API Patterns, Logging & Analytics Traps, The Inference Problem, Multi-System Data Flows, HIPAA Safe Harbor
- Added practical code examples (PostgreSQL/MySQL patterns, API design, monitoring tools)
- Technical implementation guidance for Safe Harbor method
- Vendor-agnostic terminology (CSP for Cloud Service Providers)

**Module 4 Core Principles Expansion**
- Enhanced "Core Principles" subsection with three foundational principles:
  1. Minimize Access & Storage
  2. Use Approved Tools Only
  3. De-identify for Development
- Added "What this means in practice" sections with real-world scenarios
- Common violation examples and explanations

**UI/UX Improvements**
- Added subsection navigation breadcrumbs
- Improved Module 3 navigation with persistent section buttons
- Enhanced mobile responsiveness
- Fixed subsection visibility logic

**Content Quality**
- Enhanced learning objectives
- Updated marketing copy for community positioning
- Improved technical accuracy across all modules

### v2.4 — Module 4 Restructure (2025-10-16)
**Expanded Module 4 from 3 to 5 subsections:**
1. Core Principles (enhanced)
2. Tools & CSP Shared Responsibility (NEW)
3. De-Identification (preserved)
4. BAA & Obligations (enhanced with upstream obligations)
5. Data Architecture (NEW - isolation strategies)

**Question Bank Expansion**
- Added ~10 new questions (from 40 to ~50 total)
- Enhanced scenario-based questions
- Improved answer feedback

### v2.0.0 — Major Feature Enhancement (2025-10-13/14)
**Enhanced with 10 new features:**
1. ✅ Scoring feedback with detailed answer review showing correct/incorrect responses
2. ✅ Enhanced progress bar with real-time percentage display
3. ✅ Printable and emailable certificate with score and completion details
4. ✅ Learn Mode vs Assessment Mode toggle for flexible training
5. ✅ Visual feedback system (green checkmarks for correct, red X for incorrect)
6. ✅ Retry/reset functionality to retake training
7. ✅ Improved Module 3 subsection navigation with Next/Previous buttons
8. ✅ Responsive design with mobile-friendly layout and keyboard navigation
9. ✅ User name input field for personalized certificates
10. ✅ Enhanced section navigation with auto-scroll

**Bug fixes:**
- Fixed certificate print layout (removed answer key from print)
- Fixed Module 3 subsection navigation appearing in other modules
- Improved accessibility with ARIA labels and focus indicators

**New files added:**
- `LICENSE.html` — Formatted MIT License page with back navigation

### v1.0.3 — Governance Documentation (2025-09)
- Added COPYRIGHT, PROVENANCE.md, THIRD_PARTY_NOTICES.md
- Added DCO (Developer Certificate of Origin)
- Added DMCA counter-notice template

### v1.0.2 — Footer Fix (2025-08)
- Fixed footer placement inside training container

### v1.0.1 — Initial Licensing (2025-08)
- Added licensing footer
- Added attribution documentation

### v1.0.0 — Initial Public Release (2025-01-08)
- 8 training modules (Welcome + 6 content modules + Completion)
- 29 interactive questions with immediate feedback
- Module 3 with 6 detailed subsections on context-dependent PHI
- Basic certificate functionality
- Progress tracking with module navigation dots

## Statement of Originality

I (Tom Smolinsky / VITSO) wrote the training content and code. The v2.0.0 enhancements and v3.0 content expansion were developed in collaboration with Claude AI (Anthropic) to add advanced interactive features and comprehensive technical content. Any third-party snippets or assets are listed in `THIRD_PARTY_NOTICES.md` with attribution and license.

## Build Artifacts and Hashes

### v3.0
* `index.html` (SHA-256): `5E93ABF33EAF9C7C4F291CAF551D690B3763AB8E0BE7FB1876C2F44E5024CD55`

### v2.0.0
* `index.html` (SHA-256): `6C074A100093C2A574C4077C21E25A79EBEC6C0A5700BF09F055C82F4C556F88`
* `LICENSE.html` (SHA-256): `C73BCCBD5E7C6B983907F09F9D9CC7795C02AF4FAF406183198907B8BDE7BAD9`

### v1.0.3
* `index.html` (SHA-256): `caea5034e38d9c0264b260d666e7702ddef8f2556bcc3354c8e50d4fed94ab1a`

## Tooling Notes

- **Editor:** VS Code
- **AI Assistance:** Claude AI (Anthropic) for v2.0.0+ feature development and v3.0 content expansion
- **Testing:** Manual testing across Chrome, Firefox, Safari
- **Deployment:** GitHub Pages
- **No proprietary third-party material included**

## License

- **Code:** MIT License (see `LICENSE`)
- **Content:** Creative Commons Attribution 4.0 International (CC BY 4.0)

**Copyright © 2025 Tom Smolinsky / VITSO**
