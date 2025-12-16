# Merch Inc Model Call

A web platform to streamline the **model call process** for Merch Inc.’s biannual fashion shows.  

This project replaces the current messy, manual process (shared laptops, forgotten numbers, confusing picks) with a **simple, transparent, and organized system**.

---

## Overview
Every semester, Merch Inc. hosts a fashion show where designers select models.  
Currently, the process is slowed down by:
- Manual sign-ups on a few laptops
- Models forgetting their assigned numbers
- Designers struggling to track who is available vs. already picked

**This project solves those problems by providing:**
- A sign-up portal for models and designers
- Profiles with photos and details
- A transparent selection system with real-time updates
- An admin dashboard to manage stages and export results

---

## Demo (Figma Prototype)
[View Figma Demo](https://www.figma.com/make/u88hRbZ6gWMlwZMvsHsQeu/Fashion-Show-Model-Call-Wireframes?node-id=0-1&t=NDNBv05NmcmsxZCM-1)

---

## Tech Stack (Planned)
- **Frontend:** React + Next.js  
- **Styling:** Tailwind CSS  
- **Backend:** Supabase (Auth, Database, Storage, Realtime)  
- **Deployment:** TBD  

---

## Roadmap
1. Build frontend mock with **Next.js + Tailwind** using fake data  
2. Integrate Supabase for auth and database storage  
3. Add real-time updates and selection logic  
4. Deploy demo on Vercel  
5. Test with Merch Inc. club members
6. Pilot test for the next Merch Inc. model call  

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
