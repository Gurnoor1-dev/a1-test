# Goethe A1 Exam Platform

A browser-based practice and assessment platform for the Goethe-Zertifikat A1 / Start Deutsch 1 sample exam.

## Run locally
Open `index.html` in a modern browser, or deploy this repository as a static site on Vercel. No build command, database, account, API key, or external backend is required.

## Included
- Four exam areas: Hören (20 min), Lesen (25 min), Schreiben (20 min), Sprechen (15 min).
- Candidate name and optional email; timed exam sections; MCQ, written responses, and microphone recordings.
- Password-protected local admin area to add questions, upload listening audio, review submissions, play recordings, and manually award points.
- Automatic MCQ scoring, backup export/import (including audio), and local browser persistence.

## Important storage limitation
All data is stored in the current browser profile using localStorage and IndexedDB. It does not sync between devices or browsers. Export a backup regularly and import it on another device if needed. The admin password is a local access gate, not server-side authentication; do not use this for sensitive or high-stakes examinations.

## Source exam coverage
The supplied sample PDF specifies the exam structure and point/time allocation, but it does not include the listening audio files. The platform deliberately leaves Hören and Lesen question banks empty rather than inventing source questions or audio. An administrator must enter the original questions and upload the corresponding audio before conducting a full mock exam.
