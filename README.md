# BlinkRead v0.3

BlinkRead is an AI-powered speed reading system built to improve reading speed, focus, and comprehension using Rapid Serial Visual Presentation (RSVP) and intelligent document processing.

---

## 🚀 Overview

BlinkRead transforms traditional reading into a high-efficiency experience by displaying words sequentially with optimized fixation points, reducing eye movement and increasing retention.

---

## ✨ Key Features

### ⚡ RSVP Reading Engine
- Word-by-word display
- Adjustable speed (100–1000 WPM)
- Smooth playback with precise state tracking
- Resume from exact position

---

### 🎯 Fixation Highlighting
- Always highlights 2 letters per word
- Even words → middle two letters  
- Odd words → left-middle + middle  
- Designed for optimal eye fixation and speed

---

### 🧠 AI Document Processing
- Powered by Claude (Anthropic)
- Automatically removes:
  - Headers / footers
  - Page numbers
  - Metadata
- Detects actual start of content
- Outputs clean, structured text

---

### 📄 Dual Reading Modes

#### 1. Parsed Mode
- Clean, distraction-free text
- Optimized for speed reading

#### 2. Original Document Mode
- Displays actual document pages
- Fully synced with reading engine

**Highlighting:**
- 🟡 Yellow → already read  
- 🟢 Green → current word  

Ensures transparency and allows verification of parsed content.

---

### 🎮 Controls
- Play / Pause
- Skip ±10 seconds
- Jump across sections
- Keyboard shortcuts:
  - ↑ / ↓ → adjust speed  
  - Space → play/pause  

---

### 🧪 AI Comprehension Testing
- Generate questions from read content
- Evaluate retention and understanding
- Score-based feedback

---

## 🧠 Tech Stack

- Frontend: Lovable.dev (React-based)
- Backend: Claude API (Anthropic)
- Rendering: Custom RSVP engine
- Storage: Local state (planned cloud sync)

---

## 📂 Status

Current version: **v0.3**

This version introduces:
- AI-powered parsing
- Dual document view
- Improved highlighting logic
- Comprehension testing

---

## ⚠️ Known Limitations

- PDF-to-text mapping may not be perfectly aligned
- Parsing accuracy depends on document format
- Large documents may require processing time

---

## 🔭 Roadmap

- Improve document-word mapping accuracy
- Add EPUB support
- Add user accounts & cloud sync
- Optimize mobile experience

---

## 🎯 Vision

BlinkRead aims to bridge AI and human cognition by creating a reading system that is fast, reliable, and verifiable—without sacrificing comprehension.

---
