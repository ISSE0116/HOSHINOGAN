# HOSHINOGAN
星野源とガッキーの顔を元にDCGANを用いて顔画像を生成します。
image_hoshinofamilyディレクトリ内にある画像を使用して学習を行います。
星野源のみ、ガッキーのみの画像はそれぞれOnlyGEN image,OnlyGAKKI imageに収めてあるので適宜学習に使用したい画像のディレクトリをimage_hoshinofamilyに収めてください。
初期段階ではCPUで学習を行うようにセッティングしているので、GPUを使用する際は、"ngpu = 1"に変更してください。
このソースコードはhttps://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html を参考に作成しています。

# Sample Result
"eval"ファイルに異なるハイパーパラメータでの学習結果のサンプルを格納しています。  
↓実行結果例  
<img src="eval/hoshino_family/128_2000_without_br/result.png" width="750px">

# GUIによる顔特徴調整
TBA...
