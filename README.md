

# Card Deck App — ReactJS Assignment

## Author  
**Mahtabin Tushi**  
Student ID: **000952184**

---

## Statement of Authorship  
*StAuth10244: I Mahtabin Tushi, 000952184 certify that this material is my original work. No other person's work has been used without due acknowledgement. I have not made my work available to anyone else.*

---

## Overview  
This project is a **ReactJS card deck application** built using **function components**, **hooks**, and **props**. It simulates a deck of playing cards and supports:

- Dealing 5 or 7 cards  
- Drawing a single card  
- Selecting and swapping cards  
- Tossing a selected card  
- Adding a wildcard  
- Regrouping (shuffling) displayed cards  
- Resetting the game  

The UI and card visuals are styled in **style.css**, and all React logic is inside **index.html** using Babel for JSX.

---

## Technologies  
- ReactJS (Hooks + Function Components)  
- ReactDOM  
- Babel  
- HTML5  
- CSS3  
- JavaScript (ES6)

---

## React Requirements  
This project follows all required React practices:

- ✔ Function components only  
- ✔ `useState` for all state management  
- ✔ Props passed into child components  
- ✔ No class components  
- ✔ No jQuery  
- ✔ No manual DOM manipulation  
- ✔ JSX rendered through ReactDOM  

---

## Features  
### Overturned Deck  
A styled rectangle appears on load, representing the back of the deck.

### Card Interactions  
- **Deal**: Draws 5 or 7 cards  
- **Draw**: Click the deck to draw one card  
- **Swap**: Select two cards to swap  
- **Toss**: Remove selected card  
- **Wildcard**: Add a random card  
- **Regroup**: Shuffle displayed cards  
- **Reset**: Restore full deck  

---

## File Structure  
```
project/
│
├── index.html   # React components, JSX, and logic
├── style.css    # Card and layout styling
└── README.md    # Documentation
```

---

## Git Commit Summary  
- **Bug 1 Commit** – Broke state access by moving handleDeckClick() outside App()  
- **Fix 1 Commit** – Returned handleDeckClick() inside App()  
- **Bug 2 Commit** – Placed JSX before return(), causing syntax error  
- **Fix 2 Commit** – Moved JSX back inside return()  
- **Readability Commit (HTML)** – Added structured comments throughout index.html  
- **Readability Commit (CSS)** – Added section comments in style.css  

---

## How to Run  
1. Open the project folder  
2. Open **index.html** in a browser  
3. React + Babel will load automatically  
4. Use the buttons and card interactions  

---

## Conclusion  
This project demonstrates modern ReactJS development using hooks, props, and function components. It meets all assignment requirements and includes full documentation and Git commit history.

---
