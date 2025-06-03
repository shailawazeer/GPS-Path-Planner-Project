# GPS Path Planner 🗺️

A Java-based desktop application that demonstrates pathfinding algorithms through an interactive graphical interface. This project implements classic search algorithms to find optimal routes between user-specified points on a grid-based map while navigating around various obstacles.

## 🚀 Features

- **Interactive Grid Interface**: User-friendly GUI for selecting start and destination points
- **Multiple Pathfinding Algorithms**: 
  - Breadth-First Search (BFS) - finds shortest path
  - Depth-First Search (DFS) - explores paths systematically
- **Obstacle Navigation**: Smart routing around predefined impediments including:
  - Buildings
  - Construction zones
  - Other environmental barriers
- **Real-time Distance Calculation**: Automatic computation and display of path distances
- **Visual Path Display**: Clear visualization of discovered routes on the grid
- **Single Window Interface**: Clean, consolidated desktop application design

## 📋 Prerequisites

- Java Development Kit (JDK) 8 or higher
- Any IDE that supports Java (IntelliJ IDEA, Eclipse, VS Code, etc.) or command line

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/shailawazeer/gps-path-planner.git
   cd gps-path-planner
   ```

2. **Compile the project**
   ```bash
   javac *.java
   ```

3. **Run the application**
   ```bash
   java Main
   ```

## 🎮 How to Use

1. Launch the application to open the interactive grid map
2. Click to select your starting point on the grid
3. Click to select your destination point
4. Choose between BFS or DFS algorithm
5. Watch as the algorithm explores the grid and finds a path
6. View the calculated route with distance information

## 🧠 Algorithms

### Breadth-First Search (BFS)
- Guarantees the shortest path in terms of grid steps
- Explores all neighbors at each level before moving deeper
- Optimal for finding minimum distance routes

### Depth-First Search (DFS)
- Explores paths by going as deep as possible before backtracking
- May not find the shortest path but demonstrates systematic exploration
- Useful for understanding different search strategies

## 🔧 Technical Details

- **Language**: Java
- **Interface**: Swing/AWT GUI
- **Grid System**: 2D array-based map representation
- **Pathfinding**: Graph traversal algorithms with obstacle avoidance
- **Visualization**: Real-time algorithm execution display

## 📚 Educational Value

- Learn fundamental pathfinding algorithms
- Understand the difference between BFS and DFS
- Visualize graph traversal concepts
- Explore obstacle avoidance in route planning
- Practice GUI programming in Java

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Project Link: [https://github.com/shailawazeer/gps-path-planner](https://github.com/shailawazeer/gps-path-planner)

## 🙏 Acknowledgments

- Thanks to all contributors who helped improve this project
- Inspiration from classic pathfinding algorithm implementations
- Educational resources on graph theory and search algorithms
