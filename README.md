# week3
・どんな実装をしたか

　画像を取得し、二次元フーリエ変換を実行。つぎにパワースペクトルで表示後、マウスで指定した周波数を用いてフーリエ逆変換を行う。
 
・使い方

 　1.2D_FFT_IFFT.ipynbを実行する。
  
   2.元画像を表示するウィンドウ、パワースペクトルを表示するウィンドウ、実際にマウスを動かし周波数を指定するウィンドウ、
   　指定した点（矩形）でのフーリエ逆変換をした画像を表示するウィンドウ、フーリエ逆変換をした画像を重ね合わせた画像を表示するウィンドウ
     の５つのウィンドウが表示されている。
   
   3.実際にマウスを動かし周波数を指定するウィンドウで左クリック、もしくは左クリックを押しながらマウスを動かす。
   
   4.終了したくなったときは、Escキーを押す。


・依存ライブラリ


・バージョン情報

  python 3.6.0
  
  Anaconda 4.3.1
  
・参考にしたサイト
  https://www.hello-python.com/2018/02/16/numpy%E3%81%A8opencv%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%9F%E7%94%BB%E5%83%8F%E3%81%AE%E3%83%95%E3%83%BC%E3%83%AA%E3%82%A8%E5%A4%89%E6%8F%9B%E3%81%A8%E9%80%86%E5%A4%89%E6%8F%9B/
    
    numpyとopencvを用いた画像のフーリエ変換と逆変換の方法を参考にした。
    
  https://ensekitt.hatenablog.com/entry/2018/06/17/200000
  
    マウスイベントのコードを参考にした。また、終了処理も参考にした。
    
  
    
