# 処理内容
#### 動画を撮る
- 動画を撮影して、Azure Notebooksに取り込む。
#### 動画を1フレーム毎の画像に変換する
- Pythonを用いて動画を画像に変換する。osとcv2をimportして画像処理を行う。  
スクリーンキャプチャを保存するディレクトリを作成して、そこに画像を保存する。
#### 1枚ずつ画像の輝度値の平均をとる
- imreadを用いて1枚1枚画像を読み込む。読み込んだ画像の輝度値の平均をim.mean()を用いて求めてyの配列に入れていく。
#### 輝度値を画像にプロットする
- xに0から93が入った配列を用意し、yに先ほど求めた画像の輝度値の平均を1つ1つ配列に入れていく。  
そしてplt.plotでグラフをプロットする。

# 実行の仕方
Azure Notebooksに動画を取り込んで、Pythonで処理を実行した

# 参考サイト
https://www.tech-tech.xyz/opencv_video.html  
このサイトの「動画を1フレーム毎に画像へ変換」の部分のコードを利用した
