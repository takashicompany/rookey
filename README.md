# Rookey

<img src = "https://github.com/takashicompany/rookey/blob/master/images/daihuku/DSC01480_2.jpg?raw=true" width = "600px" />


Rookey(ルーキー)は9キーのマクロパッドです。  
1枚のPCBから回路プレート、スイッチプレート、スペーサーを切り出して組み立てます。  
シンプルな構造のため組み立てやすく、自作キーボードの組み立てに慣れていない方でも容易に完成させることができます。  
入門用としてはもちろんのこと、指を自然に置けるキー配置なため永く使える一台となっております。  
リバーシブル基板ですので、利き腕や使用シーンにあわせた使い方を実現しています。  
オプションでロータリーエンコーダを取り付けることも可能です。  

<img src = "https://github.com/takashicompany/rookey/blob/master/images/01.jpg?raw=true" width = "400px" />
<img src = "https://github.com/takashicompany/rookey/blob/master/images/daihuku/DSC01468.jpg?raw=true" width = "400px" />
<img src = "https://github.com/takashicompany/rookey/blob/master/images/02.jpg?raw=true" width = "400px" />
<img src = "https://github.com/takashicompany/rookey/assets/4215759/54fb3733-e7ac-41b1-814a-2b16168d4312" width = "400px" />

## 入手する前に当ビルドガイドをご一読ください。

入手する前・組み立てる前にこのビルドガイドの全てを一読ください。  
頭の中で実際の作業工程をイメージして読み進めると、実際の作業の際に滞ることが少なくなります。  
不明点などがありましたら、XやBoothのメッセージ等にてお気軽にご質問ください。  
また、後述のYoutube動画もご覧になられると、より確実に組み立てることができます。  

