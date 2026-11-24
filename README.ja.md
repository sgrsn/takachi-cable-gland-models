# タカチ ケーブルグランドの 3D モデル（非公式）

[English](README.md) | 日本語

タカチ電機工業のケーブルグランドのうち、2D 図面だけが公開されている型番の 3D モデル（STEP）です。
収まりの確認や、取付穴・パネルの設計に使えます。
公式の図面と照合しています。

> [!IMPORTANT]
> **非公式です。** タカチ電機工業とは無関係で、承認も受けていません。公式サイトの 2D 図面だけを元に作りました。
> 無保証です。取付や干渉に関わる寸法は実物で確かめてください。詳しくは [NOTICE.ja.md](NOTICE.ja.md)

## 使い方

下の一覧から型番を選び、色に合った STEP をダウンロードしてください。

どのファイルも部品ごとのアセンブリで、単位は mm です。
原点はパネルの外面と軸の交点で、+Z がキャップ側、ねじは −Z の向きです。
改訂は [manifest.json](manifest.json)、変更履歴は [CHANGELOG.md](CHANGELOG.md)（英語）にあります。

## 型番一覧

<!-- models:begin -->
| 型番 | L × D (mm) | 取付穴径 (mm) | 色 | STEP |
|---|---|---|---|---|
| [RM12L-7](models/RM/RM12L-7/) | 35 × 19 | 12.2 | ブラック<br>ライトグレー | [RM12L-7B](models/RM/RM12L-7/RM12L-7B.step)<br>[RM12L-7S](models/RM/RM12L-7/RM12L-7S.step) |
<!-- models:end -->

## ご意見

実測値の報告・不具合・型番の追加の希望は [Issues](https://github.com/sgrsn/takachi-cable-gland-models/issues/new/choose) へどうぞ。[CONTRIBUTING.ja.md](CONTRIBUTING.ja.md) もご覧ください。

## ライセンス

モデルのライセンスは [CC BY 4.0](LICENSE) です。対象はこのリポジトリのモデル化の成果だけで、タカチの商標や図面の権利は含みません。
