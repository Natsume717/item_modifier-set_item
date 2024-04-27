# item_modifier-set_item
item_modifierの1項目であるset_item_sampleのサンプルになります。

詳しくはブログ記事『[【マイクラ】set_itemでアイテムをすり替える【item_modifier】](https://natsumake.com/item_modifier-set_item/)』を参考にしてください。

<h3>概要</h3>
対称としたアイテムのコンポーネントと個数を変更せずに、指示したアイテムへと変更します。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

名前が付いているエメラルドが64個付与されますので、それを手に持った状態で以下のコマンドを実行します。

```copy
/item modify entity @s weapon.mainhand sample:set_item
```

名前と個数が元のままでエメラルドからダイヤモンドに変更していることが確認できるはずです。
