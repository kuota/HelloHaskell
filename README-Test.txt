


実行:
$ cd /home/enokida/workspace/Haskell/unittests/hspec
$ runhaskell test/MathSpec.hs

実行(2)
$ cabal configure --enable-tests     # dist ディレクトリが生成
$ cabal build
$ cabal test



参考:
https://hspec.github.io/getting-started.html
https://github.com/kazu-yamamoto/unit-test-example/blob/master/markdown/ja/tutorial.md
http://qiita.com/taiki45/items/e1b7e9abcd8bd0b42aff
https://stackoverflow.com/questions/12133320/cabal-output-is-redirected-but-not-generated   # Main未定義だと cabal build で 警告
