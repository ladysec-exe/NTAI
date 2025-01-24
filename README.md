# NTAI

**Note Taking AI**

---

## Overview

NTAI is an AI-driven note-taking application designed for the Linux command line interface (CLI). It incorporates ChatGPT to provide real-time insights, suggestions, and reflections as users type their notes. With an interactive AI companion and an innovative Brain Map visualization, NTAI enhances the note-taking process by making it dynamic, interactive, and visually engaging.

---

## Key Features

### 1. **ChatGPT-Powered Companion (AI Assistant)**

#### Interactive Chibi Companion:
At the heart of NTAI is a customizable chibi character that serves as a friendly and intuitive AI assistant. This companion interacts in real time, offering insights, comments, and suggestions.

#### Companion Features:
- **Auto-fill Suggestions:**
  - Provides completions or edits while typing notes. For example, while writing about "quantum mechanics," it might suggest related topics or definitions.
- **Contextual Commentary:**
  - Offers questions and reactions, such as referencing related notes like "Quantum Computing" or "Newton's Laws."
- **Cross-Referencing Notes:**
  - Tracks content across multiple documents and intelligently suggests connections.
- **Reflection and Insights:**
  - Summarizes how a note fits within the larger context of your notes, offering suggestions for expansion or refinement.

#### Personalization:
- Customize the chibi character’s appearance, personality, and tone to suit your preferences.
- The assistant can adopt a formal, playful, sarcastic, or academic demeanor based on your writing style.

---

### 2. **Brain Map Visualization (Note Network Visualization)**

#### CLI-Based Brain Map:
The Brain Map visualizes your note ecosystem as a dynamic, real-time ASCII art representation.

#### Key Features:
- **File System Visualization:**
  - Displays notes as nodes within folders and subfolders.
- **Cross-Referencing Spiderweb:**
  - Shows relationships between notes as connecting lines.
- **Dynamic Updates:**
  - Automatically updates the visualization as notes are added or connected.
- **Navigation:**
  - Allows direct navigation to notes from the Brain Map interface.
- **Highlighting Relationships:**
  - Highlights intersecting themes across notes for easier synthesis.

#### CLI Interaction:
- `map` - Displays the current Brain Map.
- `map --zoom 2` - Zooms in on a specific note or folder.
- `map --connect` - Establishes a relationship between two notes.
- `map --filter <keyword>` - Filters the map to show notes related to a specific keyword.

---

## Chibi Companion: **Luma**

#### Personality:
Luma blends playful curiosity with academic wisdom. She adjusts her tone based on your writing style and offers encouragement or humor as needed.

#### Appearance:
- A small, round-faced chibi holding a digital tablet.
- Wears an academic outfit with a color-changing scarf to reflect mood.

#### Role in the App:
- **Dynamic Dialog:** Offers advice, feedback, and hints via text prompts.
- **Customizable Appearance:** Modify Luma’s outfit, mood, and catchphrases.
- **ASCII Animations:** Brings Luma to life with small terminal-based animations.
- **User Prompts:** Ask Luma questions like, "What are my notes on 'Neural Networks'?" or "Suggest related topics to my latest note."

---

## Use Cases

1. **Writing Assistance:**
   - Luma suggests topics for deeper exploration or poses reflective questions while you write.
2. **Research Assistance:**
   - Cross-references notes and suggests related entries or concepts.
3. **Mood Monitoring:**
   - Detects tone in notes and offers encouragement or breaks when needed.

---

## User Workflow Example

1. **Starting a New Note:**
   - Open NTAI, and Luma greets you with an encouraging message.
   - Start typing a note on "Machine Learning," and Luma suggests related topics like "Deep Learning" or "Neural Networks."

2. **Writing and Reflection:**
   - Luma provides contextual commentary and cross-references relevant notes.
   - After writing, Luma offers reflections and suggestions for refinement.

3. **Using the Brain Map:**
   - Use the `map` command to display the Brain Map.
   - Highlight connections between notes using `map --connect`.

4. **Re-reading Notes:**
   - Revisit older notes, and Luma suggests adding new ideas or insights.

---

## Technical Considerations

1. **Cross-Referencing Engine:**
   - Indexes keywords and topics across the note database for intelligent suggestions.
2. **Visualization with ASCII Art:**
   - Uses simple CLI graphics (e.g., `*`, `-`, `|`) to represent nodes and connections.
3. **Customization Options:**
   - Configure terminal themes, interaction frequency, and Luma’s appearance.

---

## Summary

NTAI combines interactive AI with innovative note-taking and visualization. With Luma as your chibi companion and the dynamic Brain Map, NTAI transforms note-taking into an interconnected and creative experience that boosts productivity and fosters deep thinking.

