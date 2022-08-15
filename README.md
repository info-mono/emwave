<p align="center"><a href="https://github.com/info-mono/emwave"><img src="https://user-images.githubusercontent.com/43980777/184646552-b75357f3-d3e1-4798-baed-3d30c8f40036.png"></a></p>
<p align="center">Emwave with custom string</p>
<p align="center">
  <a href="https://github.com/info-mono/emwave/blob/main/LICENSE"><img src="https://img.shields.io/github/license/info-mono/emwave?labelColor=383838&color=585858&style=for-the-badge" alt="License: GPL-3.0"></a>
  <a href="https://gist.github.com/NNBnh/9ef453aba3efce26046e0d3119dab5a7#development-completed"><img src="https://img.shields.io/badge/development-completed-%23585858.svg?labelColor=383838&style=for-the-badge&logoColor=FFFFFF" alt="Development completed"></a>
</p>

## 💡 About

**Emwave** script is originally written by Ilya144 as [a pull request](https://github.com/stark/Color-Scripts/pull/18) for [Color-Scripts](https://github.com/stark/Color-Scripts).

This is an enhanced version of it with option to set display string. It also use `sh` instead of `bash` for more portability.

Try it:

```sh
sh -c "$(curl -fsLS https://info-mono.github.io/emwave)" -- <string>
```

If you just want a quick print of the default emwave, try:

```sh
curl -fsLS https://info-mono.github.io/emwave/default
```

## 🚀 Setup

### 🧾 Dependencies

- [POSIX compliance shell (`sh`, `bash`, `zsh`, ...)](https://wikipedia.org/wiki/Unix_shell)
- [`sed`](https://wikipedia.org/wiki/Sed)

### 📥 Installation

#### 🔧 Manually

Option 1: using `curl`

```sh
curl https://raw.githubusercontent.com/info-mono/emwave/main/bin/emwave > ~/.local/bin/emwave
chmod +x ~/.local/bin/emwave
```

Option 2: using `git`

```sh
git clone https://github.com/info-mono/emwave.git ~/.local/share/emwave
ln -s ~/.local/share/emwave/bin/emwave ~/.local/bin/emwave
```

#### 📦 Package manager

For [Bpkg](https://github.com/bpkg/bpkg) user:

```sh
bpkg install info-mono/emwave
```

For [Basher](https://github.com/basherpm/basher) user:

```sh
basher install info-mono/emwave
```

## ⌨️ Usage

Run `emwave` in the terminal:

```sh
emwave
```

```sh
emwave <string>
```

## 💌 Credits

Special thanks to:
- [**Original Emwave**](https://github.com/stark/Color-Scripts/pull/18) by [Ilya144](https://github.com/ilya144)

<br><br><br><br>

---

> <h1 align="center">Made with ❤️ by <a href="https://github.com/info-mono"><code>@info-mono</code></a></h1>
>
> <p align="center"><a href="https://www.buymeacoffee.com/nnbnh"><img src="https://img.shields.io/badge/buy_me_a_coffee%20-%23F7CA88.svg?logo=buy-me-a-coffee&logoColor=333333&style=for-the-badge" alt="Buy Me a Coffee"></a></p>
