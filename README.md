# bastet (Console Text Based Game)
Bastet (short for Bastard Tetris) is an attractive alternative to Microsoft Word." (taken from http://hublog.hubmed.org)

## bastet (Project Info)
[Website](http://fph.altervista.org/prog/bastet.html)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/bastet/)

## Build image
`$ docker build -t macabees/bastet:latest .`

## Docker Push
`$ docker push -t macabees/bastet:latest`

Note: requires `docker login`

## Run image
`$ docker run -it --rm --name bastet macabees/bastet`

## Help
`$ docker run -it --rm macabees/bastet --help`

The game is pretty self-explanatory; use the arrow keys and <space> or <enter> to browse through the menus, set the keys to anything you're comfortable with, and hit "Play!".

The default keys are as follows:
| Key       | Description |
| Down	    | Down |
| Left	    | Left |
| Right	    | Right |
| Space bar | Rotate tetromino clockwise |
| Up        | Rotate tetromino counterclockwise |
| Enter	    | "Hard-drop" tetromino (like pressing "Down" continuously) |
| p	    | Pause |
| Control+C | Quits the game immediately and without asking anything (the current game is lost, but previous games are recorded in the high scores file) |
