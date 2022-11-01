# seminar2
実験のためのPython＆Git入門（機械学習による関数近似実験）

## 環境の確認

第3回で想定している環境
- [ ] VSCodeにて開かれているシェルがBashである
    - `$ echo $0` でbashらしき名前であればOK（zshらしきものはNG）
- [ ] シェルの環境変数に`$SEMINAR2`と`$VENV`が設定されている
    - `$ echo $SEMINAR2`と`$ echo $VENV`を実行した際にそれぞれのパスが表示されればOK
- [ ] Python 3.10.8を使用している
    - `$ python --version`の出力に3.10.8が含まれていればOK
    - `$ python3.10 --version`が成功してもOK
- [ ] GitHub上のリソースが手に入る
    - `$ cd $SEMINAR2/tutorial`したのち`$ git pull --set-upstream origin main`でエラーが出なければOK
- [ ] VSCodeのGUIでGitのコミットができる
    1. `$SEMINAR2/hello_python`以下に`.gitignore`という空のファイルを作成し保存
    1. これをコマンドではなくVSCodeのGUIから`add`＆`commit`できればOK
