
# 🃏 Blackjack Game (Java Swing)

A simple and interactive Blackjack game built using Java and the Swing GUI toolkit. Play against a computerized dealer, test your luck, and enjoy a fully visual game experience with card images and score tracking.

## 🎮 Game Rules

- You play against the dealer (computer).
- Try to get as close to 21 as possible without going over.
- Numbered cards are worth their face value, face cards (J, Q, K) are worth 10, and Aces can be worth 11 or 1.
- Dealer must draw until they have at least 17.
- Player wins if:
  - They have a higher score than the dealer without busting (going over 21).
  - The dealer busts.

## 🖥️ Features

- GUI built with Java Swing.
- Clickable buttons to `Hit`, `Stand`, and `Reset`.
- Real-time score updates for both player and dealer.
- Ace handling logic: automatically reduces Ace value to 1 if you're about to bust.
- Card images displayed for both hands (player and dealer).
- Hidden dealer card revealed after you stand.
- Randomized deck shuffle each round.

## 📦 Folder Structure

```
BlackJack/
│
├── /cards/               # Contains all card images (e.g., 2-H.png, Q-S.png, BACK.png)
├── BlackJack.java        # Main Java source code
├── README.md             # You're reading it!
```

> 📝 Card images must be named in the format `VALUE-TYPE.png` (e.g., `A-H.png` for Ace of Hearts), and placed in the `/cards/` folder. The back of the dealer's hidden card should be named `BACK.png`.

## 🚀 How to Run

1. **Clone or Download** the repository.
2. Ensure you have Java installed (Java 8+ recommended).
3. Place the card images inside a folder called `/cards/` in your classpath.
4. Compile and run the program:

```bash
javac BlackJack.java
java BlackJack
```

## 🧠 Notes

- The GUI opens in a fixed-size window.
- Hitting after busting will automatically trigger a "Stand".
- Dealer plays automatically after you stand.
- Dealer’s hand is partially hidden until the player stands.
- If the player busts (goes over 21), the game ends immediately.
- Aces are dynamically calculated: if you have two Aces, one is treated as 11 and the other as 1 to avoid busting.
- Reset button clears the board and starts a new round with a reshuffled deck.

## 📸 Preview

<!-- Optional: Add a screenshot of the game window here -->
<!-- ![Blackjack Game Screenshot](your_screenshot_here.png) -->

## 👨‍💻 Author

Created by [Your Name] — Built for fun, learning, and practicing GUI-based game development in Java.

## 📜 License

This project is open-source and free to use.
