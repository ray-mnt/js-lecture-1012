# テクノロジー（藤原） 10/12課題

- テキストエディタ（Visual Studio Codeなど）でREADME.mdを開きます
- 下の欄（` ``` `で挟まれている部分）に、ChromeデベロッパーツールのConsoleで実行したログを丸ごとコピー＆ペーストしてください

```
//本来は3-1~3-8もできていたのですがwhile文の上限設定を失敗していたみたいで延々と実行結果が流れ続けるのでブラウザを再起動してしまいました
for (var i=0;i < 5;i++){
    console.log(i);
}
VM103:2 0
VM103:2 1
VM103:2 2
VM103:2 3
VM103:2 4
undefined
var i = 5;
undefined
while(i<20){
    console.log(i);
    i=i+3;
}
VM186:2 5
VM186:2 8
VM186:2 11
VM186:2 14
VM186:2 17
20
var i =5;
undefined
do{
    console.log(i);
    i=i+3;
}while(i<20);
VM262:2 5
VM262:2 8
VM262:2 11
VM262:2 14
VM262:2 17
20
var j = 30;
undefined
do{
    console.log(j);
    j = j +10;
}while(j<20);
VM366:2 30
40
do{
    console.log(j);
    j = j +10;
}whdo{
    console.log(j);
    j = j +10;
}while(j<20);ile(j<20);
```

## 例（下記の書き方をまねてください）

```
console.log('hello')
VM31:1 hello
undefined
```
