# リポジトリの概要
![test](https://github.com/sak057/robosys2022/actions/workflows/test.yml/badge.svg)  
このリポジトリには、plusコマンドに関するコードとテストがあります。  

# plusについて  
概要    
標準入力から読み込んだ数字を足す。  
ダウンロード方法  
```
git clone https://github.com/sak057/robosys2022  
```
↑を実行する。  

実行方法  
計算したい値を標準入力でコードに読み込ませてplusを実行する。  

使い方  
①１から指定した数までを足したいとき  
```
seq 数 | ./plus
```
②任意の数を足したいとき  
```
vi nums
```
これで任意の数を縦並びで入力  
```
./plus < nums
```
これで実行


## 必要なソフトウェア
* Python 3.7～3.10

## テスト環境
* Ubuntu22.04.1LTS

## 著作権について
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* © 2022 Sakuto Shirasawa
