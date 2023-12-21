# Mason CLI

This project aims to evaluate the implementation and features of mason_cli. \
You can find bricks examples in the repository [bricks](bricks/)
>Documentation : [BrickHub](https://docs.brickhub.dev/)

## Installation

```bash
 #Activate from https://pub.dev
 dart pub global activate mason_cli
```

 You may need to manually add Mason to your environment variables.

## Initializing

By initializing mason this will generate a **mason.yaml** and allow mason to work with bricks scoped locally within the workspace.

```bash
 mason init
```

## Installing Bricks

You can add bricks to your project from a local repository or from a Git repository.

```bash
 # from a local repository
 mason add [BRICK_NAME] --path [PATH]

 # from a Git repository
 mason add [BRICK_NAME]
  --git-url [GIT_URL]   # https://github.com/felangel/mason
  --git-path [GIT_PATH] # bricks/widget
```

## Listing all Installed Bricks

You can list all installed bricks.

```bash
 mason ls
```
