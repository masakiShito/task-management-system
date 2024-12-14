# 個人開発
## この資料について
この資料は、個人開発において、アイデアを出すための資料です。
<br>この資料に記載されている内容は全て決定ではなくあくまでアイデアとして記載しています。

## アイデア
### 理想のタスク管理システム
無料で使えるツールでは、タスク管理システムが使いにくいと感じることがあります。
<br>そのため、理想のタスク管理システムを作成したいと考えています。

### イメージ
- タスクの追加が簡単
- スケジュールの設定が簡単
- タスクの進捗が一目でわかる
- タスクの優先度が設定できる
- タスクのカテゴリーが設定できる
- タスクの期限が近づいたら通知が来る
- WBSが作成できる
- タスクの進捗がグラフで見れる
- サマリーが作成できる
- AIがタスクの進捗を予測してくれる

### 技術選定
- フロントエンド: Next.js
- バックエンド: Nest.js
- データベース: MySQL
- インフラ: AWS
- その他: AI駆動開発、Prisma、TypeScript、Tailwind CSS

### 画面イメージ
| 画面 | 説明                   |
| ---- |----------------------|
| ログイン画面 | ログイン画面です。（個人開発なので不要） |
|ダッシュボード画面 | タスクの進捗が一目でわかるダッシュボードです。 |
| タスク一覧画面 | タスクの一覧が表示されます。       |
| タスク詳細画面 | タスクの詳細が表示されます。       |
|プロジェクト一覧画面 | プロジェクトの一覧が表示されます。   |
|WBS画面 | WBSが表示されます。           |
| 設定画面 | 設定が表示されます。           |

### 機能イメージ
1. **ログイン画面**
   1. ログインができる
2. **ダッシュボード画面**
   1. タスクの進捗が一目でわかる
   2. タスクの期限が近づいたら通知が来る
   3. 全タスク、プロジェクトの進捗がグラフで見れる
   4. サマリーが見れる
   5. AIがタスクの進捗を予測してくれる
   6. タスクの追加が簡単
   7. スケジュールの設定が簡単
3. **タスク一覧画面**
   1. タスクの一覧が表示される
   2. タスクの進捗が一目でわかる
   3. タスクの優先度が設定できる
   4. タスクのカテゴリーが設定できる
   5. タスクの期限が近づいたら通知が来る
   6. タスクの追加が簡単
   7. スケジュールの設定が簡単
4. **タスク詳細画面**
   1. タスクの詳細が表示される
5. **プロジェクト一覧画面**
   1. プロジェクトの一覧が表示される
6. **WBS画面**
   1. WBSが表示される
   2. タスクの進捗が一目でわかる
7. **設定画面**
   1. 設定が表示される