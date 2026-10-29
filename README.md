# FFXI Arebati Veng+25 作戦ガイド

シェオルジェール AT3「Arebati Veng+25」のLS当日用作戦ガイド（非公式・学習用）。

## ファイル

| ファイル | 内容 |
|---|---|
| `arebati_v25_battle1_guide.html` | 1戦目ガイド（単一HTML） |
| `arebati_v25_battle2_guide.html` | 2戦目ガイド（単一HTML）。ジョブ別の局面行動・NG・関係図・当日タイマー・WS閾値早見表・事前チェック・YouTube局面ブックマーク |
| `docs/dev_brief.md` | 開発依頼書（ガードレール・Human Gate） |


## 使い方

公開版: https://xxxkouxxx.github.io/ffxi-arebati-guide/


ブラウザでHTMLを開くだけで動作します（外部依存はYouTube IFrame APIのみ）。動画タブを使う場合は `file://` では再生できないことがあるため、HTTPで開いてください。

```bash
python -m http.server 8765
```

→ http://localhost:8765/arebati_v25_battle2_guide.html

## 出典

- 正本：[JinkoのFF11日記 — Arebati veng25 Part3](https://jinko0914.seesaa.net/article/513963925.html)
- 補足：同 [Part1](https://jinko0914.seesaa.net/article/505643713.html)・[Part2](https://jinko0914.seesaa.net/article/511834767.html)（旧戦術。Part3と矛盾しない内容のみ）、FF11人生を捧げるブログ（[魔法のキャンセル問題](https://www.kagurazakac.com/entry/2026/08/03/000000)・[ヘイト管理](https://www.kagurazakac.com/entry/2026/04/13/000000)）
- 動画：[白魔道士・ナイト目線](https://www.youtube.com/watch?v=IUVoTOXzPPQ) ／ [風＆吟視点](https://www.youtube.com/watch?v=8j_RGlLJNeY)（公式埋め込みプレイヤーで参照。映像の複製・自動解析はしない）

画面上の各行動には出典ラベル（記事／記事の動画解析値／旧記事Part1/2／他PT記事／要確認／記載なし）を付けています。

## 未決事項

- 20%以降の吟遊詩人の方針（離脱してガストスラッシュ連打か、攻撃参加か）は記事内で記述が揺れているためLSで決める
- 動画の局面ブックマークは未登録（実動画を見て手動登録し、JSONで共有）
