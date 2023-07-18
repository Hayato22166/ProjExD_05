# ブロックアクションゲーム
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1


## ゲームの概要
白黒の世界をブロックの主人公が冒険するゲーム

## ゲームの実装
### 共通基本機能
* 地面と主人公の描画、横移動(矢印キーにより)

### 担当追加機能
* Field作成(担当:かしわぎ) : 足場や壁を作るクラス
* Goal作成(担当:きじま)：ゴールできるようになる
* end作成(担当:わたなべ) : ゲーム終了時の文字生成、ゲームのクローズ
* jump作成(担当:かない)　: 　ジャンプができるようになる
* Enemy作成(担当:もとはし)　:　敵の生成
* time作成(担当:きじま)：制限時間ができました
* Character Animation追加(担当:かしわぎ) : キャラクターの移動にアニメーション（エフェクト）を追加

### ToDo  実装しようと思ったけど時間が足りずできなかったことなど
- [ ] 穴に落下したときの死亡処理
- [ ] 残気処理
- [ ] 主人公攻撃処理
- [ ] 敵攻撃処理
- [ ] 横スクロール処理

### メモ  グループメンバーへの連絡など

