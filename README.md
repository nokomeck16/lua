# lua

自作の素材群です。

* ご利用の際は、[ライセンスファイル](LICENSE)をご確認ください。
* ニコニコ コンテンツツリーへの登録は任意です。ご登録の際は、**nc288379**をご利用ください。

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

* dummy_im1696493.png（およびその他のダミー画像）
  * 使用したツールの画像を拡張編集にドラッグ＆ドロップしておくと、  
    イスターリャ氏の「コモンズ素材リストアップツール」に見つけてもらえるようになります。  
    ※**soで始まるID**に関しては、上記に加えてリストアップツール側にも設定が必要です。
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

| .exo / .exa | font(s)  |
| -  | -  |
| auto_telop.exo  | BIZ UDゴシック
| calender.exo  | 源暎ラテミン v2
| dummy_base.exo  | 源暎エムゴv2 Black
| line_chart.exo  | 源暎エムゴv2 Bold <br /> コーポレート・ロゴ ver3 Bold
| long_shadow.exo  | 源暎ラテミン v2
| progress.exa  | コーポレート・ロゴ ver3 Bold
| switch.exo  | コーポレート・ロゴ ver3 Medium
| synth.exo  | 源暎エムゴv2 Medium
| tank_telop.exo  | 源暎エムゴv2 Black
| triple_shadow.exo  | BIZ UDPゴシック
