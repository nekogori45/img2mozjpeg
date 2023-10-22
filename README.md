# img2mozjpeg

<p align="center">
  <img src="./screenshot.jpg" />
</p>

このアプリは様々な形式の画像ファイルをmozjpegによる圧縮でjpgに変換します

既存のmozjpegはwebpやavifに入力対応しておらずローカルで一括変換したかったので作成しました

## 使用方法
  入力ファイルはwebp、jpg、png、bmp、gif、avifに対応確認済みです  
出力先は画像を入力した同じフォルダのjpgフォルダになります  
複数ファイルドラッグ＆ドロップ対応しています  
フォルダのドラッグ＆ドロップは一つのみ対応しています  
注意点として画像ファイル以外の全ての形式のファイルも処理するのでフォルダをドラッグ＆ドロップする際は画像のみのフォルダにしてください  
binフォルダ内のimg2mozjpeg.batに直接ドラッグ＆ドロップしても機能します  
mozjpegの圧縮率を変えたい場合はimg2mozjpeg.bat内のcompressの値を変えてください  
