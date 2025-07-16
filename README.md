# workflow

### Install most packages on MacOS

```
brew install fzf \
    ripgrep \
    fd
```


### Best terminal emulator

```

brew install iterm2
```

### Shell

```
brew install zsh \
    zsh-autosuggestions \
    zsh-syntax-highlighting
```

*** Example
```
ZSH_THEME="powerlevel10k/powerlevel10k"

plugins=(
  git
  zsh-autosuggestions
  zsh-syntax-highlighting
  # docker
  # z
)
```

## Helpers

```
brew install fzf
```

### Common commands

```
cd /path/to/dir
```

```
grep "search term" -r .
``` 

```
ls -l
```


```
cat file.txt
```


```
cat file.txt | grep -i "search term"
```



## Navigate directory

```
brew install z
```
## Search files

Contents:
```
brew install ripgrep 
```

Names of files
```
brew install fd
```


### dotnet 

```
which dotnet
/usr/local/bin/dotnet
```


```
dotnet test 
```

```
dotnet run
```

```
dotnet clean
```

## Neovim

```
brew install nvim


Custom configuration via:
https://www.lua.org/

~/.config/nvim

```

### Mangement of env variables 

```
https://direnv.net/
```

### Session Mangement

```
brew install tmux
```
