# temperature-management
# 体温管理アプリケーション

娘の通う幼稚園では毎朝体温を測って園バスの添乗の先生、クラスの担任に渡すことになっています。
現在は毎朝、日付、クラス、名前、体温を書いたメモ二枚（バス添乗用、クラス担任用）用意し
バス乗車の際に手渡ししています。（バス登園は添乗の先生に手渡し、歩き登園は園入り口の箱にクラス別に提出）
非常に面倒なので、あらかじめユーザー登録をした上でスマホからその日の体温だけを入力、職員はバスコース別、
クラス別にそれぞれ閲覧できる機能を持ったアプリケーションを作成したいと思います。

### 機能 
*create:*  
```
ユーザー登録(名前、クラス)  
ユーザーによる体温入力  
＊日付ごと入力なのでカレンダーの機能を持っている
```
*read:*
```
管理者がグループごと(バスコース別、クラス別)にリストを閲覧する機能    
ユーザーが自分の登録した体温記録を閲覧する機能  
```
update: 
```　　
ユーザによる記録の更新、変更　　
```
*delete:*  
```
一定の期間(直近一か月)が過ぎたら記録を自動削除
卒園、転園等の場合ユーザーをリストから削除する
```






