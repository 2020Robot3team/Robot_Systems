# Robot_Systems
ロボットシステム学の課題で作成したプログラムです。
LEDの点滅の時間を調整しモールス信号として伝えます。
# 環境
- Rasberry Pi 4 ModelB
- Ubuntu 18.04 LTS
- LED
- ブレッドボード
- 300Ω抵抗　

# 実行手順
`$git clone<https://github.com/2020Robot3team/Robot_Systems>より` <br>
`リポジトリのインストール `<br>
`$cd Robot_Systems `<br>
`$make`<br>
`$sudo insmod myled.ko `<br>
`$sudo mknod/dev/myled0 `<br>
`$sudo chmod 666/dev/myled0` <br>
`$echo 科目系 > /dev/myled0で実行` <br>
    <br>
- ロボットシステム学 `”r”`
- メカニクス2 `"m"`
- 物理 `"p"`
- 英語 `"e"`
- ロボットマニュピュレータ`"M"`
# 実行例
英語の場合、頭文字のeを入力　<br>
`(例)$echo e > /dev/myled0`
# 動画
ロボットシステム学のrを入力　<br>
<https://youtu.be/ZRvTmj3eVUU><br>
メカニクス2のmを入力　<br>
<https://youtu.be/yqfVk1uDf8c>

# ライセンス
GNU General Public License v3.0
<https://github.com/2020Robot3team/Robot_Systems/blob/main/LICENSE>
