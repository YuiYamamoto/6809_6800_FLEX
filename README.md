# 6809_6800_FLEX
6809/6802シングルボードコンピュータでWindows上の仮想ディスクを用いてFLEXを走らせる

(1)FlexDrvWin.exe
　Windows上に仮想ドライブを作成するソフトです。FLEX用のDSKファイルやD77ファイルをリードライトできます。
また、ファイル一覧ボックス内へWindows上のファイルをドラッグ＆ドロップしてファイルを追加できます。さらに、右ボタンメニューから、各種操作が可能です。

(2)6809AsmWin.exe, 6809DasmWin.exe, 6800AsmWin.exe, 6800DasmWin.exe
　Windows上で動作する6809用、6800用のクロスアセンブラ、クロス逆アセンブラです。
FLEX用のプログラム作成に数年間使用してきましたので、重大なバグはないとは思いますが、全くの素人が試行錯誤で作成したものですので、バグがあってもご容赦を。

いずれも、Visual Studio 2013 Express版でビルドしましたので、それに合ったランタイムが必要かもしれません。

(3)Driver.txt,Driver.hex,Console.txt,Console.hex
　私が使用している6809用のWindows仮想ドライブ対応のFLEX用Driver，Consoleルーチンです。

