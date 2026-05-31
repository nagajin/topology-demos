# 位相空間の道標 — シミュレータ集 / Topology Demos

『位相空間の道標 — 基礎から位相不変量まで』(小池直之 著・共立出版, 2025) の章順に沿って、点集合位相論の主要概念を視覚的に学ぶためのインタラクティブ・デモ集です。外部ライブラリ・ビルド・サーバを一切必要とせず、各ページは単一の HTML ファイルだけで動作します。

> Interactive, dependency-free visual demos for point-set topology, following the chapter order of N. Koike's textbook *位相空間の道標* (Kyoritsu, 2025).

## ▶ ライブデモ

- **索引(目次)**: https://nagajin.github.io/topology-demos/
- 第2章 距離空間 — 開球の形: https://nagajin.github.io/topology-demos/ch02_metric.html
- 第3章 位相空間 — 内部・閉包・境界・導集合: https://nagajin.github.io/topology-demos/ch03_closure.html
- 第3章 位相空間 — ε–δ 連続性: https://nagajin.github.io/topology-demos/ch03_continuity.html
- 第4章 連結性・弧状連結性 (位相幾何学者の正弦曲線ほか): https://nagajin.github.io/topology-demos/ch04_connected.html

## 関連

- **平均曲率流シミュレータ** (2D 曲線短縮流 / 3D 曲面): https://nagajin.github.io/mean-curvature-flow/

## 内容

| 章 | デモ | 主な可視化 |
|---|---|---|
| 2 距離空間 | `ch02_metric.html` | L¹(菱形)・L²(円)・L<sup>∞</sup>(正方形)・L<sup>p</sup> の開球の形を比較。距離が違っても同じ位相を定める様子 |
| 3 位相空間 | `ch03_closure.html` | 開円板/閉円板/穴あき円板/収束列/稠密集合 ほか 8 例について int(A) / cl(A) / ∂A / A′ を色分け表示 |
| 3 位相空間 | `ch03_continuity.html` | 8 種の関数 (x², 1/x, sign, sin(1/x) ほか) に対し ε–δ の δ を自動探索。不連続点では δ が取れないことを体感 |
| 4 連結 | `ch04_connected.html` | 6 例で「経路をたどる」アニメ。位相幾何学者の正弦曲線で「連結だが弧状連結でない」が見える |
| 5–8 | (予定) | コンパクト性, 分離性, ホモトピー群, ホモロジー群 |

## 使い方

ブラウザでライブデモの URL を開くだけです。ローカルで動かす場合は次のとおり (ビルド・依存関係は不要):

```bash
git clone https://github.com/nagajin/topology-demos.git
cd topology-demos
open index.html   # またはブラウザにドラッグ&ドロップ
```

## ライセンス

[MIT License](LICENSE) © 2026 長塚 悠仁 (Yuto Nagatsuka)

## 参考

- 小池直之, 『位相空間の道標 — 基礎から位相不変量まで』, 共立出版, 2025年. <https://www.kyoritsu-pub.co.jp/book/b10131191.html>
