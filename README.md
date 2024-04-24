# item_modifier-toggle_tooltips
item_modifierの1項目であるtoggle_tooltipsのサンプルになります。

詳しくはブログ記事『[【マイクラ】toggle_tooltipsでアイテム情報の切り替え【item_modifier】](https://natsumake.com/item_modifier-toggle_tooltips/)』を参考にしてください。

<h3>概要</h3>
アイテムのツール情報を非表示・表示を切り替えることが可能です。

具体的には、trim、不可壊、設置可能、破壊可能、エンチャント（ツール、本の2種）、染色、attributeが挙げられます。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

8種類のアイテムが付与されますので、それぞれを手に持った状態で以下のコマンドを実行してください。<br>
末尾がtureの場合はその表記を表示するようになり、falseの場合には表記が非表示になります。

<h4>不可壊な鉄のツルハシ(不可壊)</h4>

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/unbreakable/false
```

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/unbreakable/true
```

<h4>金のツルハシ（破壊可能）</h4>

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/can_break/false
```

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/can_break/true
```

<h4>ダイヤモンドブロック（設置可能）</h4>

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/can_place_on/false
```

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/can_place_on/true
```

<h4>皮の上着（色）</h4>

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/dyed_color/false
```

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/dyed_color/true
```

<h4>ダイヤモンド（attribute）</h4>

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/attribute_modifiers/false
```

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/attribute_modifiers/true
```

<h4>鉄の剣（エンチャント）</h4>

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/enchantments/false
```

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/enchantments/true
```

<h4>エンチャントされた本（エンチャント）</h4>

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/stored_enchantments/false
```

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/stored_enchantments/true
```

<h4>ダイヤモンドのチェストプレート（装飾）</h4>

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/trim/false
```

```copy
/item modify entity @s weapon.mainhand sample:toggle_tooltips/trim/true
```
