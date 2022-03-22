# エミュレータと自分のスマホ

Flutterプロジェクトを作成する。

```console
$ flutter create sake_memo
Creating project sake_memo...
Running "flutter pub get" in sake_memo...                        2,076ms
Wrote 96 files.

All done!
In order to run your application, type:

  $ cd sake_memo
  $ flutter run
$
```

なにはともあれ、構成管理をする。

```console
$ cd sake_memo
$ git init
$ git add .
$ git commit -m 'First commit'
```

ビルドして実行すると、ブラウザが立ち上がって、サンプルアプリが立ち上がります。

```console
$ flutter run
```

![](../images/1_01_counter_app.png)

