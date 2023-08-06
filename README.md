# The Jocorice (Jocomol's <https://jocomol.ch>'s dotfiles)

These are the dotfiles deployed by [JARBS](https://larbs.xyz) and as seen on
[Luke's YouTube channel](https://youtube.com/c/lukesmithxyz).

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- nsxiv (image/gif viewer)
	- mpv (video player)
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/jocomol/dwm) (window manager)
- [dwmblocks](https://github.com/jocomol/dwmblocks) (statusbar)
- [st](https://github.com/jocomol/st) (terminal emulator)

I also recommend trying out
[mutt-wizard](https://github.com/lukesmithxyz/mutt-wizard), which additionally
works with this setup. It gives you an easy-to-install terminal-based email
client regardless of your email provider. It is integrated into these dotfiles
as well.

## Install these dotfiles and all dependencies

Use [JARBS](https://larbs.xyz) to autoinstall everything:

```
curl -LO larbs.xyz/larbs.sh
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/Jocomol/LARBS/blob/master/static/progs.csv).

## Default Desktop Artwork

Thomas Thiemeyer's *The Road to Samarkand* ([fb](https://www.facebook.com/t.thiemeyer/), [insta](https://www.instagram.com/tthiemeyer/), [shop](https://www.redbubble.com/de/people/TThiemeyer/shop))
