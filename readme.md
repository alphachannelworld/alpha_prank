# 0. 1.21.2は最高のアップデート

先日、Minecraft: Java EditionのVer1.21.2が正式リリースされました。
1.21.2はバンドルの正式実装とペールガーデンやトロッコ、レッドストーンの実験機能が行われました。

でもそれは表面のお話。技術面ではもっと凄いことになっていました。

# 1. どんなデータパック？

ドッキリアップデート、そう、ドッキリが簡単に作れるようになったアップデートなのです。

簡単に言うと、リソースパック無しでアイテムのモデルをいじる事が出来るようになったので、今までminecraft:custom_model_dataを使っていたり、テクスチャを変えなくても既存のアイテムテクスチャは全てのアイテムに影響出来るようになったのです。

このデータパックでは、自分が適当に作ったドッキリを有効にすることが出来るデータパックです。ワールドを一部破損させる可能性があるので、新規作成することをお勧めします。

# 2. 導入方法

導入方法について、一応シングルプレイでも問題なく動作しますが、ドッキリにはならなくなります。

シングルプレイの場合は下記の記事をご参照ください。

https://minecraft-mcworld.com/tutorial/how-to-dl-datapack/

今回はサーバーでの導入方法を紹介します。

まずサーバーのあるディレクトリを開き、そこにある「ワールドフォルダー」を探します。
「ワールドフォルダー」はserver.propertiesの「level-name」に割り当てたstring値で、デフォルトは「world」です。「world」フォルダーがない場合は「world」フォルダーを新規作成してください。

「world」フォルダーの中にある「datapacks」フォルダーを開きます。ない場合は新規作成してください。

その中にこの圧縮ファイルを入れると導入することが出来ます。

# 3. ワールドを起動する

ワールドを起動したら、まずはデータパックが有効になっているか確認してください。

「/datapack list」コマンドで導入出来ているかどうかがわかります。

バージョンが合っていない場合、不具合が発生する可能性があるので注意してください。

正常に導入出来ている場合、「/trigger alpha.prank_items」コマンドを入力出来るようになっていると思います。

「/trigger alpha.prank_items」コマンドを実行すると、自分自身にバンドル&ドッキリデータパックのオペレーター権限が付与されます。

この状態でダッシュキーとスニークキーを同時入力(デフォルトは「LControl」+「LShift」)すると、UIが表示されます。

この画面の状態でジャンプキー(Space)を押すとその設定のオン／オフを切り替えられ、左(A)と右(D)で移動出来ます。ダッシュキー(LControl)で解除出来ます。この仕組みは1.21.2のプレイヤーのpredicateにinputという条件が追加され、そこのキーを押しているかどうかを出力する事が出来る機能を使用しています。

効果音設定はONの時に自分自身のみに発生し、OFFの時は発生しません。

それ以外の設定は全てゲームプレイ動作に影響を与えるもので、全てのプレイヤーの共通の設定になります。間違えないように有効にしてください。

# 4. 終わりに

ここまで見てくださりありがとうございました。データパックは下記のダウンロードボタンを押して、その下のファイルの1番上を押して頂くとダウンロード出来ます。

このデータパックはcreative commons zero v1.0 universalライセンスにて配布されており、

- 商用利用
- 修正
- 分布
- 私的使用

上記の権限を無償で付与されます。同時に、

- 責任
- 保証

上記の内容が制限されるため、このデータパックを使用して、いかなる損害に対しても制作者は一切責任を負いかねます。

また、[Minecraftエンドユーザー使用許諾契約の範囲内](https://aka.ms/MinecraftEULA)の中で利用してください。
