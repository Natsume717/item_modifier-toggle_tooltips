# item_modifier-toggle_tooltips
item_modifierの1項目であるtoggle_tooltipsのサンプルになります。

~詳しくはブログ記事『[]()』を参考にしてください。~<br>
現在執筆中

<h3>概要</h3>
アイテムのツール情報を非表示・表示を切り替えることが出来ます。

具体的には、trim、不可壊、設置可能、破壊可能など。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

不可壊な鉄のツルハシが付与されますので、それを手に持った状態で以下のコマンドを実行します。<br>
すると不可壊の表記が消えます。

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips-unbreakable_false
```

表示させたい場合には、以下のコマンドを実行します。

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips-unbreakable_true
```

---

