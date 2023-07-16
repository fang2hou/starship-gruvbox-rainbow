# 🌈 starship-gruvbox-rainbow

<center>
    <div>
       <a href="README.md">🇺🇸 English</a> | 🇯🇵 日本語 | <a href="README_CN.md">🇨🇳 中文</a>
    </div>
    <br>
    <b>🎨 Starship 用 Gruvbox Dark テーマ</b>
    <img src="screenshot.png" />
</center>

## 🚚 インストール

1. 設定がすでに存在する場合、バックアップを作る。

   ```shell
   [[ -f "$HOME/.config/starship.toml" ]]\
   && mv ~/.config/starship.toml ~/.config/starship.bak.toml
   ```

2. テーマをダウンロードして、Starship コンフィグとして設定する。

   ```shell
   curl -o ~/.config/starship.toml \
   https://raw.githubusercontent.com/fang2hou/starship-gruvbox-rainbow/main/starship.toml
   ```

3. 各種カスタマイズ。（_オプション_）
   ```shell
   vim ~/.config/starship.toml
   ```

## 💖 謝辞

このテーマのデザイン・作成は以下のプロジェクトから莫大なインスピレーションを得ました。

- [Gruvbox](https://github.com/morhetz/gruvbox)
- [Tokyo Night](https://starship.rs/presets/tokyo-night.html)
- [Pastel Powerline](https://starship.rs/presets/pastel-powerline.html)

## 🪪 ライセンス

[MIT](LICENSE)
