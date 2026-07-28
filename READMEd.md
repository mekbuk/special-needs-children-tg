# 🗣️ Speech & Sensory Therapy Orchestrator

## Overview
This repository contains the core application algorithm designed to facilitate structured, interactive speech and sensory therapy sessions. By translating technical sequence diagrams—originally mapped in Azerbaijani—into English-driven executable logic, the application orchestrates a seamless workflow between the clinician (Doctor) and the patient (Child). 

The system manages timed states, hardware integrations (such as LED boards and lighting sequences), and specific cognitive exercises to guide users through introductory phonetics and sensory grounding.

## Core Features
*   **Algorithmic State Management:** Strictly timed progression through distinct therapeutic phases (e.g., Sensor Activation, Letter Introduction, Calming Down).
*   **Hardware Integration Routing:** Built-in logic for triggering external hardware responses, including specific red LED light sequences and interactive smart-board displays.
*   **Bilingual Workflow Support:** Translates localized clinical instructions into a standardized, English-executable prompt sequence for broader application compatibility.
*   **Interactive Event Handling:** Maps specific child inputs (e.g., touching the correct word on an LED board) to pre-defined cognitive game reactions and scoring.

## Session Workflow Architecture
The application logic is currently modeled around the **1st Week - Day 1** curriculum, breaking down a 45-minute session into the following programmatic states:
1.  **Sensor Activation (5m):** LED light initialization and initial vocalization prompts.
2.  **Feeling the Sound (10m):** Tactile and mirror-based feedback loops.
3.  **Letter Introduction (5m):** Visual display routing and word association.
4.  **LED Games (15m):** Three distinct interactive matching and location games.
5.  **Cognitive Game (5m):** Auditory recognition and reaction triggering.
6.  **Calming Down (5m):** Environment softening and breathing pacing.
