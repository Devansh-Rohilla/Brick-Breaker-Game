 Brick Breaker Game

Overview
This is a classic Brick Breaker game developed using Java. The game involves controlling a paddle to bounce a ball and break a set of bricks. The objective is to destroy all the bricks without letting the ball fall below the paddle. This project demonstrates the use of object-oriented programming principles in a simple yet engaging game.

Features
- **Paddle Control**: Use keyboard inputs to move the paddle left and right.
- **Ball Physics**: Realistic ball movement and collision detection with bricks, walls, and the paddle.
- **Brick Layout**: Dynamic brick layouts generated for different levels.
- **Scoring System**: Points awarded for each brick destroyed, with the game ending when all bricks are broken or the ball is missed.

Key Files
- **`GamePlay.java`**: Contains the main game logic, including player controls, ball movement, collision detection, and scoring.
- **`MapGenerator.java`**: Generates the grid of bricks for each level, allowing for customizable and varying levels of difficulty.
- **`MyApp.java`**: Serves as the entry point for the game, initializing the game environment and starting the game loop.

How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/brick-breaker-game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd brick-breaker-game
   ```
3. Compile the Java files:
   ```bash
   javac src/main/java/com/mycompany/brick/*.java
   ```
4. Run the game:
   ```bash
   java -cp src/main/java com.mycompany.brick.MyApp
   ```
 Requirements
- Java JDK 8 or higher

 Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.

---

This README provides a comprehensive yet concise overview of the project, making it easy for others to understand, run, and contribute to the game.
