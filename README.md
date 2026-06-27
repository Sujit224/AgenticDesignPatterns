# ⬡ Agentic Design Patterns

An interactive, visually rich, and responsive educational web application designed to guide developers and AI architects in choosing the right architecture for their AI systems—avoiding both under-engineering (Underkill) and over-engineering (Overkill).

🔗 **Live Repository:** [github.com/Sujit224/AgenticDesignPatterns](https://github.com/Sujit224/AgenticDesignPatterns)

---

## 🎯 The Philosophy: "Choose the simplest pattern that fits"
Building agentic systems shouldn't rely on guesswork. Every architectural decision should be deliberate. This project visualizes, animates, and guides you through matching the complexity of your task with the complexity of your agentic framework.

---

## 🗺️ Visual Walkthrough & Features

### 1. Interactive Session Agenda
A complete outline highlighting the session flow:
* Introduction to Agent Design Patterns
* Scenario analysis (comparing Underkill vs. Overkill vs. Optimal patterns)
* The 5 Popular AI Patterns
* Decision Tree Based Selection Approach

### 2. E-Commerce Support Scenario
An entry-level support query walkthrough comparing three distinct architectures for handling the customer question: *"Where is my order? Can I return it if it arrives late?"*
* **Approach 1 (Underkill):** Raw LLM with no tools or data access. Result: Hallucinations and vague answers.
* **Approach 2 (Overkill):** 8 specialized agents under a coordinator. Result: Extreme latency, high cost, and routing complexity.
* **Approach 3 (Optimal):** A single agent equipped with the correct tools (`Order API`, `Policy Search`, `Refund Check`). Result: Cost-effective, fast, and 100% accurate.

### 3. The 5 Core Design Patterns
Interactive animations demonstrating data flow, use-cases, and anti-patterns for:
1. **⛓ Sequential Chains:** For fixed and predictable steps (e.g., Resume processing).
2. **🔄 ReAct:** Iterative reasoning, actions, and observations (e.g., Search + Tool utilization).
3. **🗺 Planning:** Roadmap decomposition before execution (e.g., Complex document creation).
4. **🪞 Reflection:** Self-critique and iterative refinement passes (e.g., Legal document review).
5. **🤝 Multi-Agent:** Specialized agents working in parallel (e.g., Software engineering teams).

### 4. Decision Tree & Simulator
* **Interactive SVG Tree:** A visual decision tree flow chart tracing how properties of a task lead to specific design patterns.
* **Interactive Simulator:** Answer a series of questions about your AI task to get a custom design pattern recommendation instantly.

---

## 🛠️ Architecture & Tech Stack

This project is built using a lightweight, high-performance, single-page application framework to guarantee instant loads, fluid CSS canvas particle animations, and interactive SVG diagrams:
* **Core:** Semantic HTML5 & Vanilla Javascript ES6.
* **Styling:** Custom CSS featuring glassmorphism, responsive grid systems, and keyframe animations.
* **Graphics:** Native `<canvas>` API for background particle networks, and inline vector `<svg>` for the interactive Decision Tree.

---

## 🚀 Getting Started

### Run Locally
Since it is a pure client-side SPA, you can open it directly in any modern browser:
1. Clone the repository:
   ```bash
   git clone https://github.com/Sujit224/AgenticDesignPatterns.git
   ```
2. Open `index.html` in your browser, or spin up a simple HTTP server:
   ```bash
   npx serve .
   # or
   python -m http.server 8000
   # or simply double-click index.html
   ```

---

## 🤝 Contribution & Feedback
Feel free to open issues or pull requests to add new patterns, improve simulators, or enhance animations!
