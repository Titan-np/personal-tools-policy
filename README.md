# [個人用ツールのポリシー](https://titan-np.github.io/personal-tools-policy/)

作者が個人で利用するツールに共通の、概要・プライバシーポリシー・利用規約のページです。  
GoogleのOAuth同意画面など、外部サービスの認可設定に登録するURLとして使うため、GitHub Pages で公開しています。

---

## 使い方

各ツールの認可設定（Googleの場合は「Google Auth Platform → ブランディング」）に、以下のURLを登録します。

| 項目             | URL                                                      |
| ---------------- | -------------------------------------------------------- |
| ホームページ     | `https://titan-np.github.io/personal-tools-policy/`         |
| プライバシーポリシー | `https://titan-np.github.io/personal-tools-policy/#privacy` |
| 利用規約         | `https://titan-np.github.io/personal-tools-policy/#terms`   |

### フォルダ構成

- `index.html`：公開するページ本体（GitHub Pages の公開元は main ブランチの直下）
- `.nojekyll`：Jekyll による変換を止め、README.md などがページとして公開されないようにするための空ファイル

## 制約・注意点

- リポジトリ名を変えるとURLが変わり、登録済みの全ツールで再登録が必要になります。
- 外部へデータを送信するツールを作る場合は、プライバシーポリシーの「3. データの保存」の改訂が必要です。

## 免責事項

- 本リポジトリは、作者個人のツールのためのものです。他の方の利用は想定していません。
