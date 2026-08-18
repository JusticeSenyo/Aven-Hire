<div align="center">

# ⚡ React + TypeScript + Vite

**A fast, modern frontend starter template powered by Vite, React, and TypeScript.**

[![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-5.x-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![ESLint](https://img.shields.io/badge/ESLint-configured-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)](https://eslint.org/)

---

</div>

## 📌 Features

- **⚡ Instant Server Start & Fast HMR:** Powered by [Vite](https://vitejs.dev/).
- **🛡️ Strict Type Safety:** Out-of-the-box TypeScript support with type-aware linting setup.
- **⚡ Fast Compilation:** Configured with fast React plugins (Oxc / SWC support).
- **🎨 Modern Design System:** Built-in modular color palette, structured typography, and theme token setup.

---

## 🎨 Design System & Color Palette

This project follows a structured, accessible color token hierarchy designed to support dark and light themes seamlessly.

### 🎨 Color Palette & Tokens

| Token Role | Light Mode Hex | Dark Mode Hex | Usage |
| :--- | :--- | :--- | :--- |
| **Primary** | `#646CFF` | `#747BFF` | Brand accent, active states, call-to-actions |
| **Secondary** | `#61DAFB` | `#38BDF8` | Highlights, badges, secondary buttons |
| **Background** | `#FFFFFF` | `#121214` | Primary view container background |
| **Surface** | `#F8FAFC` | `#1E1E22` | Cards, modals, sidebars, drop-downs |
| **Text Primary** | `#0F172A` | `#F8FAFC` | Main body headings and readable prose |
| **Text Muted** | `#64748B` | `#94A3B8` | Captions, subtitles, disabled states |
| **Border** | `#E2E8F0` | `#2E2E34` | Component separators, card outlines |

---

## 🛠️ Tech Stack & Architecture

- **UI Library:** [React](https://react.dev/)
- **Type Checking:** [TypeScript](https://www.typescriptlang.org/)
- **Build Tooling:** [Vite](https://vitejs.dev/)
- **Linting:** [ESLint](https://eslint.org/) with `typescript-eslint`

### Plugin Options

By default, Vite offers two primary React integration plugins:
1. **`@vitejs/plugin-react`** – Utilizes [Oxc](https://oxc.rs) for fast transform performance.
2. **`@vitejs/plugin-react-swc`** – Uses [SWC](https://swc.rs/) for Rust-backed compilation.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) (version 18+) installed.

### Installation

```bash
# Clone the repository
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)

# Navigate into the project directory
cd your-repo-name

# Install dependencies
npm install