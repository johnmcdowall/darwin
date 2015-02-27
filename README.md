<a name="darwin"></a>

<p align="center">
<b><a href="#run">Run</a></b>
|
<b><a href="#options">Options</a></b>
|
<b><a href="#themes">Themes</a></b>
|
<b><a href="https://github.com/bucaran/darwin/wiki/Copy-&-Paste-Recipes">Recipes</a></b>
|
<b><a href="#about">About</a></b>
</p>

<p align="center">
<a href="https://github.com/bucaran/darwin/blob/master/darwin">
<img width=10% height=10% src="https://cloud.githubusercontent.com/assets/8317250/6326580/6c238cd8-bb96-11e4-83a4-41e8d6fd2568.gif">
</a>
</p>

<p align="center">
<em><strong>It's dangerous to go alone! Take <a href="http://git.io/darwin">this</a>...</strong></em></p>


<hr>


<a name="run"></a>


<p align="center">
<img width="80%" src="https://cloud.githubusercontent.com/assets/8317250/6407336/54f358de-be81-11e4-9000-7fcbbeb58011.gif"></p>


```sh
curl -L http://git.io/darwin | sh
```


### Options

* __Install [Powerline](https://github.com/powerline/fonts) fonts__

```sh
... | FONTS=true
```

* ___git_ defaults via [_git.io/dotfiles_](https://git.io/dotfiles)__

```sh
... | CONFIG="Your Name;e@mail.com;username"
```

* __Restart Mac after done__

```sh
... | RESTART=true sh
```

* __Skip `homebrew`__

```sh
... | BREW=false sh
```

* __Hide `$HOME` subdirectories__

```sh
... | HOMELESS=true sh
```

* __No Nibernation__

> Removing hibernation may speed things up, but it's a risky business.

```sh
... | NOHIB=true sh
```

* __No 'Are you sure you want to open this application?'__

> Removing this security mechanism could pose a security risk.

```sh
... | NOQ=true sh
```

* __Disable Notification Center__

```sh
... | NC=true sh
```

<p align="right"><a href="#darwin">:arrow_up:</a></p>

### Packages

```sh
... | <PACKAGE_NAME>=true sh
```

<table>
    <tr>
      <td align="center"><a href="https://beyondgrep.com">ACK</a>
      </td>
      <td align="center"><a href="https://caskroom.io">CASK</a>
      </td>
      <td align="center"><a href="https://fishshell.com">FISH</a>
      </td>
      <td align="center"><a href="https://git-scm.com">GIT</a>
      </td>
      <td align="center"><a href="https://www.imagemagick.org">IMGMAGICK</a>
      </td>
      <td align="center"><a href="https://lynx.isc.org/lynx2.8.7/index.html">LYNX</a>
      </td>
      <td align="center"><a href="https://nodejs.org">NODE</a>
      </td>
      <td align="center"><a href="https://github.com/bpinto/oh-my-fish">OMF</a>
      </td>
      </tr>
      <tr>
      <td align="center"><a href="https://github.com/yyuu/pyenv">PYENV</a>
      </td>
      <td align="center"><a href="https://github.com/sstephenson/rbenv">RBENV</a>
      </td>
      <td align="center"><a href="https://mama.indstate.edu/users/ice/tree/">TREE</a>
      </td>
      <td align="center"><a href="https://www.ffmpeg.org">FFMPEG</a>
      </td>
      <td align="center"><a href="http://www.lcdf.org/gifsicle/">GIFSICLE</a>
      </td>
      <td align="center"><a href="https://github.com/b4winckler/macvim">MacVim</a>
      </td>
      <td align="center"><a href="https://www.vagrantup.com">Vagrant</a>
      </td>
      <td align="center"><a href="http://www.videolan.org/vlc/index.html">VLC</a>
      </td>
      <tr>
      <td align="center"><a href="https://github.com/bucaran/darwin/fork">＋</a>
      </td>
      </tr>
    </tr>
</table>

<p align="right"><a href="#darwin">:arrow_up:</a></p>

### Themes

```sh
... | THEME=<name> sh
```

No default themes, but you can install one via `THEME=<name>` from the following list:

+ [flat](https://github.com/ahmetsulek/flat-terminal) by [@ahmetsule](https://github.com/ahmetsulek)
+ [peppermint](?) by [@noahfrederick](https://github.com/noahfrederick)
+ [hemisu](https://github.com/noahfrederick/Hemisu-Terminal-app) by [@noahfrederick](https://github.com/noahfrederick)
+ [monokai](https://github.com/stephenway/monokai.terminal) by [@stephenway](https://github.com/stephenway)
+ [solarized](https://github.com/altercation/solarized) by [@altercation](https://github.com/altercation)
+ [tomorrow-night](https://github.com/chriskempson/tomorrow-theme) by [@chriskempson](https://github.com/chriskempson)
+ [smyck](https://github.com/hukl/Smyck-Color-Scheme) by [@hukl](https://github.com/hukl)
+ [dracula](https://github.com/zenorocha/dracula-theme) by [@zenorocha](https://github.com/zenorocha)

> Note: You are welcome to add more themes to this list, given you submit a PR including the `.terminal` source.

<p align="right"><a href="#darwin">:arrow_up:</a></p>

### About

This is my darwin setup file cherry-picked from [@hjuutilainen](https://github.com/hjuutilainen)/[dotfiles](https://github.com/hjuutilainen/dotfiles/blob/master/bin/osx-user-defaults.sh), [@xero](https://github.com/xero)/[dotfiles](https://github.com/xero/dotfiles), [@mathiasbynens](https://github.com/mathiasbynens)/[dotfiles](https://github.com/mathiasbynens/dotfiles/blob/master/.osx), [@amix](https://github.com/amix)/[vimrc](https://github.com/amix/vimrc) and voracious interweb scavenging.

### License

:metal: Public Domain

_This is free and unencumbered software released into the public domain._

<p align="right"><a href="#darwin">:arrow_up:</a></p>
