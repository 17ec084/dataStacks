# このbranchについて
[電磁気学の独自研究](https://github.com/17ec084/grade2-2/tree/master/electromagnetism/ElectricLinesOfForce)にて、参考のために作成したmatlab用グラフデータcosΦαβ_by_A.figを格納するbranchである。  
このデータは100MBを超えているため、[ファイル分割プログラム](https://github.com/17ec084/fileSplitter)にて分割されている。

# データの復元の仕方
1. レポジトリの中身をすべて同じローカルフォルダにダウンロードする。  
2. [ファイル分割プログラムのソースファイル](https://github.com/17ec084/fileSplitter/fileSplitter.c)を同じフォルダにダウンロードする。  
3. gccをインストールし、パスも通す。  
4. 1、2のフォルダにてCUIを起動し、 `gcc fileSplitter.c -o fileSplitter` を実行する。  
5. そのままCUIで `fileSplitter cosΦαβ_by_A.fig merge` を実行する。  
6. しばらく待つと、同じフォルダにcosΦαβ_by_A.figが生成される。  
7. matlabで起動する。