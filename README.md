JavaScriptで紙吹雪を降らす
===

使い方
---
1.Kamihubuki.jsを読み込む
```html
<script src="./js/Kamihubuki.js"></script>
```

2.Kamihubukiオブジェクトのrunメソッドを使用する
```javascript
Kamihubuki.run();
```
これだけで画面全体にカラフルな紙吹雪が舞い散ります。さらにオプションでいろいろな設定ができます。


デモページ
---
https://yuki-sakaguchi.github.io/Kamihubuki.js/


オプション
---
・canvasに表示する紙吹雪の数
```javascript
Kamihubuki.options.viewCount = 1000; // デフォルトは500
```

・色のランダムフラグをONにする
```javascript
Kamihubuki.options.randomColor = true; // デフォルトはfalse
```

・紙吹雪の色を設定（色のランダムフラグがOFFの場合のみ有効)
```javascript
Kamihubuki.options.fill = "#000"; // デフォルトはyellow



