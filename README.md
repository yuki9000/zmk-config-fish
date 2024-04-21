# おさかなキーボード  
これは、[おさかなキーボード](https://o24.works/fish/)のためのZMK Firmareの設定リポジトリです。  
  
## 書き換えていいファイル  
### [fish.keymap](https://github.com/TakumaOnishi/zmk-config-fish/blob/master/config/boards/shields/fish/fish.keymap)  
キーの割り当てや入力の内容を設定できます。このファイルを視覚的に編集できる[キーマップエディター](https://o24.works/fish/editor/)も活用してください。  
### [fish.conf](https://github.com/TakumaOnishi/zmk-config-fish/blob/master/config/boards/shields/fish/fish.conf)  
スリープ時間、検出名など、キーボード本体の挙動を設定できます。  
### [Kconfig.defconfig](https://github.com/TakumaOnishi/zmk-config-fish/blob/master/config/boards/shields/fish/Kconfig.defconfig)
親機の左右を変えることができます。  
  
## デフォルトキーマップ
![keymap](https://github.com/TakumaOnishi/zmk-config-fish/assets/85474111/142e9807-6d93-41ce-8b9a-6d23d5f8b853)　　
 - 単にキーを押すと、青字の入力になります。英字は[大西配列](https://o24.works/layout/)です。　　
 - 黄色い丸（BackSpace）を押しながらキーを押すと、黄色字の入力になります。　　
 - 赤い丸（Space）を押しながらキーを押すと、赤字の入力になります。　　
 - その両方を押しながらキーを押すと、灰色字の入力になります。　　
 - AとO、TとNを同時に押すとそれぞれ日本語IMEのオフ、オンが入ります。　　
 - ホールドタップ複合キーは、短く押してから長押しすると連続入力が入ります。
  
キーマップを書き換えておさかなを更新する手順は[ユーザーガイド](https://o24.works/fish/guide/)を参照してください。
