# Maze generator

## System requirements
> python3

> pip

## Project launch
```bash
pip install -r requirment.txt
python3 start.py <length_of_maze_side> <gen_algoritm: dfs or mst>
```

There are restrictions of size: it should be above 5, and for mst algorithm under 25

Then pygame window will open and you can use arrow keys to wander through the maze.

If you want to exit, use "Esc" button. 

If you want to see the path, use "Tab" button.

After closing pygame window, you can find solution in solution/solution.txt

WARNING: there will be sound if you'll find the way(don't worry, it's innocent)
