# 第5回
## 負けるなこうかとん(ex05/fight_kokaton.py)
### ゲーム概要

- ex04/dodge_bomb.pyを実行すると,1600×900のスクリーンに草原が描画され，こうかとんを移動させ飛び回る爆弾から逃げるながら，的にビームを当てるゲーム
- こうかとんが爆弾や敵と接触するとゲームオーバーとなる
### 操作方法
- 矢印キーでこうかとんを上下左右に移動する
- スペースキーでビームを発射する
### 追加機能
- 敵の配置 : 敵はプレイヤーを追尾する．定期的に爆弾を放出する．
- 爆弾の生成 : 爆弾は敵が定期的にランダムな方向に生成する．生成位置は敵の位置になる．
- 弾を撃つ : スペースキーで前方に弾を打つことができ，的に当てると倒すことができる．
- ゲームオーバー表示 : 爆弾に接触するか妖怪と接触すると'GAME OVER'の文字が表示される．
- クリアー表示:敵に弾を当てるとクリアーとなる
- リスタート機能 : ゲームオーバーになった状態かクリアーになった状態で'Rキー'を押すと新しくゲームを始めることができる． 
- りんごを集める機能 : フィールド上のランダムな位置にりんごが生成される．これを取ると敵が放った爆弾がすべて消える
- 