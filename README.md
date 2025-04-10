## 🌀 Mouse Trail Effect using Vanilla JavaScript

This simple project demonstrates a dynamic mouse trail effect using plain JavaScript and DOM manipulation.

Whenever the user moves the mouse across the page, a randomly sized `span` element is created at the cursor's position. These elements visually trail the mouse, creating an engaging and interactive experience. Each element is automatically removed after 3 seconds to keep the DOM clean.

### 💡 Features:
- Uses `addEventListener` to track mouse movement.
- Dynamically creates `span` elements with random sizes.
- Positions each element exactly at the cursor location using `offsetX` and `offsetY`.
- Automatically removes elements after a short delay (3 seconds).
- Built without any external libraries — just pure JavaScript.

### 📚 Topics Covered:
- DOM Manipulation
- Event Handling
- Dynamic Element Creation
- Timed Element Removal (`setTimeout`)
