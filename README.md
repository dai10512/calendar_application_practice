# calendar_application_practice

<h2>カレンダーアプリで学ぶパッケージ開発を元に学習</h2>
conpassで開催された中條 剛（ちゅーやん）さんによるハンズオンイベントで、実際に作ってみました。
<br>
<br>


<img width="600" alt="スクリーンショット 2022-07-02 21 33 56" src="https://user-images.githubusercontent.com/38497198/177000978-569ba998-fbb7-4f99-b73c-288d42238d0c.png">



参照:https://flutter-jp.connpass.com/event/250745/

<h2>実際に作ったアプリ<h2>
<img src="https://user-images.githubusercontent.com/38497198/177000985-94190b60-91b1-4748-9086-14629520e386.png" width="250">

<h2>学習したポイント</h2>
・テストの仕組みが少し理解できた<br>
・パッケージリリース自体の方法（アプリのリリースよりはシンプルに見える）<br>
・DateTime型の特性として、下記の要領で月の最後の日が取得できると言うこと<br>


```
int _calcLastDate(DateTime date) {
    return DateTime(date.year, date.month + 1, 0).day;
}
```


