# Maze Runner with Q-Learning 🧠

This project demonstrates a reinforcement learning agent navigating through a randomly generated maze using the **Q-Learning** algorithm. After training, the best path to the goal is visualized as a `.gif`.

## 📂 Project Structure

- `main.ipynb`: Jupyter Notebook for experimentation
- `maze_runner.py`: Main Python script
- `MazeRunnerWith QLearning/`: Folder where output GIFs are saved
- `README.md`: Project documentation

## 🤖 Algorithm

- **Q-Learning** (off-policy RL)
- **Epsilon-greedy** exploration strategy
- **Reward Structure**:
  - Reaching the goal: `+1`
  - Hitting a wall: `-5`
  - Stepping on empty cell: `-0.1`

## 🎯 Features

- Random maze generation for each run
- Q-table based training over multiple episodes
- Success rate tracking & plotting
- GIF export of the best path after training
- (Optional) Real-time visualization via Pygame
