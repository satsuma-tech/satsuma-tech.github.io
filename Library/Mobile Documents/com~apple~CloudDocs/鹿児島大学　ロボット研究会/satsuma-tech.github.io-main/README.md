# SATSUMA TECH 公式Webサイト

鹿児島大学「SATSUMA TECH」の公式Webサイトのソースコードを管理するリポジトリです。
NHK学生ロボコン等への出場を目指す当団体の活動発信、新入生の勧誘、およびスポンサー企業様からの協賛募集を目的として運用しています。

🌐 **公式サイトURL:** https://satsuma-tech.github.io/

---

## 🛠 採用技術・構成 (Tech Stack)

本サイトは、サークル内での引き継ぎやすさと保守性を考慮し、複雑なビルド環境（Node.jsなど）を必要としないシンプルな構成で構築されています。

- **ホスティング**: GitHub Pages
- **フロントエンド**: HTML5, JavaScript (Vanilla)
- **CSSフレームワーク**: [Tailwind CSS](https://tailwindcss.com/) (CDN経由で読み込み)
- **スライダー実装**: [Swiper.js](https://swiperjs.com/) (CDN経由)
- **ヘッドレスCMS (お知らせ管理)**: [microCMS](https://microcms.io/)
- **お問い合わせ窓口**: Google フォーム
- **アクセス解析**: Google Analytics

---

## 📂 ディレクトリ構成 (Directory Structure)

```text
.
├── index.html       # トップページ
├── activity.html    # 活動内容
├── infomation.html  # お知らせ一覧
├── join.html        # 入部案内・募集要項
├── about.html       # 団体概要
├── sponsors.html    # スポンサー
├── contact.html     # お問い合わせ
├── privacy.html     # プライバシーポリシー
└── images/          # 画像ファイル
    ├── logo/        # サイトUI用のロゴデータ
    ├── NHK/         # NHK学生ロボコンの機体写真
    ├── naturobo/    # 九州夏ロボコンの機体写真
    ├── catchrobo/   # キャチロボの機体写真
    ├── kadaisai/    # 鹿大祭の写真
    ├── kouryu/      # 技術交流会の写真
    └── sponsor/     # スポンサーロゴ