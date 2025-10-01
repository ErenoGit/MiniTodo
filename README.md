# MiniTodo
Simple test project todo HTML application with counter

# Mini App — Todo List + Counter

A simple project written in **HTML + JavaScript**, containing two main modules:
1. **Counter** — increase and decrease the value, with persistence using `localStorage`.
2. **Todo List** — add, remove, and clear tasks. The list is also stored in `localStorage`.

---

## Features

- **Counter**
  - `+1` and `-1` buttons increase or decrease the counter.
  - The counter value is stored in the browser's `localStorage`, so it does not reset after page reload.

- **Todo List**
  - Add a new task to the list.
  - Delete individual tasks.
  - Clear the entire list with one button.
  - All tasks are saved in `localStorage`.

---

## How to Run

1. Download or copy the `index.html` file.
2. Open it in any modern web browser (e.g., Chrome, Firefox).
3. Use the buttons to test the functionality.

---

## File Structure

- **HTML**:
  - Counter section (`#counter`, buttons `#incBtn`, `#decBtn`).
  - Todo list section (`#taskInput`, `#addTaskBtn`, `#taskList`, `#clearBtn`).

- **JavaScript**:
  - Variable `counter` and functions `updateCounter()`, `save/load` with `localStorage`.
  - Array `tasks` and functions:
    - adding tasks (with validation),
    - removing tasks,
    - clearing the entire list,
    - saving and loading state from `localStorage`.

---

## Possible Extensions

You can expand the project by adding:
- Editing existing tasks.
- Splitting tasks into “done” and “to do”.
- Exporting and importing tasks as a `.json` file.
- Reset button for the counter.

---

## Requirements

- No external libraries or frameworks required.
- Works in any modern browser that supports `localStorage` (virtually all of them).