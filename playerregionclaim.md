# 土地の保護
## 使い方
1. `/playerregion togglewand` を実行
2. 木のくわを使ってWorldEditと同じように右クリック左クリックで2地点を選択(スマホだと、タップと長押しです！、コントローラの場合は使うのとパンチするボタンです！)
3. `/playerregion checkprice` を実行し、値段を確認
4. `/playerregion claim <id>` を実行することで、ダイヤを消費し土地を保護できます、保護した土地の名前はidに入力した文字列になります

## コマンド一覧
* `/playerregion togglewand` wandmodeを有効にするか無効にするか変更できます
* `/playerregion claim <id>` ダイヤを消費し土地を保護できます、保護した土地の名前はidに入力した文字列になります
* `/playerregion remove <id>` 土地保護を解除します、その際設定された分のダイヤモンドが返ってきます(Configファイルで量を調整できます)
* `/playerregion list` 保護している土地を確認します
* `/playerregion checkprice` 選択している大きさで土地を保護する場合の値段か確認します(Configファイルで値段を調整できます)
* `/playerregion memberlist <id>` 保護している土地のメンバーを確認します
* `/playerregion addmember <id> <player>` 保護している土地にメンバーを追加します
* `/playerregion removemember <id> <player>` 保護している土地のメンバーを消去します
