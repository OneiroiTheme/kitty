## Installation

Compile and install:

1. Clone this repository

    ```bash
    git clone "https://github.com/{{repository.publisher}}/{{repository.repo}}.git" ./kitty
    cd ./kitty
    ```

2. Install themes

    Place theme files inside the `themes` folder under your `kitty config directory`.

    ```bash
    mkdir -p ~/.config/kitty/themes
    cp ./*.conf ~/.config/kitty/themes
    ```

3. Changing the theme

    ```bash
    kitten themes --reload-in=all oneiroi dream
    ```
