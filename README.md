# sample-codespaces-get-secret

Github の Codespaces Secret を取得してみるテスト

## Github でやったこと

- `.devcontainer`フォルダ、付随するファイルの作成
- Codespaces secret で`TEST_SECRET`の作成

# 結論

- Decvontainer 内の terminal から Github Codespaces の Secret を取得するには

  `gh auto login`が必要なのでちょっと面倒。
