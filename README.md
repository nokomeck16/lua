# lua

自作の素材群です。

* 再配布や自作発言は禁止といたします。
* いかなる損害が発生しても、こちらでは責任を負いません。
* <https://commons.nicovideo.jp/material/nc288379> にて、利用登録をおこなってください。
* 派生作品の公表の際は、ニコニ・コモンズID（**nc288379**）を表示してください。

## ダウンロード

1. `Code` をクリックし、`Download ZIP` をクリックする。
1. ダウンロードしたzipファイルを右クリックから`すべて展開`する。
1. **中身の**lua-mainをAviUtlと同じ階層に置く。

※gitが使える方はAviUtlと同じ階層でcloneすればOKです。

## 使い方

* AviUtlの拡張編集を右クリック、`メディアオブジェクトの追加`から`lua-main`下の
オブジェクトを選択することで挿入できます。
* （pop_up.exaを除き）各ファイルをAviUtlの拡張編集にドラッグ＆ドロップすること
でも挿入できます。
* オブジェクトの配置は適宜調整してください。なお、想定画像サイズは 1920 x 1080 です。

---

## 使い方が特殊なもの

* im1696493.png（およびその他のダミー画像）
  * 使用したツールの画像を選択し、拡張編集にドロップしておくと、  
    イスターリャ氏の「コモンズ素材リストアップツール」に見つけてもらえるようになります。  
    ※ただし、so数字は**標準で非対応**
* pop_up.exa
  * 任意のオブジェクトに対するフィルタ効果として使用することができます。
* rice_ball.exo
  * 画像オブジェクトの参照先に、rice_ball.png（同梱）を指定することで使用できます。  
    他の画像を使う場合、その画像に合わせた調整が必要です。
  * このexoファイルは、Layer 2に配置することを想定しています。  
    （画像オブジェクト移動幅（deltaYmax）調整のため）

---

## フォントファイルを参照するもの

* 下記ファイル群は、参照先のフォントファイルがない場合、表示が崩れることがあります。
* 字幕表示オブジェクト等、oov氏の「PSDToolKit」の導入を前提としているものがあります。
* 各フォントをご使用の際は、適用されるライセンスをお確かめください。

---

| .exo / .exa       | font                         |
| -                 | -                            |
| auto_telop.exo    | BIZ UDゴシック                |
| calender.exo      | 源暎ラテミン v2               |
| dummy_base.exo    | 源暎エムゴv2 Black            |
| line_chart.exo    | 源暎エムゴv2 Bold             |
| ^                 | コーポレート・ロゴ ver3 Bold   |
| long_shadow.exo   | 源暎ラテミン v2               |
| progress.exa      | コーポレート・ロゴ ver3 Bold   |
| switch.exo        | コーポレート・ロゴ ver3 Medium |
| synth.exo         | 源暎エムゴv2 Medium           |
| tank_telop.exo    | 源暎エムゴv2 Black            |
| triple_shadow.exo | BIZ UDPゴシック               |
