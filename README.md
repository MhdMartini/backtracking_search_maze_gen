# backtracking_search_algorithm
Uninformed DFS of map with obstacles. 
Maze generator to generate searchable maps
Sample map is provided in the maps directory.

Generate a random maze:
    python maze_gen.py [--width WIDTH] [--help | -h]

        --width:    width of square maze, default is 75


Search a map:
    python searcher.py [--map MAP] [--start START] [--vid VID] [--help | -h]

        --map:      path to map image, default is maps/map2_100_i.png
        --start:    start position <row,col>, default is randomly generated
        --vid:      boolean for video output, default is False
