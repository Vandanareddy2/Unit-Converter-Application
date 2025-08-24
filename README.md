# Unit-Converter-Application

# Unit Converter Application
A simple webpage that demonstrates **HTML5 structural elements** and **basic CSS styling** by building a Unit Conversion UI (Temperature, Weight, Distance). This lab focuses on layout, navigation, and styling — not JavaScript logic.

## Features
- Top “Home” section with **header** and **nav** (anchor links jump to sections)
- Three conversion panels:
  - **Temperature** (Celsius ↔ Fahrenheit)
  - **Weight** (Kilograms ↔ Pounds)
  - **Distance** (Kilometers ↔ Miles)
- **Floating Home button** (fixed at bottom-left)
- Responsive-ish layout using **Grid + Flexbox**

## Tech Stack
- **HTML5** → `section`, `header`, `nav`, `figure`, `article`, `aside`, `fieldset`, `legend`
- **CSS** → selectors, classes/ids, hover states, grid, flexbox

## File Structure
.
├── index.html  
└── style.css

## Getting Started
### 1. Fork the repository
Click the **Fork** button (top-right of this repo) to create your own copy under your GitHub account.

### 2. Clone your fork
git clone https://github.com/<your-username>/unit-conversions.git

### 3. Navigate to the project folder
cd unit-conversions

### 4. Open the project
- Open `index.html` directly in your browser  
- OR use VS Code’s **Live Server** extension:  
  - Right-click `index.html` → **“Open with Live Server”**

## What You’ll See
- **Header** on the left, **Nav buttons** on the right
- Three white “cards” (600×400) with colored top borders:
  - Temperature → green
  - Weight → coral
  - Distance → cyan
- **Convert buttons** styled (rounded, light green, pointer on hover)
- A **cyan circular home icon** fixed at the bottom-left that links to the top

## Contributing
Contributions are welcome 🎉

1. Fork the repository  
2. Clone your fork  
   git clone https://github.com/<your-username>/unit-conversions.git  
3. Create a new branch  
   git checkout -b feature/your-feature-name  
4. Make your changes (update HTML, CSS, or README)  
5. Commit your changes  
   git commit -m "Add: description of your change"  
6. Push to your fork  
   git push origin feature/your-feature-name  
7. Open a Pull Request on GitHub

## Notes
- This lab focuses only on **styling**; JavaScript conversion logic can be added later.  
- Classes were added per instructions: `.topdiv`, `.topmenu`, `.b temperature`, `.b weight`, `.b distance`, `.iconbutton`.  
- Footer styled with light background and spacing.
