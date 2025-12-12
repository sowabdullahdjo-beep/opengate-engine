# OpenGate Engine — Product Vision

OpenGate is an AI-native game engine built on top of the Godot Engine (MIT license).
Its purpose is to drastically reduce the technical barrier to game creation by embedding AI directly into the editor.

This document defines what OpenGate IS, what it WILL build, and what it WILL NOT build.

---

## Core Philosophy

- Do not rebuild a game engine from scratch
- Use Godot as a stable, proven foundation
- Treat AI as a first-class feature inside the editor
- Optimize for clarity, speed, and accessibility
- Prioritize solo creators and non-developers

---

## Target Users

- Beginners who want to create games without deep coding knowledge
- Indie developers who want to move faster
- Designers and artists who need help with logic and structure
- Small teams prototyping ideas quickly

---

## Phase 1 — MVP Scope

### 1. AI Chat Panel (Editor Integrated)
- Docked panel inside the editor
- Natural-language interaction with the project
- Context-aware (current file, scene, node selection)
- Central entry point for all AI features

### 2. AI Coding Assistant
- Explain selected code
- Fix script errors
- Rewrite logic from instructions
- Generate scripts from natural language
- Modify multiple files when required

Supported:
- GDScript
- C#
- Basic shaders

### 3. AI Scene Generator
- User describes a scene in natural language
- Engine generates:
  - Scene tree
  - Nodes
  - Camera
  - Lighting
  - Basic objects or player
- Uses placeholders for rapid prototyping

### 4. AI Asset Generation (MVP)
- Generate simple textures, sprites, and UI elements
- Automatically import assets into the project
- Attach assets to selected nodes

### 5. AI Debugger
- Read error logs and crashes
- Explain issues in simple language
- Suggest or apply fixes

---

## Explicit Non-Goals (Important)

- No custom rendering engine
- No rewrite of Godot architecture
- No AAA realism generation
- No multiplayer backend in Phase 1
- No attempt to outperform Unreal technically

---

## Long-Term Vision

OpenGate becomes the most accessible AI-powered game creation environment.
Users can go from idea → playable prototype with minimal friction.

AI handles complexity.
Humans focus on creativity.

---

## Development Rule

If a feature:
- Increases complexity
- Breaks Godot compatibility
- Confuses beginners

Then it should NOT be added.

Simplicity > power.
