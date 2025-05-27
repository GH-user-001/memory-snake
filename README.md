# Memory Snake

Memory Snake is a web-based game that helps you memorize lists by playing a fun and challenging version of the classic Snake game. Instead of just eating food, you must eat items in the correct sequence to master a list!

🎮 **[Play Now](https://tinyurl.com/23v3uv67)**  
📚 **[View Research & Analysis](RESEARCH.md)**

## Features
- **Memorize by Playing:** Select or create a list (e.g., numbers, colors, planets) and memorize the sequence by eating items in order.
- **Custom & Built-in Lists:** Choose from built-in lists (Mandarin numbers, Spanish numbers, French colors, planets) or enter your own custom list.
- **Challenging Gameplay:** Eating the wrong item ends the game. Eat the correct item to progress and score points.
- **Progress Tracking:** See your progress and score as you play. Visual feedback helps reinforce memory.
- **Modern UI:** Responsive, visually appealing interface with keyboard controls (arrow keys to move, space to pause).

## How to Play
1. **Choose a List:** Click the settings icon to select a built-in list or enter your own custom, comma-separated list.
2. **Start the Game:** Press the Start button. Control the snake with the arrow keys.
3. **Eat in Sequence:** Eat the food items in the exact order shown. The next target is highlighted.
4. **Scoring:**
   - Eat the correct item: +10 points
   - Eat the wrong item: Game Over!
5. **Win:** Memorize the entire list in order to win!

## Example Lists
- Mandarin Numbers (1-10): 一,二,三,四,五,六,七,八,九,十
- Spanish Numbers (1-10): uno,dos,tres,cuatro,cinco,seis,siete,ocho,nueve,diez
- French Colors: rouge,bleu,vert,jaune,noir,blanc,orange,violet,rose,gris
- Planets: Mercury,Venus,Earth,Mars,Jupiter,Saturn,Uranus,Neptune

## Controls
- **Arrow Keys:** Move the snake
- **Space Bar:** Pause/Resume
- **Settings:** Change or create a list

## Tech Stack
- React
- Tailwind CSS (for styling)
- [lucide-react](https://lucide.dev/) (for icons)

## Getting Started
1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd memory-snake
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```
4. Open your browser at [http://localhost:3000](http://localhost:3000)

## License
MIT
