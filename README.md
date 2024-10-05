# termroll
## what is termroll
termroll is simply a way to rickroll someone right from their (ANSI capable) terminal
## requirements for termroll
`pv` and `wget` (for using termroll over the internet)
## how to rickroll using termroll
i will show how to use it over the internet.

1. install `pv` and `wget`
  - for debian/ubuntu-based distrbutions:
    ```
    sudo apt install pv wget
    ```
  - for arch/manjaro-based distrbutions:
    ```
    sudo pacman -Sy pv wget
    ```
2. activate termroll
  - for color (for ANSI and RGB color capable terminals only):
    ```
    wget 'https://github.com/kaslmineer7999/termroll/releases/download/termroll.files/rrc.txt' -qO-|pv -qL1000000
    ```
  - for B&W (supports any terminak):
    ```
    wget 'https://github.com/kaslmineer7999/termroll/releases/download/termroll.files/rr.txt' -qO-|pv -qL50000
    ```
3. you're done

## why "termroll" exists
because rickrolling your buddy is the best thing ever in planet earth
    
