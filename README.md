# 🛠️ Workflow Wizard Manager

### A Dynamic Multi-Configuration Workflow Wizard System

The **Workflow Wizard Manager** is a flexible wizard-based system that allows users to create, configure, and manage multiple workflows, each containing multiple levels and customizable questions. It also supports capturing **wizard-level metadata**, such as terms acceptance, contact emails, and organizational details.

---

## 🚀 Features

✅ Wizard-driven page navigation for initial setup  
✅ Support for multiple independent configurations within a single workflow  
✅ Level-wise and question-wise data capture  
✅ Dynamic UI rendering from JSON definitions  
✅ Persistent storage using `localStorage` (can be extended to API or database)  
✅ Pre-configuration data capture (Terms & Conditions, Breakglass emails, etc.)

---

## 🏗️ Project Structure

```text
.
├── app.js             // Core logic for page flow, navigation, and configuration control
├── renderer.js        // Dynamic HTML rendering for sections, fields, and navigation
├── stateManager.js    // Central data storage, state management, and save logic
├── sampleWorkflow.json // Sample workflow definition (JSON-based)
└── README.md          // Project documentation

