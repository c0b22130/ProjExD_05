# ProjExD_05

# ふらっとん
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
Flappy Birdがモチーフ。こうかとんが土管に当たらないようにジャンプさせるゲーム

## ゲームの実装
###共通基本機能
* 主人公キャラクターに関するクラス+描画
* 土管に関するクラス+描画
* 背景描画
### 担当追加機能
* 点数追加: 土管を通過した際に1ポイント獲得
* 一定点数で無敵(+表示変更): 50ポイントとか取れたら無敵
* コイン機能: コイン集め　浮いてる
* 良いアイテム機能: 土管の幅広げるとか
* 悪いアイテム機能: ジャンプ量が増加する
* gameover画像追加: こうかとんが土管に当たったらgameoverとスコアを表示
### ToDo
- [ ] 点数機能
- [ ] 無敵機能
- [ ] コイン機能
- [ ] アイテム(良)機能
- [ ] アイテム(悪)機能
- [x] gameover画像追記
### メモ
