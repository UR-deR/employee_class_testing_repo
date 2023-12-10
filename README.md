# テスト実行方法

1. 以下のコマンドでモジュールのインストールを行なってください。

```sh
npm i
```

2. Box にアップロードされている`src`フォルダーを、このリポジトリの`package.json`と同じ階層に配置してください。


3. 以下のコマンドでテストが実行できます。

```sh
npm test
```

**コマンド実行結果**

```sh
❯ npm test

> employee_class_test_environment@0.0.0 test
> vitest --run


（中略）

 Test Files  5 passed (5)
      Tests  47 passed (47)
   Start at  17:02:20
   Duration  362ms (transform 363ms, setup 0ms, collect 524ms, tests 26ms, environment 1ms, prepare 395ms)

```