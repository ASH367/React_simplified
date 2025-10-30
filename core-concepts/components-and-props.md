# 🧱 Components and Props

Components are the fundamental building blocks in React — they define isolated, reusable UI units that encapsulate both structure and behavior.

---

### 🧩 Functional Components
A component is a pure function that accepts input (`props`) and returns UI (`JSX`).

```jsx
function Button({ label, onClick }) {
  return (
    <button
      onClick={onClick}
      className="px-4 py-2 rounded-md bg-blue-600 text-white hover:bg-blue-700"
    >
      {label}
    </button>
  );
}
