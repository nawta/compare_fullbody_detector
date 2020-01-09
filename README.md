# compare_fullbody_detector
compared 3 algorithms of image analysis in terms of accuracy, precision, F-measure, and exec speed

画像解析に使われる
HaarLike特徴抽出 + cascade識別器
LBP特徴抽出 + cascade識別器 
HOG特徴抽出 + SVM識別器

の３つのモデルの精度と実行速度を比べました。

題材としては人物検出を選択し、学習データはMITのサイトから拝借させていただいた100枚の画像を使用。
評価軸としてはAccuracy, Precision, F-measureを用いました。あと実行速度も測りました。

比較するとこんな感じ
[](https://user-images.githubusercontent.com/39507181/72038037-69aafd00-32e3-11ea-8d69-4c82b50be207.png)
結果はこんな感じ
[](https://user-images.githubusercontent.com/39507181/72038036-6879d000-32e3-11ea-96f6-8c2cedd64539.png)
