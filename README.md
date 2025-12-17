# Far Away – Packing List App

A simple React application for managing a travel packing list. Users can add items with quantities, mark items as packed, sort the list, clear the list, and view packing progress statistics.

---

## Features

* Add packing items with quantity and description
* Mark items as packed / unpacked
* Delete individual items
* Sort items by:

  * Input order
  * Description
  * Packed status
* Clear the entire packing list
* View packing progress statistics
* Conditional UI rendering (sorting controls appear only when items exist)

---

## Tech Stack

* **React** (Hooks API)
* **JavaScript (ES6+)**
* **CSS** (custom styling)

---

## Project Structure

```
src/
│
├── App.jsx
├── App.css
├── Logo.jsx
├── Form.jsx
├── PackingList.jsx
├── Item.jsx
├── Stats.jsx
└── main.jsx
```

---

## Getting Started

### Prerequisites

* Node.js (v16 or later recommended)
* npm or yarn

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project directory:

```bash
cd far-away
```

3. Install dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm run dev
```

5. Open your browser and navigate to:

```
http://localhost:5173
```

---

## Usage

1. Select a quantity and enter an item description.
2. Click **Add** to add the item to the packing list.
3. Use the checkbox to mark items as packed.
4. Sort items using the dropdown (appears once items are added).
5. Remove individual items using the delete button.
6. Click **Clear List** to remove all items.
7. View packing progress in the footer statistics section.

---

## Key Components

* **App** – Root component, manages global state
* **Form** – Handles item creation
* **PackingList** – Displays items and sorting controls
* **Item** – Individual packing list item
* **Stats** – Displays packing progress summary
* **Logo** – Application header

---

## State Management

* Global state (`items`) is managed in `App.jsx`
* Child components receive state and handlers via props
* Sorting state is localized to `PackingList.jsx`

---

## Possible Enhancements

* Persist items to `localStorage`
* Add edit functionality for items
* Add drag-and-drop reordering
* Convert to TypeScript
* Add unit tests

---

## License

This project is for educational purposes and personal use.

---

## Author

Built as a React practice project to demonstrate component composition, state lifting, and controlled inputs.
