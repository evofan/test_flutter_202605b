# test flutter

reference  

**環境構築(Windows編)**  
[https://zenn.dev/heyhey1028/books/flutter-basics/viewer/getting_started_windows](https://zenn.dev/heyhey1028/books/flutter-basics/viewer/getting_started_windows)  

**Flutterの導入(1) ~for Windows10~ Android Studio と Flutter をインストールしよう**  
[https://qiita.com/bonkoturyu/items/5ab3d756c24f5b8875a8](https://qiita.com/bonkoturyu/items/5ab3d756c24f5b8875a8)  

<img src="https://evofan.github.io/test_flutter_202605b/screenshot/1.png" width="50%">  

AI による概要  
「The current Visual Studio installation is incomplete」エラーは、  
Windows用Flutter開発に必要なコンポーネントが不足していることを示しています。  
Visual Studio Installerで「C++によるデスクトップ開発」ワークロードをインストールし、  
関連する推奨コンポーネントを含めることで修正できます。   
  
対処手順  
Visual Studio Installerを開く:  
Windowsのスタートメニューから「Visual Studio Installer」を検索して起動します。  
修正（Modify）をクリック:  
インストールされているVisual Studio 2022（または2019）の「修正」ボタンをクリックします。  
ワークロードを選択:  
「ワークロード」タブで「C++によるデスクトップ開発」（Desktop development with C++）にチェックを入れます。  
必要なコンポーネントの確認:  
右側の「詳細」パネルで、以下がチェックされているか確認します。  
MSVC v14x - VS 2022 C++ x64/x86 build tools  
Windows 10/11 SDK  
インストールを実行:  
「修正」をクリックしてインストールを完了させ、PCを再起動します。  
確認:  
コマンドプロンプトで flutter doctor を再実行し、エラーが消えたことを確認します。  

<img src="https://evofan.github.io/test_flutter_202605b/screenshot/2.png" width="50%">  
<img src="https://evofan.github.io/test_flutter_202605b/screenshot/3.png" width="50%">  
<img src="https://evofan.github.io/test_flutter_202605b/screenshot/4.png" width="50%">  
