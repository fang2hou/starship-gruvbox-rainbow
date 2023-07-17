# 🌈 starship-gruvbox-rainbow

<div align="center">
    <div>
       🇺🇸 <a href="README.md">English</a> | 🇯🇵 <a href="README_JP.md">日本語</a> | 🇨🇳 中文
   </div>
    <br>
    <b>🎨 适用于 <a href="https://starship.rs/zh-CN/">Starship</a> 的 Gruvbox Dark 主题</b>
    <img src="screenshot.png" />
</div>

## 🌟 功能

1. Gruvbox Dark 色调
2. 针对各个操作系统的独特图标
   - macOS, Windows, Arch, Ubuntu, SUSE, Raspbian, Mint, Manjaro, Gentoo, Alpine, Amazon, Andriod, Artix, CentOS, Debian.
3. 自定义的环境上下文
   - C, Rust, Go, Node.js, PHP, Java, Kotlin, Haskell, Python, Docker

## 🚚 安装

1. 如果存在当前的 starship 配置文件，备份一下。

   ```shell
   [[ -f "$HOME/.config/starship.toml" ]] \
   && mv ~/.config/starship.toml ~/.config/starship.bak.toml
   ```

2. 下载主题并设定为当前 starship 配置。

   ```shell
   mkdir -p ~/.config && curl -o ~/.config/starship.toml \
   https://raw.githubusercontent.com/fang2hou/starship-gruvbox-rainbow/main/starship.toml
   ```

3. 自定义主题。（_可选_）

   ```shell
   vim ~/.config/starship.toml
   ```

## 💖 感谢

此主题深受下面的工作启发：

- [Gruvbox](https://github.com/morhetz/gruvbox)
- [Tokyo Night](https://starship.rs/presets/tokyo-night.html)
- [Pastel Powerline](https://starship.rs/presets/pastel-powerline.html)

## 🪪 协议

[MIT](LICENSE)
