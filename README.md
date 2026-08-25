# 施設警備2級 超問題集

GitHub Pagesでそのまま公開できる静的Webアプリです。

## 公開方法

1. ZIPファイルを展開します。
2. 展開後、このフォルダ内にあるファイルとフォルダを、同じ階層のままGitHubリポジトリへアップロードします。
3. GitHubのリポジトリで「Settings」→「Pages」を開きます。
4. 「Build and deployment」のSourceを「Deploy from a branch」にします。
5. Branchを「main」、フォルダを「/ (root)」にして「Save」を押します。
6. 数分後、GitHub Pagesの公開URLが表示されます。

重要：`index.html`がリポジトリの一番上（公開ルート直下）にある状態でアップロードしてください。ZIPの親フォルダだけをアップロードすると表示されません。

## 必要なファイル

- `index.html`
- `assets/app.js`
- `assets/app.css`
- `service-worker.js`
- `manifest.json`
- `icons/icon-180.png`
- `icons/icon-192.png`
- `icons/icon-512.png`
- `.nojekyll`

## 主な機能

- 全10分野・650問
- 本番模試20問・制限時間60分・90％合格判定
- ランダム演習、分野別演習
- 苦手問題の自動登録と再出題
- 問題の保存
- 成績、正答率、履歴の端末内保存
- ホーム画面追加とオフライン再利用

## 注意

- 学習記録はブラウザの端末内に保存されます。別のスマートフォンとは自動同期されません。
- PWA・オフライン機能は、GitHub PagesのHTTPS公開後に有効になります。
- この問題集は公式出題範囲と現行法令を基にしたオリジナル問題です。非公開の公式過去問を転載したものではありません。
