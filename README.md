# ClearMark – AI-Assisted OCR Verification for Children's Handwriting

CSEN 909 Human Computer Interaction, Winter 2026 – Team Ziad – Milestone 3 coded front-end (bonus).

A clickable prototype of the full workflow with simulated (hard-coded) OCR output, grades and feedback:
student uploads exam → teacher verifies extracted text with the OCR confidence heatmap → teacher confirms
grade and red flag → student sees results. Includes an optional parent view.

## Links
- Live prototype: https://mohamed1karim.github.io/clearmark/
- Video walkthrough: https://mohamed1karim.github.io/clearmark/walkthrough.mp4

## Run locally
1. Download or clone this repository.
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari). No install or build step is needed.

## Deploy (GitHub Pages)
Repository → Settings → Pages → Source: `main` branch, `/ (root)` → Save. The site appears at
https://mohamed1karim.github.io/clearmark/.

## Demo walkthrough
1. **Student** → Upload a new exam → Next → Take photo (first photo is blurry on purpose) → Retake → Take photo → Submit.
2. **Teacher** → open Youssef's row → Jump to next uncertain → Q3 (red): Ask student.
3. **Student** → bell → open the message → type 1 over 4 (or draw it) → Send to teacher.
4. **Teacher** → Verify text → Q3 → Use this answer → Jump to next uncertain → Accept Q4 → Confirm text.
5. **Teacher** → confirm or dismiss the red flag, adjust marks if needed → Publish to Youssef.
6. **Student** → Exams tab to see grade, feedback, weak spot and practice. Use EN | DE to switch language.
7. **Parent** → see the grade, progress and confirmed red flag.

Use **Log out** (top right) to return to the role selection screen and switch between Student, Teacher and Parent. Reload the page to start over.
