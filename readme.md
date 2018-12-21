# このbranchについて
[電磁気学の独自研究](https://github.com/17ec084/grade2-2/tree/master/electromagnetism/ElectricLinesOfForce)にて、参考のために作成したmatlab用グラフデータcosΦαβ_by_rθ.figを格納するbranchである。  
このデータは100MBを超えているため、[ファイル分割プログラム](https://github.com/17ec084/fileSplitter)にて分割されている。

# データの復元の仕方
1. レポジトリの中身をすべて同じローカルフォルダにダウンロードする。  
2. [ファイル分割プログラムのソースファイル](https://github.com/17ec084/fileSplitter/filesplitter.c)を同じフォルダにダウンロードする。  
3. gccをインストールし、パスも通す。  
4. 1、2のフォルダにてCUIを起動し、 `gcc filesplitter.c -o filesplitter` を実行する。  
5. そのままCUIで `filesplitter cosΦαβ_by_rθ.fig merge` を実行する。  
6. しばらく待つと、同じフォルダにcosΦαβ_by_rθ.figが生成される。  
7. matlabで起動する。
8. 起動時にエラーが出たのであれば、[参考サイト](https://jp.mathworks.com/matlabcentral/answers/220925-save)を参考に、「MATLAB Version 7.3以降」に変更する。

# 参考
https://jp.mathworks.com/matlabcentral/answers/220925-save