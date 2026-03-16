<p align="center">
  <img src="assets/screenshots/title.png" alt="Water Jug Game Title Screen" width="700"/>
</p>

<h1 align="center">
  💧 Water Jug Puzzle Game
</h1>

<p align="center">
  <strong>Where Logic Meets Water</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Built_With-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Powered_By-HTML5_%26_CSS3-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/Platform-Web_App-00DDC0?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/No_Dependencies-Zero-00DDC0?style=for-the-badge"/>
</p>

---

<p align="center">
  <em>An interactive water jug puzzle game based on a classical logic problem.<br/>
  Measure the exact amount of water using a limited number of jugs.</em>
</p>

---

# 🌊 What Is the Water Jug Puzzle?

The **Water Jug Puzzle** is a classic logic problem widely used in **mathematics, computer science, and artificial intelligence**.

Players are given jugs of different capacities and must measure an **exact target amount of water** using a limited set of operations.

These operations include:

• Filling a jug  
• Emptying a jug  
• Pouring water between jugs  

The puzzle requires logical reasoning and step-by-step planning to reach the target measurement.

---

# 🎮 Game Modes

This web application provides two gameplay modes.

## 🪣 2 Jug Mode

Jug Capacities:

```
4 Liters
3 Liters
```

Players must reach a randomly generated goal using these two jugs.

---

## 🪣 3 Jug Mode

Jug Capacities:

```
8 Liters
5 Liters
3 Liters
```

This mode is more challenging because it introduces additional combinations of water transfers.

---

# 🎯 Objective

Each time a new game starts, the system generates a **random goal value**.

Example:

```
Goal: 4 Liters
```

The player must reach **exactly that amount of water in any jug**.

---

# 🎮 Gameplay

## 🏠 Main Menu

The main menu allows the player to select the game mode.

Options:

• 2 Jug Puzzle  
• 3 Jug Puzzle  

---

## 🎮 Game Screen

The game interface includes:

• Visual water buckets  
• Current water levels  
• Goal amount display  
• Move counter  
• Control buttons  

Players interact with buttons to perform actions.

---

# 💧 Controls

| Button | Function |
|------|------|
| Fill | Fill the jug to its maximum capacity |
| Empty | Empty all water from the jug |
| Pour | Transfer water from one jug to another |
| Reset | Reset water levels without changing the goal |
| Menu | Return to the main menu |

---

# 🏆 Winning the Game

The player wins when:

```
Water in any jug = Goal amount
```

When this happens:

• A **YOU WON message** appears  
• The number of moves used is displayed  
• The player can start a new puzzle  

---

# 🧠 Game Logic

The puzzle works using three core operations.

## Fill Operation

Fill a jug completely.

Example:

```
Fill(A)
```

---

## Empty Operation

Remove all water from a jug.

Example:

```
Empty(A)
```

---

## Pour Operation

Transfer water between jugs.

```
pour(A → B)

amount = min(level[A], capacity[B] - level[B])
```

The pour stops when:

• Source jug becomes empty  
• Destination jug becomes full  

---

# 🏗 Project Structure

```
water-jug-game
│
├── index.html
├── README.md
│
├── assets
│   └── screenshots
│       ├── menu.png
│       ├── gameplay.png
│       └── win.png
```

---

# 🚀 Running the Project

This project does **not require installation**.

Steps:

1. Download or clone the repository
2. Open the project folder
3. Run the file:

```
index.html
```

in any web browser.

---

# 🌐 Deployment

The project can be deployed using **GitHub Pages**.

Steps:

1. Upload the project to GitHub  
2. Go to **Repository Settings**  
3. Select **Pages**  
4. Choose **Deploy from main branch**

Your game will be available at:

```
https://username.github.io/water-jug-game
```

---

# 🛠 Technologies Used

| Technology | Purpose |
|------|------|
| HTML | Structure of the webpage |
| CSS | Styling and layout |
| JavaScript | Game logic and interactions |

---

# 👨‍💻 Author

**Soumyajyoti Jana**

KIIT University  
Web and Mobile Application Development Assignment

---

<p align="center">
  <img src="https://img.shields.io/badge/Made_with-💧_&_Logic-64E8FF?style=for-the-badge"/>
</p>

<h3 align="center">
  <em>Water Jug Puzzle Game — Where logic meets water.</em>
</h3>
