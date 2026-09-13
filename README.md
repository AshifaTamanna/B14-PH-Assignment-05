# DevStack

Dev Stack is a React and TypeScript workspace for exploring modern developer technologies and building a personalized development stack. It features a curated catalog of tools with quick filtering, category-based browsing, and a live stack builder for managing selected technologies.

## Technologies Used

- React 19 with TypeScript
- Vite
- Tailwind CSS and DaisyUI
- Lucide React icons
- React Toastify
- JSON-driven technology data

## Key Features

1. Built a searchable, category-filtered technology catalog with dynamic personal-stack management.
2. Implemented real-time toast feedback, responsive navigation, loading skeletons, and mobile-first UI.
3. Developed a reusable orange–pink–violet design system for consistent theming.

## Run Locally

```bash
npm install
npm run dev
```

To create a production build:

```bash
npm run build
```

## React Questions

### 1. What is JSX, and why is it used?

JSX is a syntax used in React to write HTML-like code inside JavaScript. It is used to make writing UI code in React easier and more readable by combining JavaScript with HTML-like syntax.

### 2. What is the difference between props and state?

Props are data passed from a parent component to a child component, while state is data managed and updated within a component.

### 3. What is `useState` and how does it work?

useState is a React Hook used to create and manage state in a component. 
It returns the current state value and a function to update it; when the state changes, React re-renders the component.

### 4. What is `useEffect` and when should it be used?

useEffect is a React Hook used to perform side effects in a component, such as fetching data, updating the document title, or setting up event listeners.
It runs after the component renders and is used when we need to interact with something outside the component.

### 5. How do you share state between components?

State is shared between components by lifting it to their common parent and passing the state and its update function through props.

### 6. What is a controlled component?

A controlled component is a form element whose value is controlled by React state. The input value is stored in state and updated using an event handler like onChange.

### 7. Why are keys needed when rendering lists?

Keys help React identify each list item uniquely and efficiently update, add, or remove items when the list changes.
