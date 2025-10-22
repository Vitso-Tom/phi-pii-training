# Provenance and Authorship

**Author:** Tom Smolinsky / VITSO  
**Work:** PHI/PII Identification & Handling — Technical Training  
**Initial drafting:** Jan 2025  
**Major enhancements:** Aug-Oct 2025

## Public Releases

### v3.1 — Progress Saving & Session Management (2025-10-21)
**New Features:**
- ✅ Automatic progress saving to browser localStorage
- ✅ "Welcome Back" resume prompt with session details
- ✅ Visual save confirmation toast notifications
- ✅ Complete state preservation (answers, modules, subsections, user name)
- ✅ Module 3 & 4 subsection tracking in resume prompt
- ✅ "Continue Training" or "Start Fresh" options
- ✅ Auto-save on question answers, navigation, and page close
- ✅ Graceful error handling and browser compatibility

**Technical Implementation:**
- Integration with existing state management system
- localStorage-based persistence (no backend required)
- JSON serialization of complete training state
- Subsection name capture for accurate resume display

**Build Artifacts:**
* `index.html` (SHA-256): `63A33B048455BD1AE0E00B79B70B7963EB5DF1C46A7FCB48708CBE60A1B454FD`

### v3.0 — Major Content Enhancements (2025-10-19)
**Module 3 Complete Rewrite:**
- Expanded to 6 comprehensive subsections with 20+ minutes of expert-level content
- New subsections: Basic Context Rules, Database & API Patterns, Logging & Analytics Traps, The Inference Problem, Multi-System Data Flows, HIPAA Safe Harbor
- Added technical code examples, architectural guidance, and real-world scenarios

**Module 4 Core Principles Expansion:**
- Enhanced with three foundational principles: Minimize Access & Storage, Use Approved Tools Only, De-identify for Development
- Added "What this means in practice" sections with common violations

**UI/UX Improvements:**
- Subsection navigation breadcrumbs
- Fixed subsection visibility logic
- Improved mobile responsiveness

**Build Artifacts:**
* `index.html` (SHA-256): `[Previous v3.0 hash - to be documented]`

### v2.4 — Module 4 Restructure (2025-10-16)
**Content Updates:**
- Expanded Module 4 from 3 to 5 subsections
- Added ~10 new questions (40 → 50 total)
- Standardized CSP terminology

### v2.0.0 — Major Feature Enhancement (2025-09/10-25)
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

**Build Artifacts:**
* `index.html` (SHA-256): `6C074A100093C2A574C4077C21E25A79EBEC6C0A5700BF09F055C82F4C556F88`
* `LICENSE.html` (SHA-256): `C73BCCBD5E7C6B983907F09F9D9CC7795C02AF4FAF406183198907B8BDE7BAD9`

### v1.0.3 — Governance Documentation (2025-07-25)
- Added COPYRIGHT, PROVENANCE.md, THIRD_PARTY_NOTICES.md
- Added DCO (Developer Certificate of Origin)
- Added DMCA counter-notice template

**Build Artifacts:**
* `index.html` (SHA-256): `caea5034e38d9c0264b260d666e7702ddef8f2556bcc3354c8e50d4fed94ab1a`

### v1.0.2 — Footer Fix (2025-08-25)
- Fixed footer placement inside training container

### v1.0.1 — Initial Licensing (2025-07-25)
- Added licensing footer
- Added attribution documentation

### v1.0.0 — Initial Public Release (2025-07-25)
- 8 training modules (Welcome + 6 content modules + Completion)
- 29 interactive questions with immediate feedback
- Module 3 with 6 detailed subsections on context-dependent PHI
- Basic certificate functionality
- Progress tracking with module navigation dots

## Statement of Originality

I (Tom Smolinsky / VITSO) wrote the training content and code. The v2.0.0+ enhancements were developed with AI assistance (Claude AI by Anthropic) for advanced interactive features, state management, and progress saving functionality. Any third-party snippets or assets are listed in `THIRD_PARTY_NOTICES.md` with attribution and license.

## Tooling Notes

- **Editor:** VS Code with Live Server
- **AI Assistance:** Claude AI (Anthropic) for v2.0+ feature development, v3.1 progress saving implementation
- **Testing:** Manual testing across Chrome, Firefox, Safari
- **Deployment:** GitHub Pages
- **No proprietary third-party material included**

## License

- **Code:** MIT License (see `LICENSE.html`)
- **Content:** Creative Commons Attribution 4.0 International (CC BY 4.0)

**Copyright © 2025 Tom Smolinsky / VITSO**
