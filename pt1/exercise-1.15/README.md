# Maze Generator CLI

To run the app you need to pull and run the [image](https://hub.docker.com/repository/docker/tikibeni/tira):

```sh
~$ docker run -it tikibeni:tira
```

Then the program asks (in Finnish) for the algorithm to be used (input 1 for Wilson or 2 for Random Prim)
After that you need to input the number of rows (integer) and columns (integer) used for the maze building.

Finally the program will generate the maze using these parameters and output it with the duration of building.

More information can be found in the repository of the [project](https://github.com/tikibeni/tiralabra).