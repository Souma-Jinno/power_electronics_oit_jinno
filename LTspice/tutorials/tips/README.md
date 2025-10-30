# LTspice Tips

LTspiceをより便利に使うための小技やカスタマイズ方法を紹介します。

## 📌 目次

### [指数の表し方](exponent_notation.md)
数値入力時の指数表記と接頭辞（k, M, u, nなど）の使い方を説明します。

**主な内容：**
- 指数と接頭辞の対応表
- メガ（Meg）とミリ（m）の違い
- 実践的な使用例

### [インターフェースの表示色](interface_colors.md)
回路図やグラフの表示色をカスタマイズして、見やすくする方法を紹介します。

**主な内容：**
- デフォルト設定の問題点
- 推奨配色設定
- プレゼンテーション用の設定

## その他の便利な機能

### ショートカットキー

LTspiceには便利なショートカットキーが多数あります。主なものは[基本的な使い方](../02_getting_started/README.md#便利なショートカットキー)を参照してください。

### パラメトリック解析

素子の値を変化させながらシミュレーションする方法：
1. `.step param` コマンドを使用
2. 例: `.step param R 1k 10k 1k` （Rを1kΩから10kΩまで1kΩ刻みで変化）

### モンテカルロ解析

部品のばらつきを考慮したシミュレーション：
1. `.step` コマンドと `mc()` 関数を組み合わせて使用
2. 統計的な解析が可能

## 参考リンク

- [LTspice公式サイト](https://www.analog.com/jp/design-center/design-tools-and-calculators/ltspice-simulator.html)
- [LTspice Users Club（英語）](https://www.ltwiki.org/)

---

[← 目次に戻る](../README.md)
