# TL;DR

karabiner_elementsのkinesis用のキー配置入れ替えconfig file。

# USAGE

1. `~/.config/karabiner/assets/complex_modifications`に`personal_kinesis.json`を配置
2. karabiner_elementsの`Preferences`の`complex_modifications`タブに移動
3. `Add rule`ボタンからkinesis用の設定を`Enable`にする

# 現行のルール

* PageDownを押すと右のタブに、Endを押すと左のタブに移動する  
  PageDown, Endは使用頻度が低いので、タブの移動に利用
* non_us_backslashを~に変更する  
  バックスラッシュがPの横の他にXの下にもあるが、Xの下のキーは`§`キーになっている  
  使用頻度は低いが`~`として利用

# TODO

* DeletをFNに変更する  
  単一キーの変更は設定が容易さからkarabiner_elements側の機能で補っている  
  タイプミス防止と特殊操作のためにFNに変更
* Homeをescapeに変更する  
  単一キーの変更は設定が容易さからkarabiner_elements側の機能で補っている  
  使用頻度は高いが、kinesisのescapeは押しにくいので親指で押すようにする
* PageUpを何かに変更する  
  研究中

