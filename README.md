# Anime Collection App 🎴

アニメ作品をカード形式で一覧表示できるシングルページアプリケーション（SPA）です。
今期アニメから作品を探し、キャラクターや声優情報を直感的に確認できるなど、軽量でスムーズなUXを重視しています。
このリポジトリは、フロントエンドとバックエンドの2つのプロジェクトの入口になります。

## 🔗 サンプルデプロイ
- Webアプリ公開URL：https://toshimitsu-m.github.io/frontend-vue/#/AnimeHome

## 📦 構成リポジトリ

| リポジトリ名 | 技術 | 説明 |
|-------------|------|------|
| [`frontend-vue`](https://github.com/toshimitsu-m/frontend-vue) | Vue.js / TypeScript / Tailwind CSS | UI・UX、ローカルでのカード管理機能 |
| [`backend-spring`](https://github.com/toshimitsu-m/backend-spring) | Spring Boot / REST API / DynamoDB | アニメ情報に対するコメントを保存・取得を行うAPIサーバー |

## 🗂 機能一覧（予定含む）

- [x] アニメカードの表示（Vue）
- [x] お気に入り登録機能（localStorage）
- [ ] ユーザー認証（Firebase予定）
- [ ] アニメ情報の取得・登録（Spring予定）

## 🧠 技術選定と工夫

- **Vue 3 Composition API** による状態管理の柔軟性
- **Tailwind CSS** によるコンポーネントの迅速なスタイリング
- **REST API設計** を意識したSpring構成
- 今後のAWSデプロイやCI/CD化も視野に入れた設計

## 📖 セットアップ手順（予定）

※ 各リポジトリのREADME参照。将来的にDocker構成の統合も検討中。

---

## ✍️ 作者

- GitHub: [@toshimitsu-m](https://github.com/toshimitsu-m)

---

