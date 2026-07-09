# **Tetris Game - Console Version**  

### **Overview**  
This is a **console-based Tetris game** implemented in **C++**. It follows the classic Tetris rules, where you control falling Tetrominoes (blocks), rotate them, and stack them to clear lines. The game ends when the blocks reach the top of the grid.

---

## **Features**  
✔ **Classic Tetris Gameplay** - Move, rotate, and drop pieces to clear lines.  
✔ **Hard Drop & Soft Drop** - Instantly drop pieces or move them down faster.  
✔ **Automatic Line Clearing** - Full rows disappear to make space.  
✔ **Game Over Detection** - The game stops when the stack reaches the top.  
✔ **Pause Functionality** - Press **ESC** to pause and resume the game.  
✔ **Randomized Tetromino Generation** - Ensures diverse gameplay.  

---

## **Controls**  
| Key | Action |
|------|------------------------|
| ← (Left Arrow)  | Move piece left |
| → (Right Arrow) | Move piece right |
| ↑ (Up Arrow)    | Rotate piece |
| ↓ (Down Arrow)  | Soft drop (faster movement) |
| SPACE           | Hard drop (instant landing) |
| ESC            | Pause / Resume |

---

## **How to Play**  
1. Run the **Tetris.exe** file in a console window.  
2. Use **arrow keys** to move and rotate the blocks.  
3. Try to form complete horizontal **lines** to clear them and earn points.  
4. The game ends when the blocks reach the **top of the grid**.  

---

## **Installation & Compilation**  
### **Windows**  
1. Install a **C++ compiler** (MinGW, Visual Studio, or any GCC-based compiler).  
2. Open a terminal or **Command Prompt**.  
3. Compile the game using:  
   ```sh
   g++ tetris.cpp -o tetris.exe
   ```
4. Run the game:  
   ```sh
   tetris.exe
   ```

### **Linux / macOS**  
1. Open a terminal.  
2. Compile the game using:  
   ```sh
   g++ tetris.cpp -o tetris
   ```
3. Run the game:  
   ```sh
   ./tetris
   ```

---

## **Code Structure**  
- **`main()`**: The main game loop handling movement, rotation, and collision.  
- **`draw()`**: Displays the Tetris grid and active Tetromino.  
- **`check()`**: Ensures that a move or rotation is valid.  
- **`hardDrop()`**: Instantly drops the piece to the lowest position.  
- **`rotation logic`**: Uses **pivot-based rotation** for Tetrominoes.  

---

## **Planned Future Enhancements**  
🚀 **Add Color Support** - Different colors for different Tetrominoes.  
🚀 **Scoring System** - Earn points for clearing lines.  
🚀 **Hold Piece Feature** - Allow swapping pieces.  
🚀 **Next Piece Preview** - Show upcoming pieces.  
🚀 **Music & Sound Effects** - Improve player experience.  
🚀 **Multiplayer Mode** - Compete against another player.  
🚀 **Online Leaderboard** - Track high scores globally.  

---

## **Troubleshooting**  
### **Game Doesn't Compile?**  
- Ensure **g++ or another compiler** is installed.  
- Use **C++11 or higher** for compatibility:  
  ```sh
  g++ -std=c++11 tetris.cpp -o tetris
  ```

### **Screen Flickering?**  
- Try running the game in **fullscreen mode**.  
- Modify `system("cls");` to use **buffered drawing techniques**.  

### **Game Closes Instantly?**  
- Run the executable **from a terminal or command prompt**.  
- Add `system("pause");` at the end of `main()` to prevent the window from closing.  

---


## **Contributors**  
👨‍💻 **Team: Code Mavericks**  
- **Tirth Solanki**  
- **Darpan Sherathiya**  
- **Deep Shobhashana**  
- **Shaurya Pratap Singh Shekhawat**  

🔧 **Open for Contributors!** Feel free to fork and improve the game.  

---

