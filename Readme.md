# 🌅 Snake & Ladder

A colorful, interactive Snake & Ladder game inspired by beautiful sunset shades, built using **Python, Flask, JavaScript, HTML, and CSS**.

Roll the dice, climb golden ladders, avoid sneaky snakes, and race your opponent to square 100!

## 🎮 Features

- 🌅 **Sunset-themed UI** – Beautiful pastel gradients and a vibrant game board.
- 👥 **Local Multiplayer** – Play with a friend on the same device.
- 🤖 **Play Against Computer** – Challenge the Sunset Bot.
- 🌐 **Online Multiplayer** – Create a room and invite a friend using a room code.
- 🎲 **Interactive Dice** – Animated dice rolling.
- 🐍 **Snakes & Ladders** – Move up ladders and slide down snakes.
- 🏆 **Winner Detection** – First player to reach square 100 wins.
- ⭐ **Extra Turn Rule** – Rolling a six grants another turn.
- ⚠️ **Three Sixes Rule** – Rolling three consecutive sixes sends the player back to the starting position.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Game logic |
| Flask | Backend framework |
| Flask-SocketIO | Real-time multiplayer communication |
| HTML5 | Game structure |
| CSS3 | Styling and animations |
| JavaScript | Game interactions |
| Socket.IO | Client-server communication |

## 📁 Project Structure

```text
Snake-Ladder/
│
├── app.py                 # Flask server and game routes
├── game.py                # Snake & Ladder game logic
├── test_game.py           # Game logic tests
├── requirements.txt       # Python dependencies
│
├── templates/
│   └── index.html         # Main game page
│
├── static/
│   ├── css/
│   │   └── style.css      # Game styling
│   │
│   ├── js/
│   │   └── script.js      # Game interactions
│   │
│   ├── images/            # Game images
│   └── sounds/            # Sound effects
│
└── README.md
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Navigate to the project folder

```bash
cd sunset-snake-ladder
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```powershell
.\venv\Scripts\Activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
python app.py
```

### 7. Open the game

Visit:

```text
http://127.0.0.1:5000
```

## 🎲 How to Play

1. Select your preferred game mode.
2. Enter player names.
3. Roll the dice to move across the board.
4. Climb ladders to advance.
5. Avoid snakes that take you backwards.
6. Reach square 100 before your opponent to win!

## 🌟 Future Improvements

- [ ] Deploy the game online.
- [ ] Improve online multiplayer reliability.
- [ ] Add player profiles and leaderboards.
- [ ] Add background music and sound effects.
- [ ] Add more board themes and customization options.

## 👩‍💻 Developed With

Built with Python, Flask, and JavaScript, with a little creativity and a lot of dice rolls! 🎲

**If you enjoy the game, give this repository a ⭐!**
