# ⚽ FIFA/EAFC Match Companion

**Cure "Meta Fatigue" with randomized matchups and custom House Rules.**

We all know the struggle: you sit down to play FIFA/EAFC with friends, and everyone picks Real Madrid, Man City, or PSG. It gets boring. 

This project is a **Vanilla JavaScript Web App** designed to spice up couch-play sessions. It ensures fair matchups based on star ratings while introducing "Game Modes" (like *Tactical Roulette* or *Transfer Market*) to force players out of their comfort zones.

## 🚀 Features

*   **Fair Matchmaking Algorithm:** Filters teams by Star Rating (3.5★ to 5★) to ensure competitive balance.
*   **"UNO-Style" Game Modes:** A visual grid to select match stipulations (e.g., "Reroll Tax," "Survival Mode," "Tactical Roulette").
*   **Dynamic Player Input:** Supports naming for 1v1, 2v2, or 1v3 setups.
*   **JSON-Based Database:** Teams are stored in an easily editable JavaScript object, making it simple to add your favorite obscure clubs.
*   **Zero Dependencies:** Built entirely with HTML, CSS, and Vanilla JS. No framework installation required.

## 🛠️ How to Use

1.  Clone the repository (or download the `.html` file).
2.  Open `index.html` in any web browser.
3.  **Step 1:** Enter player names.
4.  **Step 2:** Select a Game Mode (e.g., *Classic* or *Transfer Market*).
5.  **Step 3:** Hit **GENERATE MATCH** and kick off!

## 💻 Customization

Want to add your local team? Open the code and look for the `const teams` array:

```javascript
const teams = [
    { name: "Real Madrid", stars: 5, league: "La Liga" },
    { name: "Your Local Team", stars: 2, league: "Sunday League" }, // Add this!
];
