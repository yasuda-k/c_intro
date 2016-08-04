# はじめに
このプロジェクトは「C言語入門」のための解説＋コード例＋課題例について整理している。想定している前提は以下の通り。

- 前提
  - Pythonで基本的なプログラミング（関数、制御文、スコープ、ファイルI/O、ユニットテスト）はできるレベル。
  - 参考: [2016年度 : プログラミング1](https://ie.u-ryukyu.ac.jp/~tnal/2016/prog1/)
    - モジュールは教えている。
    - クラスは教えていない。オブジェクトについても詳細は教えていない。
    - メモリを意識せずにプログラミングできる環境。
    - コンパイラ言語や静的型付け言語についての知識ゼロ。
- 目標
  - 組み込み等でC言語が要求されることがあり、最低限のC言語知識を持たせたい。
  - 別講義「[2015年度: アルゴリズムとデータ構造](https://ie.u-ryukyu.ac.jp/syllabus/2015/late/60105200.html)」で、実装をC言語で進めるため、ポインタ周り以外の基礎については終えておきたい。具体的な要求は次の通り。

```
アルゴリズムへの繋ぎとしては、
　　編集、コンパイル、型宣言、配列、構造体、c言語の関数
について説明してもらえると助かります。
```
- 上記を踏まえ、以下の事柄を含めつつ、Python 3のコードと比較する形でC言語の解説を行う。
  - (0) 参考文献、サイトの提示。
  - (1) コンパイラの役目。
  - (2) 静的型付け言語と動的型付け言語の違い。
  - (?) Makefile（ファイル分割されたプログラムのビルド方法）
  - (?) 「C言語の配列」と「Pythonのリスト」比較によるメモリのイメージ付け。
  - (?) デバッガの利用。
    - [CLion](https://www.jetbrains.com/clion/)のリンク紹介しとけば良い？（学生はPyCharmの演習経験あり）
    - 「紹介するならlldbでも良いのでは。OSでも使うし」 by 院生
