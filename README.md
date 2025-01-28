## 参考記事
https://typescriptbook.jp/tutorials/make-a-simple-function-via-cli

## プロジェクトを作る
### Reactプロジェクトのひながたを生成
`npm create vite@latest like-button -- --template react-swc-ts`

### Reactなど依存パッケージをインストール
`cd like-button`
`npm install`

インストールされたReactのバージョンを確認コマンド
`npm list react`

```
like-button@0.0.0 /Users/test/like-button
├─┬ react-dom@18.3.1
│ └── react@18.3.1 deduped
└── react@18.3.1
```

### Reactのローカル開発サーバーを起動
`npm run dev`


### Next.jsをセットアップする
パッケージ管理ツールとしてYarnをインストールする。
```npm install -g yarn```

最初に`yarn create next-app`コマンドでプロジェクトを作成する。TypeScriptをベースにしたプロジェクトを作成するために `--example with-typescript` を指定。`random-cat` はリポジトリ名となる部分。
```
yarn create next-app --example with-typescript random-cat
```

### 開発サーバーを起動する
```yarn dev```

### 不要なファイルを消す
```rm -rf pages utils interfaces components```