## YouTube
[Daihuku Keyboard 「【簡単＆安い】自作キーボード作ってみた Rookey編 | Rookey : Macropad Review」](https://www.youtube.com/watch?v=L61mhWEmTEg)
[![Youtube](http://img.youtube.com/vi/L61mhWEmTEg/0.jpg)](https://www.youtube.com/watch?v=L61mhWEmTEg)

## 組み立てに必要な部品

キットに含まれていないものはご自身でご用意ください。  

以下は必須の項目の説明です。
|記号|説明|
|:--|:--|
|◯|無いと動作しません。キットに含まれていないものはご自身でご用意ください。|
|△|無くても動作させられますが、用意すると組み立てさやメンテナンス性が向上します。初心者の方はご用意頂くのが確実です。|
|?|使用スタイルに併せて、選択可能です。|

|画像|部品名|個数|必須|備考|
|:--|:--|:--|:--|:--|
|<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6617.jpg?raw=true" width = "1200px" />|Rookey PCB|1|◯|1枚で回路プレート・スイッチプレート・スペーサーになります。|
|<img src = "https://github.com/takashicompany/rookey/assets/4215759/1fe9f782-f64b-4291-b03c-e1532b05013b" width = "1200px" />|[Pro Micro](https://shop.yushakobo.jp/products/21)|1|◯|キーボードの頭脳部分を司る部品です。ピン数は2列12穴です。どれを買っていいか分からない場合は[コンスルー付きのセット](https://shop.yushakobo.jp/products/21)の購入を推奨します。|
|<img src = "https://github.com/takashicompany/rookey/raw/master/images/build/IMG_6635.jpg?raw=true" width = "1200px" />|[タクトスイッチ](https://shop.yushakobo.jp/products/a0800ts-01-1)|1|△|キーボードにファームウェアを書き込む際に利用するスイッチです。取り付けなくともピンセットを用いることでファームウェアを書き込めます。詳細は[こちら](https://github.com/takashicompany/rookey/blob/master/README.md#5-%E3%83%AA%E3%82%BB%E3%83%83%E3%83%88%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91)。|
|<img src = "https://github.com/takashicompany/rookey/assets/4215759/131d8bc9-4716-4d8d-8934-5a90197babb9" width = "1200px" />|[コンスルー](https://shop.yushakobo.jp/products/31)|2|◯|回路プレートとPro Microを接続する端子です。Pro Microに付属するピンヘッダでの取り付けも可能ですが、作業ミスや故障した際の取り替えが容易になりますので、**コンスルーの使用を強く推奨します。ピンヘッダでの取り付けは当キーボードと当ビルドガイドではサポートしません。** コンスルーの必要な高さはPro Microによって異なりますので、販売元にご確認ください。コンスルーについての詳細な説明は[こちら](https://scrapbox.io/self-made-kbds-ja/%E3%82%B3%E3%83%B3%E3%82%B9%E3%83%AB%E3%83%BC)をご一読ください。併せて[取り付け方の説明](https://yushakobo.zendesk.com/hc/ja/articles/360044233974-%E3%82%B3%E3%83%B3%E3%82%B9%E3%83%AB%E3%83%BC-%E3%82%B9%E3%83%97%E3%83%AA%E3%83%B3%E3%82%B0%E3%83%94%E3%83%B3%E3%83%98%E3%83%83%E3%83%80-%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91%E6%96%B9%E3%82%92%E6%95%99%E3%81%88%E3%81%A6%E4%B8%8B%E3%81%95%E3%81%84)も目を通しておくと作業がスムーズに進められます。|
|<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6653.jpg?raw=true" width = "1200px" />|[MX互換キースイッチ](https://shop.yushakobo.jp/collections/all-switches)|9|◯|キーの動作部品です。キーの押下を電気信号でPro Microに伝えます。ホットスワップに非対応ですので、一度ハンダ付けすると取り外しの際にはハンダ吸い取り線などを用いる必要があります。|
|<img src = "https://github.com/takashicompany/rookey/assets/4215759/eafcac57-31fe-4c3a-829c-3cbf697e00ff" width = "1200px" />|[MX互換キーキャップ](https://shop.yushakobo.jp/collections/keycaps)|9|◯|指がキーに触れる部品です。全てのキーが1u(1マス)サイズです。|
|<img src = "https://github.com/takashicompany/rookey/raw/master/images/build/IMG_6672.jpg?raw=true" width = "1200px" />|[ウレタンクッション](https://shop.yushakobo.jp/products/a0800ur-01-6)|4|△|底面に貼り付けることでキーを押した時に滑らなくなります。100均ショップなどで購入したものでも代用可能です。|
|<img src = "https://github.com/takashicompany/rookey/raw/master/images/build/IMG_6666.jpg?raw=true" width = "1200px" /> |[ロータリーエンコーダ](https://shop.yushakobo.jp/collections/all-keyboard-parts/Encorder)|1|?|ノブを指で回すことでの入力が可能です。スクロール操作などに適しています。Pro Microの手前側のキースイッチをロータリーエンコーダに変更することが可能です。**不要な方は用意する必要はありません。**|

## 組み立てに必要な道具

何を用意してよいか分からない方は、[こちら](https://shop.yushakobo.jp/products/a9900to)を購入するのが確実です。

|道具|備考|
|:--|:--|
|ハンダごて|おすすめは[HAKKO FX-600](https://www.hakko.com/japan/products/hakko_fx600.html)です。[こて台](https://www.hakko.com/japan/products/hakko_kote_board.html)もあると、より作業をスムーズに進められます。|
|ハンダ|[こちら](https://www.goot.jp/products/detail/se_06008)などを使う方が多いようです。|
|ピンセット|100均などで手に入るものでも充分利用できるかと思います。|
|ニッパー|100均などで手に入るものでも充分利用できるかと思いますが、1000円程度ものを買っても損では無いかと思います。|

## あるとさらに完成度が高くなる道具
|道具|備考|
|:--|:--|
|棒ヤスリ|基板の縁にあるバリを削るのに使います。|
|サインペン|基板の縁を塗るとより美しくなります。|
|マスキングテープ|キースイッチをハンダ付けする際に役立ちます。|

## 組み立て方

### 1. 基板の左右と表裏を確認する

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6617.jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6618.jpg?raw=true" width = "600px" />

基板の左右を決める。

### 2. 基板を切り離す

基板を回路プレート・スイッチプレート・スペーサーに切り離します。  
まずは、スペーサーと回路プレート or スイッチプレートを切り離します。  
基板を折り曲げると2つに割れるかと思います。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6619.jpg?raw=true" width = "600px" />

スペーサーはペンチなどで折り曲げるとプレートから切り離せます。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6620.jpg?raw=true" width = "600px" />

スペーサーは組み立てに使いますので捨てずに保持してください。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6621.jpg?raw=true" width = "600px" />

以下のように部品を分割できたら完了です。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6622.jpg?raw=true" width = "600px" />

### 3. プレートをヤスリがけする

この項目は行わなくても動作に支障はありません。  
完成後に行うこともできます。  

プレートの切り離した箇所をヤスリがけします。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6623.jpg?raw=true" width = "600px" />

回路プレート、スイッチプレートの両方を磨きます。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6624.jpg?raw=true" width = "600px" />

### 4. プレートを染める

この項目もスキップ可能です。完成後に行っても差し支えないかと思います。

プレートの側面を表面と同じ色のサインペンなどで塗りつぶします。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6626.jpg?raw=true" width = "600px" />

側面と表面の色をあわせることによって、完成度が高まります。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6627.jpg?raw=true" width = "600px" />

### 5. リセットスイッチの取り付け

ファームウェアを書き込む際にPro Microを初期化します。一般的にはPCBにタクトスイッチを取り付けるのが主流となっています。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6635.jpg?raw=true" width = "600px" />

タクトスイッチを取り付けなくても、ピンセットなどでリセットスイッチのハンダ付け穴を導通させることで、リセットスイッチを押したことと同じ挙動となります。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6634.jpg?raw=true" width = "600px" />

Rookeyでのリセットスイッチの取り付けはお好みで構いません。

リセットスイッチ穴はPro Micro取付箇所の手前側にあります。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6637.jpg?raw=true" width = "600px" />

タクトスイッチを回路プレートの表側から刺します。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6636.jpg?raw=true" width = "600px" />

回路プレートを裏返してタクトスイッチの足が出ていることを確認し、ハンダ付けを行います。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6644.jpg?raw=true" width = "600px" />

### 6. Pro Microの取り付け

MCUとしてPro Microを取り付けます。
MCUはMicro Control Unitの略で、端的に言うとキーボードの頭脳部分となります。  

Pro Microを右に取り付ける場合は、Pro Microのチップ側が回路プレート側を向くように置きます。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6628.jpg?raw=true" width = "600px" />

Pro Microを左に取り付ける場合は、Pro Microのチップ側が表を向くように置きます。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6630.jpg?raw=true" width = "600px" />

例に用いたPro Microは[こちら](https://shop.yushakobo.jp/products/21)になります。  
Pro Microによってはピンの配置が異なることがありますので、回路プレートのピンの印字と称号した上で取り付けください。

Pro Microを取り付ける際は[コンスルー](https://shop.yushakobo.jp/products/31?variant=37665714405537)を用いることを推奨します。コンスルーを用いることで、Pro Microが故障した際に取り替えが容易になります。  
<img src = "https://github.com/takashicompany/baumkuchen/raw/master/images/build/IMG_4568.jpg?raw=true" width = "600px" />

以下は、別キーボードでのPro Microのハンダ付けですが、手順はRookeyでも同様です。
コンスルーを回路プレートに差し込みます。  
<img src = "https://github.com/takashicompany/baumkuchen/raw/master/images/build/IMG_4578.jpg?raw=true" width = "600px" />

コンスルーにPro Microを刺します。  
<img src = "https://github.com/takashicompany/baumkuchen/raw/master/images/build/IMG_4579.jpg?raw=true?raw=true" width = "600px" />



コンスルーとPro Microをハンダ付けします。  

https://user-images.githubusercontent.com/4215759/236684506-b55b27fb-9b54-4a46-b0fb-f98aaa532069.mov

下図のようにPro Microとコンスルーがハンダで接続されていれば完了です。  
<img src = "https://github.com/takashicompany/baumkuchen/raw/master/images/build/IMG_4584.jpg?raw=true" width = "600px" />

Rookeyでの取り付けは以下のようになります。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6633.jpg?raw=true" width = "600px" />

### 7. スイッチプレートの取り付け

スイッチプレートを回路プレートに取り付けます。  
スイッチプレートは画像の下側のプレートになります。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6639.jpg?raw=true" width = "600px" />

スイッチプレートの取り付けには、回路プレートとの接合部に使用していたスペーサーを使用します。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6645.jpg?raw=true" width = "600px" />

回路プレートにスペーサーを4つ取り付けます。  
スペーサーが回路プレートにハマらない場合は、ヤスリなどで削るなどしてサイズをあわせてください。
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6649.jpg?raw=true" width = "600px" />

スペーサーの上に回路プレートを載せます。仮止めですので、載っていれば問題ありません。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6650.jpg?raw=true" width = "600px" />

スイッチプレートのスペーサー部分を同色のペンで塗ると、落ち着いた印象になります。  
完成後でも作業可能です。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6651.jpg?raw=true" width = "600px" />

### 8. キースイッチの取り付け

キースイッチはCherry MX互換のものを取り付けます。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6653.jpg?raw=true" width = "600px" />

キースイッチをスイッチプレートに刺します。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6656.jpg?raw=true" width = "600px" />

取り付けづらい場合は、一度スイッチプレートのみの状態でキースイッチを挿し込むと作業がスムーズに進められます。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6655.jpg?raw=true" width = "600px" />

全体を裏返して、スイッチプレートに取り付けたキースイッチの足が、回路プレートの穴を通って底面から出てくることを確認します。  
もし、キースイッチの足が出ていない場合は、キースイッチを一度取り外して足が曲がっていないかを確認してください。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6659.jpg?raw=true" width = "600px" />

回路プレートとキースイッチの足をハンダ付けします。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6660.jpg?raw=true" width = "600px" />

### 9. ロータリーエンコーダの取り付け

Pro Microの手前のキースイッチ穴取付箇所に、ロータリーエンコーダを取り付けることが可能です。  
ロータリーエンコーダではなく、通常のキースイッチを取り付けても構いません。お好みに併せてお選びください。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6665.jpg?raw=true" width = "600px" />

[ロータリーエンコーダ](https://shop.yushakobo.jp/products/3762)はプッシュ入力に対応しております。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6666.jpg?raw=true" width = "600px" />

ロータリーエンコーダの足が回路プレートの穴と合致する向きを確認します。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6667.jpg?raw=true" width = "600px" />

ロータリーエンコーダをスイッチプレートに刺します。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6668.jpg?raw=true" width = "600px" />

全体を裏返して、ロータリーエンコーダの足が回路プレートの裏面から出ていることを確認します。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6669.jpg?raw=true" width = "600px" />

ロータリーエンコーダの足と回路プレートをハンダで接続します。。  
緑色の丸の箇所をハンダ付けします。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6671_b.jpg?raw=true" width = "600px" />

### 10. 滑り止めシールの取り付け

Rookeyの底面に滑り止めとしてゴム足シールや[ウレタンクッション](https://shop.yushakobo.jp/products/a0800ur-01-6)などを取り付けます。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6672.jpg?raw=true" width = "600px" />

打鍵スタイルや使用目的に応じて、滑り止めシールを取り付けます。以下は取り付け例です。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6673.jpg?raw=true" width = "600px" />

### 11. キーキャップ、ロータリーエンコーダキャップの取り付け

キーキャップやロータリーエンコーダのキャップを取り付けます。  
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_6681.jpg?raw=true" width = "600px" />


### 12. ファームウェアの書き込み

[Remap](https://remap-keys.app/catalog/QSD7jKLB0Ax5J4y8wJ8s/firmware)にてWebブラウザからファームウェアの書き込みを行います。  

ファームウェアを選んで、Flashをクリックします。  
<img src = "https://github.com/takashicompany/rookey/assets/4215759/933fc14a-2d65-425c-a00f-eb79a82bd547" width = "600px" />

Bootloderが「Caterina」になっていることを確認してFlashをクリックします。  
<img src = "https://github.com/takashicompany/rookey/assets/4215759/20aba117-0d60-4539-b655-5dea8084d733" width = "600px" />

[リセットスイッチを押して](https://github.com/takashicompany/rookey/blob/master/README.md#5-%E3%83%AA%E3%82%BB%E3%83%83%E3%83%88%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91)、Pro Microが選択肢に出てくるかと思いますので、「接続」をクリックするとファームウェアの書き込みが開始されます。  
<img src = "https://github.com/takashicompany/rookey/assets/4215759/d6f071fb-7d2b-4449-9b6e-1283e31dd44e" width = "600px" />

以下のような表示になれば、書き込み完了です。  
<img src = "https://github.com/takashicompany/rookey/assets/4215759/ce1170f6-8766-49af-a0e7-9ee7ca0c43e6" width = "600px" />

### 13. キースイッチの動作確認

[Remap](https://remap-keys.app/configure)でキースイッチが正しく動作するかを確認します。  
+Keyboardをクリックします。  
<img src = "https://github.com/takashicompany/rookey/assets/4215759/a635e8ac-e815-4261-99cc-3e8d57467dde" width = "600px" />

上述のVIAファームウェアを書き込むと、Rookeyが選択肢に表示されますので選択して接続します。  
<img src = "https://github.com/takashicompany/rookey/assets/4215759/7ac86720-3263-4d83-8efb-286ffaef6fa3" width = "600px" />

Rookeyの設定画面が表示されます。右下の三点リーダーをクリックするとメニューが表示されますので、「Test Matrix mode」をクリックします。  
<img src = "https://github.com/takashicompany/rookey/assets/4215759/4d9cae0f-64ad-4d40-9e02-4224ae53e4d5" width = "600px" />

「Test Matrixｌでは入力したキーが着彩されますので、全てのキーが動作(着彩)されるかを確認します。  
<img src = "https://github.com/takashicompany/rookey/assets/4215759/1b82239b-2322-4212-b655-943db4f30ca4" width = "600px" />

もし入力されないキーがありましたら、キースイッチのハンダ付けに不備がないか、Pro Microのコンスルーのハンダ付けや差し込みを確認してください。

### 14. 完成した後の楽しみ方

完成しましたら、ぜひSNSなどに写真を投稿頂ければと思います。
Twitterのハッシュタグは [`#Rookey #自作キーボード`](https://twitter.com/search?q=%23%E8%87%AA%E4%BD%9C%E3%82%AD%E3%83%BC%E3%83%9C%E3%83%BC%E3%83%89%20%23Rookey&src=typed_query) を付けていただけると幸いです。
キットを組み立てた感想や、キーボードを使った所感などをお待ちしております！

また、毎週日曜日の１9時より実施されている[#KEEP_PD](https://twitter.com/hashtag/KEEB_PD?f=live)に投稿頂くこともオススメです。  
開催の告知は[@KEEB_PD](https://twitter.com/KEEB_PD)にて行われております。

ご不明な点などございましたら、[@takashicompany](https://twitter.com/takashicompany)にメンションやDM頂ければ回答できるかと思います。

