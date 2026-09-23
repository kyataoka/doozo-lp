# Doozo — 公開サイト

Doozo の紹介ページと、プライバシーポリシー・利用規約。GitHub Pages で
**<https://doozo.kyatatata.com>** に公開します。

*The public website for Doozo, an iOS app for handing over your iPhone with only
the photos you choose. Japanese is the authoritative text; the English pages are
translations of it.*

|  | 日本語 | English |
| --- | --- | --- |
| 紹介ページ | [/](https://doozo.kyatatata.com/) | [/en/](https://doozo.kyatatata.com/en/) |
| プライバシーポリシー | [/privacy/ja/](https://doozo.kyatatata.com/privacy/ja/) | [/privacy/en/](https://doozo.kyatatata.com/privacy/en/) |
| 利用規約 | [/terms/ja/](https://doozo.kyatatata.com/terms/ja/) | [/terms/en/](https://doozo.kyatatata.com/terms/en/) |

## 文書の扱い

- **日本語が正文**です。英語は訳であり、食い違う場合は日本語が優先する旨を各文書の冒頭に記しています。日本語を改めたときは英語も同時に改めます
- 法務文書には**現に提供している機能**を記します。予定や検討中の内容は含めません
- 紹介ページで挙げる機能も、提供済みのものに限ります

## URL は変更しません

`privacy` と `terms` の 4 つの URL は、配布したアプリの設定とペイウォールから直接開かれます。プライバシーポリシーの URL は App Store Connect にも登録します。パスを変えると、すでにお使いの版から文書を開けなくなるため、各文書の permalink はファイルパスから導かず固定しています。

同じ理由から、サイトのアドレスはリポジトリ名から独立させ、独自ドメインを割り当てています（veiler の教訓）。

## 構成

| パス | 内容 |
| --- | --- |
| `index.html`, `en/index.html` | 紹介ページ。レイアウトは `_layouts/landing.html` |
| `privacy/*.md`, `terms/*.md` | 法務文書。レイアウトは `_layouts/document.html` |
| `app-ads.txt` | AdMob のパブリッシャーの宣言（veiler と同じ 1 行） |
| `assets/icon.png` | アイコン（`design/icon/AppIcon.icon` から ictool で書き出し） |
| `assets/shots/` | 画面写真。`ja/`・`en/` は言語で変わる画面、直下は言語に依らない手渡し画面。明るい・暗いの両方を置き、テーマに合わせて片方を出す |
| `_includes/soon-badge.html` | 「App Storeで近日公開」の表示。公開したら App Store のバッジに差し替える |

レイアウトは veiler-lp のものを写しています。

## 画面写真の中の写真

シミュレータで撮った画面写真に写っている写真は、Unsplash の写真です（Unsplash License。帰属表示は不要ですが、サイトの下部に出典を書いています）。

| 写真 | 撮影者 |
| --- | --- |
| <https://unsplash.com/photos/agkblvPff5U> | Linh Nguyen |
| <https://unsplash.com/photos/_WiFMBRT7Aw> | Jerry Adney |
| <https://unsplash.com/photos/gkT4FfgHO5o> | Paul Jarvis |
| <https://unsplash.com/photos/D76DklsG-5U> | Kenneth Thewissen |
| <https://unsplash.com/photos/hlnucYOsL-c> | Matteo Minelli |
| <https://unsplash.com/photos/Ven2CV8IJ5A> | Paul Jarvis |
| <https://unsplash.com/photos/8wTPqxlnKM4> | André Spieker |
| <https://unsplash.com/photos/UWRqlJcDCXA> | Carli Jean |
| <https://unsplash.com/photos/FjjUVn_KHLU> | Glen Carrie |
| <https://unsplash.com/photos/-vq7mi4oF0s> | Rula Sibai |
| <https://unsplash.com/photos/OxzhYtL-00Y> | Alexander Shustov |
| <https://unsplash.com/photos/n7n-nkadHRM> | Chris Brignola |
| <https://unsplash.com/photos/0fjGQmYCRW8> | Austin Ban |
| <https://unsplash.com/photos/V0yAek6BgGk> | Go Wild |
| <https://unsplash.com/photos/NYDo21ssGao> | Paul Jarvis |
| <https://unsplash.com/photos/yNGQ830uFB4> | Tim de Groot |
