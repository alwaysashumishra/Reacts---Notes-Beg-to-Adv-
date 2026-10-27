# 📘 React.js Notes — Hinglish

A collection of my personal **React.js learning and revision notes**, written in simple **Hinglish** with practical explanations, examples, and code snippets.

These notes are created for **React.js learning, revision, frontend development, interviews, and technical assessments**.

---

## 📚 Topics Covered

### 🟢 JavaScript Fundamentals for React

Before starting React, these notes cover some important JavaScript concepts that are frequently used in React development.

- Mutable vs Immutable Data
- Immutable State Updates
- Spread Operator (`...`)
- Object Copying
- Array Copying
- Object Destructuring
- Nested Object Destructuring
- Array Destructuring
- Import & Export
- Default Export
- Named Export
- Arrow Functions
- Single & Multiple Parameters
- Implicit Return
- Returning Objects from Arrow Functions
- `map()` Method
- `filter()` Method

---

## ⚛️ React Fundamentals

Introduction to the basic concepts and working of React.

- What is React?
- Why React?
- React Library
- Virtual DOM
- Components
- Component-Based Architecture
- Component Reusability
- Functional Components
- Component Structure
- `App.jsx`
- `main.jsx`
- React Component Flow
- `rafce` / `rfce`
- Components Folder Structure

---

## 🧩 JSX

Understanding JSX and how JavaScript works inside React UI.

- What is JSX?
- JavaScript XML
- HTML-like Syntax
- JavaScript Expressions inside JSX
- Using `{}` in JSX
- JSX with JavaScript
- Returning JSX from Components
- JSX Structure

---

## 🎨 Tailwind CSS with React

Basic Tailwind CSS integration and usage with React + Vite.

- Installing Tailwind CSS
- Tailwind CSS with Vite
- `vite.config`
- Tailwind Plugin
- `@import "tailwindcss"`
- Utility Classes
- Dynamic Tailwind Classes
- Styling React Components

---

## 🔀 Conditional Rendering

Displaying different UI based on conditions.

- Boolean Conditions
- Ternary Operator
- Conditional Text
- Conditional Buttons
- Dynamic Classes
- Conditional UI based on Data

Example use case:

```jsx
{instock ? "Buy Now" : "Out of Stock"}
```

---

## 🖱️ Event Handling

Handling user interactions in React.

- `onClick`
- Event Handler Functions
- Passing Functions to Events
- Event Function vs Function Call
- Download Button Example
- Handling User Actions

---

## 🔥 useState

Understanding React state management with practical examples.

- What is State?
- `useState()`
- State Initialization
- State Getter & Setter
- Updating State
- Boolean State
- String State
- Number State
- Object State
- Array State
- Updating Objects Immutably
- Updating Arrays Immutably
- Adding Array Elements
- Removing Array Elements
- Functional State Updates
- Previous State
- State Equality
- State Update Behaviour

Example:

```jsx
const [count, setCount] = useState(0);
```

---

## 📦 Props

Passing data between React components.

- What are Props?
- Parent → Child Data
- Passing Text through Props
- Passing Colors through Props
- Props Destructuring
- Reusable Components
- Passing Different Data to Same Component
- Props Drilling Introduction

Example:

```jsx
<Card3 
  text="Know More" 
  color="bg-blue-400"
/>
```

---

## 📝 Forms in React

Different approaches for handling forms.

### useRef

- Accessing Form Values
- `useRef()`
- `.current.value`
- `event.preventDefault()`

### Controlled Components

- Managing Form State
- `onChange`
- Input State
- Form Data Object

### React Hook Form

- Installing React Hook Form
- `useForm()`
- `register()`
- `handleSubmit()`
- Form Submission

---

## 🧭 React Router

Creating navigation between different pages/components.

- `react-router-dom`
- `BrowserRouter`
- `Routes`
- `Route`
- `Link`
- `NavLink`
- Navigation without Page Reload
- Active Navigation Styling
- Route Components
- Home Route
- User Route
- About Route

Example:

```jsx
<Route path="/about" element={<About />} />
```

---

## 🌐 API Integration

Connecting React applications with backend APIs.

- What is an API?
- Frontend & Backend Communication
- AJAX
- Fetch
- Axios
- GET Request
- POST Request
- API Response
- Storing API Data in State
- Displaying API Data
- Mapping API Data
- Fake Store API Example

Example:

```jsx
axios.get("https://fakestoreapi.com/products")
```

---

## 🔄 useEffect

Understanding side effects and component lifecycle.

- What is `useEffect()`?
- Side Effects
- API Calls using `useEffect`
- Component Mount
- Component Update
- Component Unmount
- Lifecycle Concept
- Running Functions Automatically
- API Data Fetching with `useEffect`

Example:

```jsx
useEffect(() => {
    getProducts();
}, []);
```

---

## 🛠️ Tools & Technologies

The notes use or discuss:

- React.js
- JavaScript
- JSX
- Vite
- Tailwind CSS
- Axios
- React
