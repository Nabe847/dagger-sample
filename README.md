# 始め方

1. Dockerが動いてることを確認する
    ```
    $ docker -v
    Docker version 20.10.12, build e91ed57
    ```

1. リポジトリのルートディレクトリで使用可能なアクションを確認する
    ```
    $ dagger do --help
    Usage: 
    dagger do  [flags]

    Options

    Available Actions:
    hello Say hello by writing to a file <= ここが出ていればOK

    (以下略)
    ```

1. コマンドを実行する
    ```
    $ dagger do hello
    ```
    `hello-world.txt` リポジトリのルート直下に出力される