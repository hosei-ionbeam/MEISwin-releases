[English](README.md) | **日本語**

# MEISwin — MEIS & RBS 解析ソフトウェア

法政大学 イオンビーム工学研究所

作成者: 西村智朗 (Tomoaki Nishimura)、t-nishi (a) hosei.ac.jp

MEISwin は、中エネルギーイオン散乱 (MEIS) とラザフォード後方散乱分光 (RBS) のスペクトルをシミュレーションし解析するソフトウェアです。

## ダウンロード

配布ファイルは [Releases](https://github.com/hosei-ionbeam/MEISwin-releases/releases) から入手してください。最新版は **v1.582 (2017-02-21)** です。

参考動画「アイソトープを指定する場合の操作」(`Specification_of_isotope.mp4`、2018-05-18) は v1.582 のリリースに添付しています。YouTube でも見られます: https://youtu.be/GkY538oCmec

このリポジトリには配布ファイルとその説明だけを置いています。ソースコードは含みません。

## ファイルの照合

ダウンロードしたファイルが改ざんされていないことは、SHA-256 を下の表と比べて確認できます。

```powershell
Get-FileHash .\MEISwin-v1.582-releaseVersion-170221.zip -Algorithm SHA256
```

| 版 | ファイル | SHA-256 |
|---|---|---|
| 1.582 | `MEISwin-v1.582-releaseVersion-170221.zip` | `05f18679798d4e07ccd40bf37aad4363a3285cf384e20193f0bea833069563bb` |
| 1.581 | `MEISwin-v1.581-releaseVersion-130718.zip` | `c9c8a7e33505463bd6c3450cc7c583e562d1f5801d8a3a217f77e8513341f74d` |
| 1.58 | `MEISwin-v1.58-releaseVersion-130713.zip` | `7dd6ae7f0dd1c41385ce0a09d0a7eacd04e036f73311566edd16cc0d234c110e` |
| 1.57 | `MEISwin-v1.57-releaseVersion-130619.zip` | `8876404e682ede95e15abfe1df1c683e5f841a612779cb854babc99955aa56df` |
| (動画) | `Specification_of_isotope.mp4` | `9e40de232089e2d608bc29a6e0f532846a27b9c39a88683bba720ff932c61509` |

## 版の履歴

日付は旧ページに掲載していた日です。

| 版 | 日付 | 変更点 |
|---|---|---|
| [1.582](https://github.com/hosei-ionbeam/MEISwin-releases/releases/tag/v1.582) | 2017-02-21 | EMG5.0(σ0はEMG5.2と同じ)を指定出来るようにした。<br>シミュレーションの高速化を行った。(OPEN文で大きなBLOCKSIZEを指定するようにした) |
| [1.581](https://github.com/hosei-ionbeam/MEISwin-releases/releases/tag/v1.581) | 2013-07-18 | 実験データに対するスムージング点数の最大値を 10 → 50<br>OS が小数点にカンマを用いている時は警告メッセージを出力するようにした。 |
| [1.58](https://github.com/hosei-ionbeam/MEISwin-releases/releases/tag/v1.58) | 2013-07-13 | エラーメッセージの変更 |
| [1.57](https://github.com/hosei-ionbeam/MEISwin-releases/releases/tag/v1.57) | 2013-06-17 | 旧ページに掲載していた中で最も古い版 (変更点の記載なし) |

## 配布場所の移設について

これらの版は、2013〜2017 年に研究所のウェブサイトで公開してきたものです。2026 年 10 月に配布場所をこの GitHub リポジトリへ移しました。ファイルの中身は変えていません (当時の原本とバイト一致を確認済み)。

## 参考文献

MEISwin を用いた結果を論文や講演で発表する際は、次の文献を引用してください。

T. Nishimura, "Computer simulation program for medium-energy ion scattering and Rutherford backscattering spectrometry", Nuclear Instruments and Methods in Physics Research B 371 (2016) 97–100. https://doi.org/10.1016/j.nimb.2015.10.007
