## ObjectEditor
  
##### [起動画面]
 ![起動画面](https://i.imgur.com/l2d1qri.jpg)

  
### 最初に
  
実行に際して最低限必要となるのはJavaの開発環境です、
  
OSはlinuxを想定しています。
  
ダウンロード後、
  
$ cd ObjectEditor
  
$ ./objedit
  
と入力するとプログラムが起動します。
  
もし起動時にエラーが出るようでしたら
  
$ ./make_objedit
  
と入力して再コンパイルして下さい。
  
詳しい使用法についてはヘルプを参照して下さい。
  
また"Projects"フォルダにサンプルが多少ありますので参考になれば幸いです。
  
  

### 	androidアプリケーションの開発について
本プログラムをインストールしても、そのままではandroidアプリケーションを作成することはできません。
最初に環境変数APK_DIRを設定してコンパイル済みのapkファイルを置く場所を指定します。
  
export APK_DIR=(ディレクトリ名)
  
  ・・・例えば初期化ファイル".bashrc"に上のような行を追加しておきます。
  
次にandroid開発ツールをダウンロード・解凍して適当なフォルダに配置します。

・android コマンドラインツール 
  
https://developer.android.com/studio#command-tools
  
・プラットフォームツール
  
https://developer.android.com/studio#command-tools
  
・ビルドツール
  
https://androidsdkmanager.azurewebsites.net/Buildtools  
  
・プラットフォーム(各種類)
  
https://androidsdkmanager.azurewebsites.net/SDKPlatform
  
そしてダウンロードしたandroidプラットフォームの中にあるファイル"android.jar"をObjectEditorフォルダにコピーします。
  
![enter image description here](https://imgur.com/GY0afbj.jpg)  
  
  最後にダウンロードしたツールの実行ファイルのある場所にパスを通せばandroid開発ツールが使用できる状態になります。
  
