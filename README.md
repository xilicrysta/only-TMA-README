<div align="center">
  <img src="tma_flutter/assets/images/TMAicon.png" width="150" alt="TMA Logo">
  <h1>Tempo Mental Arithmetic</h1>
  <p><strong>「有料なのに操作性が悪い」という既存アプリの壁を壊す。<br>珠算・暗算の中上級者の相棒となる、次世代の完全無料・総合暗算トレーニングアプリ</strong></p>
  
  <p>
    <img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white" alt="Flutter">
    <img src="https://img.shields.io/badge/Dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white" alt="Dart">
    <img src="https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white" alt="macOS">
  </p>
</div>

---

## プロジェクトの背景と目的 (Vision)

現在リリースされているフラッシュ暗算や珠算のアプリは、**「有料であるにも関わらず、UI/UXが古く操作性が悪い」**という課題を抱えています。
本プロジェクト（Tempo Mental Arithmetic: 通称TMA）は、その障壁を取り払い、**直感的で美しいモダンなデザイン**と、**中上級者でも満足できる高度なトレーニング機能**を「完全無料」で提供するために開発されました。

---

## 主な機能 (Core Features)

TMAは、ただのフラッシュ暗算アプリではなく、珠算学習者が求めるあらゆるトレーニングをひとつのアプリに統合しています。

| モード | 詳細・特徴 |
| :--- | :--- |
| **フラッシュ / ノーマル暗算** | 画面に次々と表示される数字を足していく定番のトレーニング。滑らかなアニメーションと細やかな速度調整が可能。 |
| **読み上げ暗算 (VOICEVOX)** | 音声合成エンジン「[VOICEVOX](https://voicevox.hiroshiba.jp/)」を採用。機械的ではない自然な音声で、本番さながらの環境を実現。 |
| **電卓算盤モード** | **「アプリ内で滑らかな算盤のタッチ操作」**という既存アプリにはないUXを実現。17桁の実践的なそろばんを画面上で直接操作可能。 |
| **テンキー入力 / 桁幅育成** | 珠算特有の数字認識力を高める独自の「桁幅育成」や、実務にも活きるテンキー練習モードを搭載。 |
| **モチベーション・システム** | プレイヤーの成績に応じてランクが変動し、多彩な称号（バッジ）を獲得できるゲーミフィケーション要素。 |

---

## 技術スタック (Tech Stack)

ポートフォリオとしての品質を担保するため、モダンな技術選定とクリーンなアーキテクチャを意識して開発しています。

- **Framework**: Flutter (Dart)
- **State Management**: Riverpod (UIとビジネスロジックの完全な分離)
- **Architecture**: 拡張性と保守性を重視したディレクトリ構成 (`providers/`, `screens/`, `widgets/` 等の分離)
- **Audio Engine**: VOICEVOX (高品質な音声合成エンジンの組み込み)
- **Target Platform**: macOS (Desktop), iOS/Android (予定)

---

## スマホUI (Mobile UI)

<div align="center">
  <img src="tma_flutter/assets/images/app%20store%20画像/Simulator%20Screenshot%20-%20iPhone%2017%20-%202026-06-21%20at%2001.44.51.png" width="200">
  &nbsp;&nbsp;
  <img src="tma_flutter/assets/images/app%20store%20画像/Simulator%20Screenshot%20-%20iPhone%2017%20-%202026-06-21%20at%2001.45.16.png" width="200">
  &nbsp;&nbsp;
  <img src="tma_flutter/assets/images/app%20store%20画像/Simulator%20Screenshot%20-%20iPhone%2017%20-%202026-06-21%20at%2001.45.33.png" width="200">
  &nbsp;&nbsp;
  <img src="tma_flutter/assets/images/app%20store%20画像/Simulator%20Screenshot%20-%20iPhone%2017%20-%202026-06-21%20at%2001.45.43.png" width="200">
</div>

---

## ランクシステム (Rank Mode)

ランクモードでは、自らの暗算力を試せる本格的なレーティングシステムを提供しています。
到達したレート（RATE）に応じて「Surface」などのランクが認定されるほか、様々な条件を満たすことで独自の「バッジ（称号）」をアンロックすることが可能です。
常時開催のBASICアリーナや夜間限定のPROアリーナなど、モチベーションを高く保ちながら成長を実感できる充実した環境が整っています。

<div align="center">
  <br>
  <img src="tma_flutter/assets/images/ランク画面.png" width="700" alt="ランクモード画面">
</div>

---

<details>
<summary><b>開発者向け: ローカルでの起動方法</b></summary>
<br>

```bash
cd tma_flutter
flutter pub get
flutter run -d macos
```
</details>

<details>
<summary><b>ユーザー向け : ニッチな所まで見てくれた方へ</b></summary>
<br>

`🏠 > 6 > 少数中 > AC > 918273645.39200392 > = 💀`
</details>

<br>

<div align="center">
  <i>より詳細な情報や最新のロードマップについては、<a href="https://tma-solo.com/">https://tma-solo.com/</a> をご覧ください。</i>
</div>
