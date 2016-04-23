# まず読んだ本
### コンピュータシステムの理論と実装
CPUやメモリの仕組みを大まかに知ることができる
### 30日でできる! OS自作入門
OSの仕組みやアセンブラの基本がわかる
### 自作エミュレータで学ぶx86アーキテクチャ-コンピュータが動く仕組みを徹底理解!
こちらもアセンブラに慣れるために読んだ
### たのしいバイナリの歩き方
バイナリに慣れるために読んだ

# ファミコンのアーキテクチャについて一通り目を通しておく
http://pgate1.at-ninja.jp/NES_on_FPGA/index.html

この辺とかを読んで、通常のx86アーキテクチャと違って
ファミコンの6502は、PPUやAPUがあるとかそういうことを一通り知っておく。
(用語に慣れておく)


# iNESファイルのフォーマットについて知る
まずNESファイルを解析することから始めます。
1.iNES フォーマットのバイナリを 16進数でダンプしましょう。
2.先頭4バイトはSignature なのでそれを読んでROMファイルかどうか判別してみる


# TODO:
CPU を実装する
レジスタビューア・逆アセンブラを実装する
画像処理機能を実装する (PPU)
音声処理機能を実装する (APU)
マッパーを実装する (MMC)





