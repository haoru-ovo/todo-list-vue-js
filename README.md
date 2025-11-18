# Vue Todo List

A simple Todo List application built with **Vue 3 + Vite**, designed for learning the basics of Vue, including component structure, reactivity, event handling, and dynamic styling.

This project includes full step-by-step learning notes (uploaded as `todo_list_vue.pdf`), which explains every implementation stage.

---

## Features

- Add new todo items  
- Delete todo items  
- Mark items as completed  
- Prevent empty input  
- Dynamically rendered list  
- Reactive state using `ref()`  
- List rendering with `v-for`  
- Two-way binding via `v-model`  
- Conditional styling via `:class`  
- Scoped component CSS + global gradient background

---

## Tech Stack

- Vue 3 (Composition API)
- Vite
- JavaScript
- CSS (Scoped & Global)

---

## Project Structure

src/
│── App.vue          # Main component
│── main.js          # App entry
│── style.css        # Global styles (gradient background)
index.html           # Root mount point


## Run Locally

npm install
npm run dev

**Default development server URL:**   http://localhost:5173/

## Key Learning Points (from notes)

- Using `<script setup>` syntax
- Creating reactive variables with `ref()`
- Updating reactive arrays
- Rendering lists with `v-for`
- Using `v-model` for two-way binding
- Dynamic styling via `:class`
- `.value` access for reactive refs
- Mixing scoped and global CSS
