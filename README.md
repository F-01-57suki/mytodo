# テストアカウント（操作OK）
- アカウント名：TestUser2021
- パスワード　：TestPass2021

# 概要
- タスク管理ウェブアプリケーション（PC向け）
- ボードに付箋を貼るイメージで、自分だけのTODOリスト作成
  - DB操作の基本を復習する意味で、会員登録やセッションを用いたログインなどの機能

## 頑張った・苦労した点
- mysqli（手続き型）によるＤＢ操作をしっかり使って作成
  - PDOを習う前に作成を始めたのでmysqli……
- 付箋を別ボードに張り替える際は、順番に違和感がないようボード最下部へ追加するよう実装

# 操作方法
1. 新規登録後、ログイン（作成済みテストアカウントは[こちら](https://github.com/F-01-57suki/mytd/blob/main/README.md#%E3%83%86%E3%82%B9%E3%83%88%E3%82%A2%E3%82%AB%E3%82%A6%E3%83%B3%E3%83%88%E6%93%8D%E4%BD%9Cok)）
2. 右上のメニューから「＋」ボタンでボードや付箋の新規作成
3. 各付箋の右上ボタンから編集や削除
4. ボード名の右「…」ボタンからボードの編集や色変え、削除
5. 右上のダウンロードアイコンから、CSVダウンロード
6. 右上のユーザアイコンから、ログイン情報の変更や退会
7. 右上のログアウトアイコンからログアウト

# 今後の追加機能
- PDOに改修
- ラベルにも編集や色変え
- タブレットやスマホ対応に手が回らなかったので、追々対応したい
