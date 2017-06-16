# JavaScriptで紙吹雪を降らす



## 使い方
1.Kamihubuki.jsを読み込む
~~~~
<script src="./js/Kamihubuki.js"></script>
~~~~

2.Kamihubukiオブジェクトのrunメソッドを使用する
~~~~
Kamihubuki.run();
~~~~

これだけで画面全体にカラフルな紙吹雪が舞い散ります。さらにオプションでいろいろな設定ができます。



## デモページ
https://yuki-sakaguchi.github.io/Kamihubuki.js/



## オプション
・canvasに表示する紙吹雪の数を設定
~~~~
Kamihubuki.options.viewCount = 1000; // デフォルトは500
~~~~

・紙吹雪の色をランダムに設定
~~~~
Kamihubuki.options.randomColor = true; // デフォルトはfalse
~~~~

・紙吹雪の色を設定（randomColorがfalseの場合のみ有効)
~~~~
Kamihubuki.options.fill = "#000"; // デフォルトはyellow
~~~~
