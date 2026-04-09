# Project Name
ClueConnect - Crime Investigation Simulator
## Team Name
PASTA

## Team Members
- Parth Badgire (GitHub: @parthbadgire-code)
- Advait Deshpande (GitHub: @username)
- Samruddhi More (GitHub: @username)
- Aary Garge (GitHub: @username)
- Tisha Sarkar (GitHub: @username) — optional

## Idea Chosen
Custom :  Interactive Crime Investigation Simulator
## Problem Statement
Traditional crime-solving games are either too simplistic (simple multiple choice) or require
heavy narrative. Users crave interactive, detective-like experiences where they feel
genuinely involved in solving the mystery.

## Tech Stack
- React
- Supabase (Postgresql)

## Implementation Details
1. Case Overview Screen

Crime story + key details
Timer countdown (15–20 minutes per case)
Progress indicator (clues collected, suspects analyzed)
"Begin Investigation" CTA
2. Case Files / Evidence Hub

Crime Scene Photos (carousel with labeled evidence)
Timeline (interactive, chronological events)

Evidence List (searchable, with descriptions)
Suspect Profiles (motive, alibi, timeline conflicts)
Clue discovery triggers (unlock new info as you investigate)
3. Interactive Evidence Board

Drag-and-drop canvas to connect evidence
Connection lines between related clues
Color-coded categories (weapon, location, motive, alibi)
Notes section to annotate findings
Real-time visual representation of detective work
4. Suspect Analysis Panel

Individual suspect deep-dive
View alibi vs. timeline conflicts
Highlight contradictions automatically
Track motive, opportunity, means
5. Final Decision

"Accuse" button locks in verdict
Reveals culprit + explanation
Score calculation:
Base Score: 100
-10 per minute over time
+15 per correct clue connection
-20 for wrong accusation
Comparison: "You solved in X minutes! "
Show correct answer + reasoning
6. Results Screen
Verdict Reveal (correct/incorrect)
Score & Ranking
Case Summary (what you found, what you missed)
Share Results (screenshot or social)
Play Again / Next Case

## How to Run Locally
Clone the Repo
then run
npm i
npm run dev


## Live Demo
https://clueconnect.vercel.app/

## Screenshots / Demo
(Include a demo video or screenshots showcasing your app's features)
