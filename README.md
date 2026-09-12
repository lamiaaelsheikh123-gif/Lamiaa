# 🧠 Memento AI — Cognitive Training Platform

> **Train Your Mind. Support Your Memories.**

An adaptive cognitive training platform powered by AI. Users are assessed across 7 cognitive skills, receive a personalized training plan, and progress through adaptive exercises that grow with their abilities.

---

## 📑 Table of Contents

1. [Overview](#overview)
2. [Tech Stack](#tech-stack)
3. [Project Structure](#project-structure)
4. [Pages List](#pages-list)
5. [User Flow](#user-flow)
6. [Design System](#design-system)
7. [localStorage Keys](#localstorage-keys)
8. [Data Flow](#data-flow)
9. [i18n (Internationalization)](#i18n)
10. [Flutter Migration Notes](#flutter-migration-notes)
11. [How to Run](#how-to-run)

---

## 📖 Overview

**Memento AI** is a web-based prototype for an AI-powered cognitive training platform. The design targets **mobile-first (375×812)** and is fully ready to be ported to **Flutter**.

### Key Concepts

- **7 Cognitive Skills**: Memory, Attention, Processing Speed, Problem Solving, Visual Skills, Language, Numerical
- **Adaptive Difficulty**: Exercises adjust to user performance
- **AI-Generated Plans**: Personalized training priorities
- **Parent Mode**: Separate dashboard for child accounts
- **Bilingual**: Full Arabic + English support with RTL

### Target Users

- **Adults** (18+) — Cognitive wellness and memory support
- **Children** (6-14) — Cognitive development via parent-managed accounts

---

## 🛠 Tech Stack

This is a **pure frontend prototype** — no backend needed.

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (Custom Properties, Flexbox, Grid) |
| Logic | Vanilla JavaScript (ES6+) |
| State | `localStorage` (persistent) |
| Icons | Inline SVG (Lucide-style) |
| Fonts | Google Fonts (Poppins + Cairo) |
| Charts | Custom SVG |

> ⚠️ **No frameworks** (React, Vue, etc.) — intentionally simple for easy porting to Flutter.

---

## 📁 Project Structure
