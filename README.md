# maynoid.github.io

Here is maynoid's website

### 作業とUP方法

src/ フォルダ配下が公開ソースとなります
(開発後、 /src → /docs に移す)

### リモートリポジトリの確認

> git remote -v

origin https://github.com/maynoid/maynoid.github.io.git (fetch)
origin https://github.com/maynoid/maynoid.github.io.git (push)

公開URL
https://maynoid.github.io/
\*.github.io という名前のリポジトリは、GitHub Pagesとして自動的にホスティングされます。リポジトリのルートにある index.html がトップページとして表示されます

### GitHub Pages の公開ソース変更方法

手順
リポジトリのSettingsを開く

https://github.com/maynoid/maynoid.github.io にアクセス
上部メニューの「Settings」タブをクリック
Pagesセクションに移動

左サイドバーの「Pages」をクリック
ソースを設定

「Build and deployment」セクションを確認
「Source」で以下のいずれかを選択:
方法A: ブランチとフォルダを指定

「Deploy from a branch」を選択
Branch: main（または任意のブランチ）
Folder: /docs を選択（/dist は選択肢にありません）
方法B: GitHub Actionsを使用

「GitHub Actions」を選択
カスタムワークフローで dist フォルダをデプロイ可能
注意点
GitHub Pagesのフォルダ選択肢は / (root) と /docs のみです。
