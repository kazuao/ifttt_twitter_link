# GithubとTwitterを連携する方法



## 概要

なにか技術的なアウトプットを行いたいなーと思った。

ブログやQiitaを書くのもいいかと思ったけど、まずはGithubとTwitterを主戦場にしようと思ったわけです。

そこで、IFTTTを使って、GithubとTwitterを連携できないかなーと調べてみたら、かんたんにできそうということで、やってみました。



## 用意するもの

1. Twitterアカウント
2. GitHubアカウント
3. IFTTTアカウント



## 手順

1. IFTTTを開き、ログインします。

2. 検索ボックスから、「GitHub Twitter」等で検索します。

3. 検索された結果から、「Tweet new repositories from my Githubuser」というものを選択します。

4. 「Connect」を押下すると、連携する画面が出ます。（IFTTTにログインしていないと、IFTTTのログイン画面が出る）
![スクリーンショット 2020-03-27 19 30 42](https://user-images.githubusercontent.com/58547962/77817435-2015c580-710e-11ea-8fb0-493d004f1725.png)

5. Twitterのアカウントが複数ある場合、英語だからと言って、油断して「進む」的なボタンを連打していると違うアカウントに連携される場合があります。（裏アカに連携された）

6. 最後にSave画面が出ます。

   ここで、GithubのユーザネームをGithubに登録しているユーザネームに設定する。

   Twitterの部分は投稿の文章を変えられます。
   ![スクリーンショット 2020-03-28 15 37 01](https://user-images.githubusercontent.com/58547962/77817456-3cb1fd80-710e-11ea-8ee0-7717b24b212d.png)

7. 最後に「Save」ボタンを押下すると連携されます。

思ったTwitterアカウントに連携されない場合は、「Tweet new repositories from my Githubuser」に連携する作業を行う前に、IFTTTで「Twitter」と検索し、先に任意のTwitterアカウントを連携する必要があります。

なんか融通効きづらいですが、我慢しましょう。

これで、Githubで新しいリポジトリを作成するとTwitterに連携されるようになりました。
![スクリーンショット 2020-03-28 15 54 48](https://user-images.githubusercontent.com/58547962/77817459-43407500-710e-11ea-9890-7177c8376ee4.png)

かんたんですが、以上となります。
