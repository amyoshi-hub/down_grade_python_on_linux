interpret it in your own way
https://qiita.com/yshimizu1114
この人の話を詳しくする
AIの基礎学習をしたいときpythonのダウングレードをしたい
dnfもinstall できない

sudo apt install build-essential zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev wget

wget https://www.python.org/ftp/python/3.6.15/Python-3.6.15.tgz

./configure --enable-optimizations

./Include/objimpl.hの258行目のdummy変数の型をlong doubleに変更
./Objects/obmalloc.cの653行目以降を
#define ALIGNMENT              16               /* must be 2^N */
#define ALIGNMENT_SHIFT         4
8 -> 16
3? -> 4
に変更をしてsudo make altinstall

私のための議事録
