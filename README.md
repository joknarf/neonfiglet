[![Joknarf Tools](https://img.shields.io/badge/Joknarf%20Tools-Visit-darkgreen?logo=github)](https://joknarf.github.io/joknarf-tools)
[![bash](https://img.shields.io/badge/shell-bash%203.x%2b%20-blue.svg)]()
[![Licence](https://img.shields.io/badge/licence-MIT-blue.svg)](https://shields.io/)


# neonfiglet

Fun banners with animated scroll / rainbow

![neonfiglet](https://github.com/user-attachments/assets/2b6ddc26-cca8-4c0a-97d7-ea3be225e03b)

![neonfiglet6](https://github.com/user-attachments/assets/f3c52816-e759-41eb-bb09-33ab167d0e5c)


## features

* lolcat color animate any content
* figlet font message
* left / center / right align
* initial scroll up / down / left / right, staggered up, write left to right
* colors lightness / saturation adjust
* color themes

## pre-requisite

* tput (ncurses)
* figlet (only to print message with figlet/toilet font)

## install

Use your prefered method according to your OS:

```
brew install joknarf/tools/neonfiglet
```

```
sudo dnf install https://github.com/joknarf/neonfiglet/releases/latest/download/neonfiglet.rpm
```

```
curl -OL https://github.com/joknarf/neonfiglet/releases/latest/download/neonfiglet.deb && sudo dpkg -i neonfiglet.deb
```

```
curl -OL https://github.com/joknarf/neonfiglet/releases/latest/download/neonfiglet.apk && sudo apk add --allow-untrusted neonfiglet.apk
```

```
curl -OL https://github.com/joknarf/neonfiglet/releases/latest/download/neonfiglet.pkg && sudo installer -pkg neonfiglet.pkg -target /
```

or just 

```
git clone https://github.com/joknarf/neonfiglet
```

## usage

```
neonfiglet -h
neonfiglet "message"
```


## credits

* awk lolcat code from [lolcat](https://github.com/Saruspete/lolcat)
