# Cow Collection

ASCII art collection tailored for use in the `cowsay` command.  
`cowsay` defines a "cow" as any ASCII art creation that presents a message in a playful and engaging way.

```text
 _________________________________
< Welcome to my cowsay collection >
 ---------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

## Notable ASCII Art Galleries

- [Additional cowsay cows colored](https://github.com/paulkaefer/cowsay-files)
- [Dots Art](https://emojicombos.com)
- <https://github.com/bkendzior/cowfiles/tree/master>
- <https://asciiart.cc>
- <https://texteditor.com/gallery>
- <https://github.com/sckott/cowsay/blob/main/R/animals.r>
- <https://artcode.org/ascii/list.php>
- <https://www.penceland.com/ascii.html>
- <https://the.sunnyspot.org/asciiart/gallery/saaas1.html>
- <http://www.ascii-art.de/ascii>

- <https://www.curlie.org/en/Arts/Visual_Arts/ASCII_Art/Collections>
- <https://www.mozz.us/ascii-art.html>
  - <https://www.mozz.us/ascii-art/scratchpad.html>
- <https://ascii.co.uk/art>
- <https://www.asciiart.eu>
- <https://asciiart.website/index.php>
- <https://artcode.org/ascii/directory.php?cat=Artists&first=0&time=>

## Notable ASCII Artists

- [Famous ASCII Artists List](https://www.asciiart.eu/ascii-artists/famous)
- Joan G. Stark (Spunk) (jgs)
  - [Personal Website](http://www.ascii-art.com)
  - [Wiki](https://en.wikipedia.org/wiki/Joan_Stark)
- Michael Lazar (mozz)
  - [Website](https://mozz.us)
- Rowan Crawford (Row)
  - [Art Repository](https://the.sunnyspot.org/asciiart/gallery/art08.html)
- Lorrie Carrington (lc)
  - Member of [ASCII Art Ring](https://artcode.org/ascii/list.php)
  - [Personal Website](https://www.angelfire.com/art/lorriesascii)
- Andreas Freise (a:f)
  - Member of [ASCII Art Ring](https://artcode.org/ascii/list.php)
  - [Personal Website](http://www.ascii-art.de/ascii/my)
- llizard (ejm)
  - <https://llizard.etherwork.net/index.php>
- Joris Bellenger (b'ger)
  - <https://asciiart.website/artist.php?artist_id=31&page=1>
- Alessio Roberti Vittory (ARV)
- Veronica Karlsson (VK)

## Local Setup Instructions

1. Install `cowsay` command
    - Linux

        ```bash
        apt get install cowsay
        ```

    - MacOS

        ```bash
        brew install cowsay
        ```

2. Persist `COWPATH` environment variable

    ```bash
    echo "export COWPATH=\"~/.cows\"" >> ~/.bashrc
    ```

3. Copy over desired `*.cow` files into `$COWPATH` directory

    ```bash
    cp cows/cow.cow $COWPATH
    ```
