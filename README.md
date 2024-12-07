# 音声ファイルを白黒の縞模様に変換する

このプログラムは、音声ファイル（WAV）を読み込んで、白黒の縞模様に変換します。
できた白黒模様を印刷して、テープ状につなぎ合わせて、光センサーとスピーカーを利用して音声を再現することができるかもしれません。

## 使い方

* https://bull-frog.github.io/sound-to-pattern/ にアクセスして、音声ファイルをアップロードしてください。
* WAVファイルを読み込んで、白黒の縞模様に変換します。
* WAVファイルは、サンプリングレートを600Hz〜1000Hz程度まで下げておくのが望ましいです。ffmpegなどを使って変換してください。
* exampleディレクトリにサンプル音源を用意していますので、お試しください。

## ディレクトリ構成

```
.
├── README.md
├── example（サンプル音源）
│   ├── demo_1000Hz.wav
│   ├── demo_44100Hz.wav
│   ├── demo_600.wav
│   └── demo_800Hz.wav
├── film_template.png（フィルムの枠となる画像）
├── icon（favicon）
├── index.html
├── sheet-teplate（film_template.pngの元ファイル）
│   └── 印刷イメージ.pptx
└── style
    └── master.css
```