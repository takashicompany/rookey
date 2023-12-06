# Rookey

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
<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

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

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />

<img src = "https://github.com/takashicompany/rookey/blob/master/images/build/IMG_ .jpg?raw=true" width = "600px" />
