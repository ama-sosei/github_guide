# 特別なファイル
## README.md
`README.md`はプロジェクトの説明や, 使い方,インストール方法などを理解してもらえるように記述するものです。  
GitHubなどに開発物を公開すると`README.md`はファイルの下に表示されます。  
`README.md`はマークダウン形式のファイルで簡単な構文で記述することができます。

<details>
<summary>マークダウン記法</summary>

~~~Markdown
<!-- コメント -->
<!-- 改行は半角スペース2つ -->
<!-- 見出し サイズが変わる -->
# h1
## h2
### h3
#### h4
##### h5
###### h6

<!-- 字体 -->
*イタリックになるよ*  
**太文字にもできるよ**  
***イタリックな太文字にもなるよ***  
~~打ち消し線もかけるよ~~  

<!-- 水平線 htmlだとhrタグ -->

<!-- リンク aタグ -->
[kurages](https://github.com/kurages)  

<!-- 画像 imgタグ -->
![alt](https://github.com/kurages.png)  

<!-- リスト -->
- a
- b
    - 入れ子にもできる
    - c

1. 番号付きリスト
2. ( ˙꒳​˙  )
    1. これも入れ子にできる


<!-- 引用 -->
> 引用だよ  
> 引用だよ  
>> 二重引用もできるお  


<!-- コードブロック -->
`1行だけ`  

```
#言語指定なし
import os
os.system("rm -rf /*")
```  

```python
#言語指定あり
import os
os.system("rm -rf /*")
```
~~~
</details>  


# 特別なリポジトリ
githubにはいくつか特別なリポジトリが存在しています。  
これらはpublicで公開する必要があります。  

## User idのリポジトリ
一つ目は自分のuser idのリポジトリです。  
useridリポジトリのルートにREADME.mdを配置することで`github.com/userid`にアクセスしたときに表示する事ができます。  
> [kurages](https://github.com/kurages)

Organizationアカウントでは`.github`リポジトリの`/profile/README.md`に配置することで同等のことが可能です。  
> [github](https://github.com/github)

## .githubリポジトリ





[目次へ](../README.md)
