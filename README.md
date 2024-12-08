# CLIwrap
🎉 The *"Spotify Wrapped"* feature for **your** terminal!

### How?
CLIwrap reads your shell's history file to serve you a recap of what commands you ran in your terminal!

### Supported Shells
- bash
- csh/tcsh
- fish
- zsh

### Installation
Installing **CLIwrap** is easy! You can pull this Git image, or create a new file and set everything up yourself. Because that it is a simple **bash** script, you don't need to run or build anything!

#### Install via Homebrew
You can now easily install **CLIwrap** on your device with [Homebrew](https://brew.sh)
```bash
$ brew tap islemci/cliwrap
$ brew install cliwrap
```

> [!NOTE]
> As the **CLIwrap** is not currently in the Homebrew main repo, you should not forget to add the tap of this app via `brew tap`.

#### Install from AUR
Arch Linux users can easily install **CLIwrap** from the [AUR](https://aur.archlinux.org)
```bash
$ yay -S cliwrap-git
```

#### Run from file
With commands below, download cliwrap to your current directory and mark it as executable.

```bash
$ curl -sSL -o cliwrap https://raw.githubusercontent.com/islemci/cliwrap/refs/heads/main/cliwrap
$ chmod +x cliwrap
```

Now, try running it with by running the following command:

```bash
$ ./cliwrap
```

Congrats! Now the script should be working. You can run it with the `-h` flag for more information.

#### Run from everywhere

To run it everywhere with a simple command, you can use command below to download the script and move the script into your `/usr/local/bin` directory.


```bash
$ sudo curl -sSL -o /usr/local/bin/cliwrap https://raw.githubusercontent.com/islemci/cliwrap/refs/heads/main/cliwrap
$ sudo chmod +x /usr/local/bin/cliwrap
```

Now, you can run:

```bash
$ cliwrap
```

to get your wrapped everywhere!

### Custom messages for specific commands/tools

Motivating and positive messages about usage of tools like `ls`, `brew` etc. will be displayed if one of them is a top tool.

### License
This project is licensed under the MIT License. You can check out the conditions [here.](LICENSE)
