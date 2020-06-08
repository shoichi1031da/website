# GitHub Pages で、じぶんのウェブサイトをつくろう！

## ひとまず作ってみよう！

1. このリポジトリを右上にあるForkを押して自分のリポジトリとしてコピーする
2. 自分のリポジトリの設定(Settings)を開く
3. GitHub Pages の項目までスクロールし、Sourceを[master brunch]に変更する
4. もう一度 GitHub Pages の項目までスクロールすると書いてあるリンクを新しいウィンドウで開いておく
5. すぐには表示されないので、待っている間にカスタマイズ！自分のリポジトリの index.html を開く
6. 右上の鉛筆マークで編集モードにする
7. &lt;h1&gt;たいとる&lt;/h1&gt;とあるところを好きなタイトルに変える
8. 画面下の「commit changes」を押す
9. さっき開いたウィンドウをリロードしてみる
10. 数分すると、編集したタイトルに変わる！
11. 以降、編集、コミット、ちょっと待って、反映でウェブサイトづくりができる

## 画像をつけよう

1. pngかjpg画像を準備する
2. 半角英数字を使った空白を含まないファイル名に変更する （日本語名やトラブルの元になる）
3. [Upload files]を押す
4. 画像ファイルをドロップして、コミットする
5. index.html を編集する
6. &lt;img src="imgfile.jpg"&gt; と、&lt;h1&gt;タイトル&lt;/h1&gt; の前の行に書く (imgfile.jpg はアップロードしたファイル名に）
7. コミットし、しばらく待って、リロードすると表示される！

## GitHub Desktop を使って効率アップ！

1. [GitHub Desktop](https://desktop.github.com/)をダウンロードする
2. 自分のリポジトリの右側[clone or download]を押し、[Open in Desktop]を押す
3. ダウンロードするフォルダをローカルパスとして指定し[Clone]する
4. ダウンロードしたフォルダの中の index.html をブラウザで開くと表示される
5. [VSCode](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)などのエディタを使って、index.html や index.css を編集し、サイトをつくる
6. GitHub Desktop で、コミットする（更新用のメモは必須、”更新”など、一言でもOK！）
7. [Fetch origin] を押し、サーバーにプッシュする
8. しばらく待つと、反映される

## 独自ドメインを設定しよう

1. ドメインを用意する
2. [Create new file]を押し、中に設定したいドメイン名を書き、CNAME という名前にしてコミットする
3. DNSを設定する （[詳細](https://help.github.com/ja/github/working-with-github-pages/configuring-a-custom-domain-for-your-github-pages-site))
