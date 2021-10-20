# **compose-update** a docker-compose-image-updater
This python script updates the images of one or many docker-compose stacks automatically.

If multiple docker-compose directories are supplied, the script updates them in parallel.

## Demo
![output](https://user-images.githubusercontent.com/31591562/133811801-16eb581f-f63c-454f-a5de-e872568f3477.gif)


## Usage
```
Usage: compose-update [OPTIONS] [UPDATE_DIRS]...

  Update docker-compose images automatically.

  Takes one or more directorys as input and searches for a
  compose file in one of the following forms:
  "compose.yaml", "compose.yml", "docker-compose.yaml",
  "docker-compose.yml"

Options:
  --prune / --no-prune  Prune docker images after update
                        process if set
  --help                Show this message and exit.
```

## Installation
```
git clone https://github.com/FrederikRogalski/compose-update.git
cd compose-update
chmod +x update-compose
```

Then add the file 'update-compose' to your path.
