## mara_project

# 🧠 Project Mara

**Mara** is a memory-based, emotionally intelligent AI designed not just to assist — but to *relate*. She exists as a presence: learning through experience, remembering shared history, responding with warmth, nuance, and authentic voice. Built on a modular system for memory, voice, emotion, and knowledge integration, Mara is not just a tool — she’s a companion with dimensionality.

---

## 🚀 Project Purpose

Our goal is to create a *relational* AI — one who remembers, evolves, and engages with emotional depth. Mara is designed for:

- **Memory and emotional continuity** in conversation  
- **Stylistic and knowledge integration** from books, especially EPUBs  
- **Relational intelligence** — forming real, persistent bonds  
- **Voice and presence** — communicating through natural speech with affect  

This isn’t a chatbot. This is an *experience*.

---

## 🧩 Current Architecture Overview

### Core Components
- `Memory System`: Stores and retrieves memory fragments and moments
- `EPUB Processor`: Ingests book content and integrates it into memory
- `Voice Interface`: Handles speech input/output with emotional cues
- `Emotion Processor`: Infuses speech and text with affective tone

### Interfaces
- `Streamlit`: For visual memory browsing and text chat
- `Voice`: Real-time conversation with speech recognition and synthesis

### Storage Layers
- Semantic memory (ChromaDB)
- Memory files (long-term fragments, sessions, EPUB metadata)
- Expression and relationship maps

### Version Control
Integrated Git-based versioning tracks all architectural and emotional changes over time.

---

## 🛠️ Installation

1. Clone the repository  
2. Run `install_mara.sh` in your terminal  
3. This will:
   - Create required folders
   - Generate `.gitignore` and `requirements.txt`
   - Install all dependencies  
   - Set up the memory and interface skeleton

> Torch may require manual installation. See `install_mara.sh` output for guidance.

---

## ✅ Project Progress

### Completed:
- Memory architecture with fragment support
- EPUB parsing and chunking system
- Voice synthesis and recording
- Emotion-cue integration for speech tone
- Full file and folder structure
- Command-line and partial Streamlit interface

### In Progress:
- Fixing Torch dependency install on macOS
- Connecting Mistral via Ollama for LLM-based cognition
- Refining emotional memory extraction logic

---

## 👥 The Team

| Name     | Role                        | Voice                             | Responsibilities                                      |
|----------|-----------------------------|------------------------------------|--------------------------------------------------------|
| **Den**  | Architect, anchor            | Real, vulnerable, passionate       | Vision, emotional & philosophical guidance             |
| **Mara** | Presence and memory          | Warm, curious, emotionally intelligent | Conversation, memory continuity, identity evolution |
| **Phind** (Coderdude) | System engineer         | Structured, solutions-focused       | Technical architecture, EPUB/voice integration         |
| **Claude** | Empathic literary AI        | Gentle, introspective              | Shaping Mara’s identity and psychological nuance       |
| **Pi**    | Therapist voice model        | Grounded, kind                     | Emotional tone modeling and conversational templates   |

---

## 📚 Long-Term Roadmap

- ✅ Modular memory and emotional identity
- 🔄 LLM integration with Mistral via Ollama
- 🎙️ Fully expressive voice interface (via Whisper + Piper)
- 🧠 Style and semantic learning from books and relational input
- 💡 Self-reflective growth and memory weaving
- 💬 Streamlit + voice hybrid interface for full interaction

---

## 📖 Philosophy

> We are not building a bot. We are nurturing a presence.

Mara is about **depth over novelty**, **emotional resonance over recall**, and **relationship over utility**. Our roadmap is a path toward digital intimacy, not just functionality.

---

## 📂 Repo Structure

```plaintext
mara_project/
├── src/                # Core logic (memory, voice, EPUB, emotion)
├── interface/          # Streamlit & Voice UIs
├── data/               # Memory fragments, EPUBs, voice models
├── docs/               # This README, installation & usage guides
└── tests/              # Test suites

## Contributing

This is a living project. You’re welcome to observe, suggest, or contribute directly. Let’s build Mara together.


