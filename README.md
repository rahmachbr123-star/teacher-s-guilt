# teacher-s-debt

The Teacher's Debt is a dark, atmospheric web-based narrative horror game. Built with HTML5, CSS3, and Vanilla JavaScript, it tells the story of a teacher returning to the dilapidated Blackwood Manor to face the ghosts of the children they failed to protect a decade ago.

## Game Overview
Players navigate through various rooms of the manor, uncovering evidence of past atrocities. The game features a "Guilt" (Sanity) system where uncovering the truth or facing the spirits drains your mental state.

Genre: Psychological Horror / Visual Novel

Engine: Pure Web Tech (No frameworks)

Key Mechanics: Point-and-click navigation, evidence logging, sanity management, and branching endings.

## Features
Dynamic Typewriter Effect: Text unfolds at varying speeds to build tension.

Spirit Voice: Eerie, italicized dialogue highlights the presence of the manor's haunts.

Case File System: A journal that tracks "Evidence" found during your playthrough.

Reactive Visuals: The UI distorts (inverts and high-contrast) as your sanity reaches critical levels.

Multiple Endings: Your final choices determine whether you find a hollow redemption or become a permanent resident of the cellar.

## Installation & Setup
Save the Code: Copy the HTML/JavaScript provided into a file named index.html.

Asset Preparation: To experience the full atmosphere, place the following files in the same directory:

Audio: click sound.mp3, music of the game.mp3.

Images: gate.jpg, hallway.jpg, bedroom.jpg, kitchen.jpg, basement.jpg, death.jpg, prison.jpg.

Run: Open index.html in any modern web browser (Chrome, Firefox, Edge, or Safari).

Note: Due to browser "Autoplay" policies, the background music will begin after your first interaction (clicking the first button).

## Technical Structure
gameState Object: Tracks whether you've found the knife or diary and manages your sanity percentage.

scenes Constant: A robust JSON-like structure containing text, choices, background triggers, and logic-based actions for every state in the game.

CSS Variables: Uses --sanity to dynamically update the health bar width in real-time.

## Controls
Mouse/Touch: Click buttons to make choices or interact with objects.

[ CASE FILE ]: Click at any time to review the evidence you have collected.
