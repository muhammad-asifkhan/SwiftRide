# Project ideas pool — for selection

Use this document to pick one idea for a build (e.g. lab exam, portfolio demo, or hackathon).  
**Note:** If you have a **~2 hour in-exam build** with only pre-setup allowed, favor ideas with **one main integration** (usually one API or one clear UI loop). Heavier items are better as longer projects.

---

## Category 1 — AI / theatrical / CV

### 1. AI Courtroom — Legal Argument Battle Simulator

**Stack:** Next.js + Tailwind + OpenAI/Gemini API  

**What it is:**  
User describes a legal case/scenario. AI generates two lawyers — prosecution and defense. They argue back and forth in real-time (streamed responses). AI judge gives final verdict with reasoning. Courtroom UI with chat-style argument flow.

**Why it stands out:** Theatrical, interactive, unexpected in a demo.

---

### 2. DeepFake Detective — Image Authenticity Analyzer

**Stack:** Flask/FastAPI + React + pre-trained CNN (e.g. EfficientNet)  

**What it is:**  
Upload a face photo. Model analyzes for deepfake artifacts (pre-trained model or error-level analysis). Heatmap overlay on suspicious regions. Confidence score + breakdown. Side panel: educational content on how deepfakes work.

**Why it stands out:** Cybersecurity + computer vision + timely topic.

---

### 3. MoodMirror — Real-Time Emotion Detection Webcam App

**Stack:** Python + OpenCV + FER/DeepFace + Streamlit or Electron  

**What it is:**  
Opens webcam. Real-time face detection + emotion labels (happy, sad, angry, surprised, neutral). Live emotion timeline graph. Optional “emotion report” after a fixed window (e.g. 60s). Optional: music matching mood.

**Why it stands out:** Real-time camera + AI = strong live demo.

---

## Category 2 — Real web apps (not dashboards)

### 4. ConfessIt — Anonymous University Confession Wall

**Stack:** Next.js + Supabase (or Firebase) + Tailwind  

**What it is:**  
Anonymous confessions in real time. Upvote/downvote. AI moderation (toxicity filter) before posting. Trending / “hottest today,” tags (funny, sad, romantic, academic). Masonry card layout with motion.

**Why it stands out:** Social product + AI moderation + polished UI.

---

### 5. CodeDuel — Real-Time 1v1 Coding Battle

**Stack:** Next.js + Socket.io + Monaco Editor + Judge0 API  

**What it is:**  
Same problem for two players. Split screen, Monaco editors. Runs against test cases via Judge0. First to pass all wins. Timer + live progress.

**Why it stands out:** Multiplayer + code execution feels advanced.

---

### 6. GhostChat — Chat With Any Historical Figure

**Stack:** Next.js + Tailwind + OpenAI/Gemini API  

**What it is:**  
Pick a historical figure. AI adopts persona, speaking style, and era-appropriate knowledge. iMessage-style chat. Sidebar: bio, timeline, achievements. Can switch figures mid-chat.

**Why it stands out:** Simple to scope; very engaging to demo.

---

## Category 3 — Desktop / utility

### 7. ScreenSage — AI Desktop Assistant That Sees Your Screen

**Stack:** Python + PyAutoGUI + Pillow + Gemini Vision + Tkinter/CustomTkinter  

**What it is:**  
Floating widget. Screenshot on demand → vision model: “What am I looking at?” / explain errors / summarize on-screen text. Conversation history.

**Why it stands out:** “It sees my screen” — strong wow factor.

---

### 8. TypeFury — Typing Speed Test with AI-Generated Passages

**Stack:** React + Tailwind (or Electron)  

**What it is:**  
AI generates contextual passages by topic. WPM, accuracy, per-character feedback. Leaderboard (localStorage or Supabase). Heat map of most-missed keys. Optional race/ghost mode.

**Why it stands out:** Polished, gamified, satisfying UX.

---

## Category 4 — Mobile

### 9. PlantDoc — Snap a Plant, Get Diagnosis

**Stack:** React Native (Expo) + TensorFlow Lite (plant disease model)  

**What it is:**  
Photo of leaf → on-device model: healthy vs diseases. Info, severity, care tips. History of scans. Nature-themed UI.

**Why it stands out:** Camera + on-device ML + practical use.

---

### 10. SafeWalk — Women Safety App with Shake Detection

**Stack:** React Native (Expo) + Expo Sensors + Supabase  

**What it is:**  
Shake to send emergency SMS with GPS to contacts. Fake incoming call. Live location sharing. Danger-zone style alerts (if you add data). SOS with countdown.

**Why it stands out:** Social impact + sensors + real utility.

---

## Category 5 — Creative / unexpected

### 11. DreamDecoder — AI Dream Journal & Interpreter

**Stack:** Next.js + Supabase + OpenAI API + Tailwind  

**What it is:**  
Write a dream → themes, symbols, tone, possible meanings. Optional generated image (DALL·E / Stability). Calendar + stats over time. Dreamy purple/dark UI.

**Why it stands out:** Unusual concept, memorable branding.

---

### 12. BeatCraft — AI Music Loop Generator

**Stack:** Next.js + Tone.js + OpenAI API  

**What it is:**  
Describe a mood → AI outputs structured music data (drums, chords, tempo). Tone.js plays audio in browser. Waveform / beat visuals. Tweaks: tempo, instruments, pattern. Export loop.

**Why it stands out:** Actual playable music in the browser.

---

## Additional suggestions (not in the numbered list above)

Same spirit as GhostChat / single-flow tools: **prefab UI + one main integration** works best under tight time limits.

- **A — PantryChef:** Ingredients in → structured recipe (steps, substitutions).
- **B — ExplainThis:** Paste SQL, regex, or an error/stack trace → plain explanation + “try next.”
- **C — StudyBurst:** Paste notes → flashcards + mini quiz + score.
- **D — MicroCourt:** One-sentence claim → For / Against / Judge in three panels (lighter than full AI Courtroom).
- **E — Diffscribe:** Paste `git diff` → conventional commit + short PR description.
- **F — CaptionClash:** Upload photo → two “rival” captions (vision model); user picks winner.
- **G — PolicySim:** Rule + scenario → structured “what would be argued” (with not-legal-advice disclaimer).

---

## Quick selection rubric (optional)

When choosing, you can score each idea 1–5 on:

- **Time fit** — Can you finish the *required* demo path in your deadline?
- **Reliability** — Few moving parts (one API, no multiplayer, no device-only quirks)?
- **Clarity** — Will a non-expert understand the demo in under a minute?
- **Wow** — Memorable or distinctive?
- **Your strength** — Stack you already know?

---

*Compiled for idea selection. Original 12 categories supplied by project owner; rows A–G are additional options suggested for short-build robustness.*
