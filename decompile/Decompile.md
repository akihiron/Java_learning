# Java_decompile
##【2016_11_26日記述】
今日はJavaのデコンパイルについてお勉強いたします。  
目標としてはUiautomator.jarの中身に何が記述されているかを知ることですね  
[Uiautomator.jar][]に関してはこちらを参照してください  
何はともかくいきなりですが、まずはググれとってことで参考にするのは
以下のサイトです。  
<http://totech.hateblo.jp/entry/2015/02/19/145004>
ここによると[JD(Java Decompiler) Project][JD]というのがおすすめのツールみたい  
UP主はEclipse使っていないので素直にダウンロードしてこようと思います
[JD(Java Decompiler) Project][JD]にアクセスしてJD-GUI(windows-1.4.0)を[ダウンロード][JD_Download]する
ダウンロードしたファイルはこのgit内に置いておくが、残りは展開して.jarファイルを開くだけで展開できた
.javaファイルとして保存することもできて、手ごろに使えそう

で、肝心のファイルの中身はというとsampleではなく型だけ用意してあるただの[スタブ群][stub]でした。

[stub]:https://ja.wikipedia.org/wiki/%E3%82%B9%E3%82%BF%E3%83%96 "スタブ"
[JD_Download]: https://github.com/java-decompiler/jd-gui/releases/download/v1.4.0/jd-gui-windows-1.4.0.zip "Java Decompiler Download"
[JD]: http://jd.benow.ca/ "Java Decompiler"
[Uiautomator.jar]: https://github.com/akihiron/python_leaning/blob/master/readme.md "Uiautomator"
[Java_decompile]: http://google.com/        "Google"

