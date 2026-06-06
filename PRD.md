# Product Requirements Document (PRD) - Fittplan

## Product Overview
Fittplan is a single-page client portal and utility application designed for LIC (Life Insurance Corporation) agents. It provides planning calculators, documents, marketing posters, training videos, and agent profiles to streamline onboarding, presentations, and sales actions.

## Key Features
1. **Policy Benefit Calculator**:
   - Supports active LIC plans (914, 915, 933, 936, 943, 944, 945, 947, 948, 951).
   - Dynamic terms matching individual plan restrictions.
   - Calculates maturity benefits, bonuses, and estimated premiums.
   - Exports professional PDF summary sheets for clients.
2. **Need Analysis Coverage Planner**:
   - Computes suggested life cover based on income, liabilities, goals, and buffers.
   - Generates an onboarding checklist for clients.
3. **Magic Poster Creator**:
   - Renders SVG-based marketing banners.
   - Allows agents to customize headlines, tags, names, contact numbers, and themes (Ocean Blue, Sunset Gold, Emerald Green).
   - Supports high-resolution SVG downloads.
4. **Form & Document Center**:
   - Lists and allows download of official proposal forms and plan brochures.
5. **Interactive Media & Training Portal**:
   - Plays concept, help, and plan videos inside the app using a custom YouTube player and local video player overlay.
6. **Agent Profile & Backup Hub**:
   - Saves contact details and a branded profile picture.
   - Saves calculation histories and offers full import/export of history using JSON files.
7. **Utility Suite**:
   - Late fee revival estimator.
   - Age calculator.
   - Income tax estimator.
   - Image utilities (Image to PDF, Image compression).

## Technical Priorities & Roadmap
- Make the main policy calculator more realistic by dynamically populating valid policy terms based on the selected plan.
- Update premium calculations to use correct premium payment terms (PPT) for different plans.
- Modernize the styling and user experience to match modern web standards.
- Add validation logic to ensure correct inputs (Sum Assured minimums/maximums, age limits per plan).
