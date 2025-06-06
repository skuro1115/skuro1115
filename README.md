# Welcome to My GitHub Profile!

取り急ぎ編集中です。 なるはやで更新します
個人やgit別アカウントで開発していたため，まだ載せられていません。　  

## 🗂 掲載状況一覧（Publication Status）

| プロジェクト名                               | 状況           | 備考                          |
|----------------------------------------------|----------------|-------------------------------|
| 麻雀AIアプリ（iOS）                          | mahjangiOS      | App Storeでリリース済        |
| マイコン制御（Arduino）                      | 🔄 公開準備中   | 壊れたPCから復旧中                 |
| VRシミュレーションアプリ（研究）            | 🔒 非公開       | 研究室内Gitリポジトリ管理     |
| LINE Bot（テーマ人狼）                       | 🔄 開発中       | 公開予定あり                 |
| LINE Bot（読図練習Bot）                      | 💤 保守停止中   | 一時的にメンテナンス停止     |
| 自動化Bot（在庫通知、締切通知）             | 🔄 公開準備中       | 受託開発・個人顧客向け        |
| 緑茶販促プロジェクト（特許付き）            | 🔄 概要編集中     | 特許情報＋活動要約を掲載     |
| 地図測量・大会運営（オリエンテーリング）     | 🔄 概要編集中     | 地図例・活動要約を掲載       |

---


#### 目次
- [プログラミング実績](#プログラミング実績)
  - [麻雀AIアプリ（iOSリリース済）](#麻雀aiアプリiosリリース済)
  - [マイコン制御（Arduino + C）](#マイコン制御arduino--c)
  - [VRシミュレーションアプリ（修士研究）](#vrシミュレーションアプリ修士研究)
  - [LINE Bot開発](#line-bot開発)
  - [自動化案件（受託含む）](#自動化案件受託含む)
- [その他プロジェクト](#その他プロジェクト)
  - [緑茶販促プロジェクト（特許取得）](#緑茶販促プロジェクト特許取得)
  - [地図測量・大会運営（オリエンテーリング）](#地図測量大会運営オリエンテーリング)
- [📫 Get in Touch](#-get-in-touch)


## 🔗 リンク集

- GitHub: https://github.com/skuro1115
- Atcoder:
- Paiza:
- iOSアプリ: [麻雀AI 配牌チェッカー](https://apps.apple.com/jp/app/麻雀ai-配牌チェッカー/id1637036872)

---

## 🖥 プログラミング実績

### 📱 麻雀AIアプリ（iOSリリース済）　　 [概要](AI_iOSApp_majong/Overview.md)
iOSアプリ: [麻雀AI 配牌チェッカー](https://apps.apple.com/jp/app/麻雀ai-配牌チェッカー/id1637036872)

配牌時点での期待点数・和了確率をAIが評価するアプリを個人開発。最上級者10M局の対局データをもとに、初心者・中級者の戦略的意思決定を支援。

| 機能             | 技術                             | 備考           |
|------------------|----------------------------------|----------------|
| AI_データ収集     | Python (selenium, bs4, pandas)  | 自動スクレイピング |
| AI_期待値計算     | Python (PyTorch)                | DNNによる推論モデル |
| AI_物体検出       | Python (SSD&DNN)                | 配牌認識用モデル |
| iOSアプリ実装     | Swift (Storyboard)              | UIKitベースで開発 |

---


### 🧪 VRシミュレーションアプリ（修士研究） [概要](lab_Unity_VR_Simulation/Overview.md)

放射線技師向け教育VRシステムをUnityにて構築。  
安全かつ効率的な技能訓練を実現するため、デザイン思考を取り入れて現場ニーズを抽出し、視認性・操作性・教育効果に基づく設計を実施。

- リポジトリ（研究室管理）: https://github.com/tus-watanabelab/radiationVR.git
- Unity / C# / Meta Quest対応


---

### アルバイト　web開発   [概要](Intern_webDev_PHP/Overview.md)

---

### インターン メルカリOA(まだ)   [概要](Intern_mercari/Overview.md)




---

### 42 Tokyo での学習 「編集中」  [概要](42tokyo/Overview.md)

- 合格率4%の選抜課程「Piscine」を突破
- C言語の自己解決型の課題に対応
- テスト仕様の読解から実装、境界値テストまでを自力で設計
- ピアレビューを通じて、コード品質（可読性・命名・責務分離）の重要性を学習

---


### その他個人・チーム開発リポジトリ [概要](Other_Dev/Overview.md)

| リポジトリ名                        | 内容                              | 備考                                 |
|-------------------------------------|-----------------------------------|--------------------------------------|
| `fueljoy`（nishipro12, skuro1115） | FuelPHPベースのECサイト          | アルバイト案件、チーム4人、時給制    |
| `themeWolves`（skuro1115）         | テーマ人狼LINE Bot                | ゲーム仕様設計・機能実装中           |
| `Dongle`（sajimo212）              | 位置情報共有SNSアプリ             | チーム開発、React Native + Firebase |
| `kurodaSNS`                        | SNSアプリの個人開発版             | 機能検証・UI設計のテスト用途         |
| `yamani`（skuro1115）             | 商品在庫確認のスクレイピングBot   | Python + Selenium、自動通知連携     |



---

#### 🔁 自動化案件（受託含む）
-Python/JS/GAS/ selenium
- LINE Messaging API
- 要件定義から実装まで
- 有償(3件10万円ほど)

| タスク                         | 技術                       | 特徴                 |
|-------------------------------|----------------------------|----------------------|
| 商品在庫通知Bot               | Python + LINE API         | ユーザーごとに通知条件設定 |
| イベント申込期限アラート       | Google Apps Script + LINE | カレンダー連携        |


#### 🤖 LINE Bot開発 [概要](LINEbot_Games/Overview.md)
- Python/JS/GAS
- LINE Messaging API
- 企画から実装まで

| Bot名       | 概要                                  | 技術スタック                         | 状態     |
|------------|---------------------------------------|--------------------------------------|----------|
| テーマ人狼  | テーマ設定・役職ランダム化・投票処理 | LINE Messaging API, JavaScript      | 開発中   |
| 読図データ  | 練習用読図問題の提示・記録管理       | LINE Messaging API, GoogleDrive API | 保守停止 |


#### 🎮 マイコン制御（Arduino + C）　　[概要](Arduino_AutoGame/Overview.md)

任天堂Switch上のゲーム（ポケモン等）の自動操作プログラム。C言語によるファームウェアを実装し、Arduino経由で定型動作を実現。



---

## 🧪 その他プロジェクト

### 🍵 緑茶販促プロジェクト（特許取得） [概要](Other_Promotion_Greentea/Overview.md)

食品法を考慮した設計を行い、県施設への展開と実地販売を達成。3DCADによる筐体設計、パッケージデザイン、地域ブランドとの連携を行った。

- [取得特許リンク](https://www.j-platpat.inpit.go.jp/c1801/PU/JP-2021-115207/11/ja)

---

### 🗺 地図測量・大会運営（オリエンテーリング） [概要](Other_Orienteering/Overview.md)

600名超参加の国内5位規模大会にて、競技エリア責任者として以下を実施：

- RTK測量、無線通信、特殊地図技術
- CADにより3Dメッシュ・ベクトルマップ作成
- 地権者・自治体との交渉による土地使用許可
- [地図例]

---

## 📫 Get in Touch

- Email: [yktsr1212@gmail.com](mailto:yktsr1212@gmail.com)
- Twitter: ※現在非公開

---

