# 🌈 starship-gruvbox-rainbow

<div align="center">
    <div>
       🇺🇸 English | <a href="README_JP.md">🇯🇵 日本語</a> | <a href="README_CN.md">🇨🇳 中文</a>
    </div>
    <br>
    <b>🎨 Gruvbox Dark theme for Starship</b>
    <img src="screenshot.png" />
</div>

## 🚚 Install

1. Backup current Starship profile if it exists.

   ```shell
   [[ -f "$HOME/.config/starship.toml" ]] \
   && mv ~/.config/starship.toml ~/.config/starship.bak.toml
   ```

2. Download the theme and set it as your Starship config.

   ```shell
   mkdir -p ~/.config && curl -o ~/.config/starship.toml \
   https://raw.githubusercontent.com/fang2hou/starship-gruvbox-rainbow/main/starship.toml
   ```

3. Customize the theme. (_Optional_)
   ```shell
   vim ~/.config/starship.toml
   ```

## 💖 Thanks

The theme is heavily inspired by the following works:

- [Gruvbox](https://github.com/morhetz/gruvbox)
- [Tokyo Night](https://starship.rs/presets/tokyo-night.html)
- [Pastel Powerline](https://starship.rs/presets/pastel-powerline.html)

## 🪪 License

[MIT](LICENSE)
