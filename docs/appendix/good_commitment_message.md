# コミットメッセージの書き方
## コミットメッセージの必要性
コミットログのうちコードの変更履歴には変更箇所の差分はわかりますが、コードの変更意図はわかりません。  
その変更意図を記述するのがコミットメッセージです。  
コミットメッセージは他人あるいは未来の自分が読むことになるのでわかりやすく書く必要があります。  


## 良いコミットメッセージとは
1. コードの変更意図を明確にする
    1. どのように変更したかではなく、なぜ変更したかを書く
    2. 一つの目的に一つのコミット
2. 関連情報を記述する
    - 変更に至った背景を書く(チケット番号など)


## 具体的な書き方
コミットメッセージの冒頭にプレフィックスを書く

| プレフィックス | 内容 |
|:---|:---|
|feat: |新機能 |
|move: |ファイルの移動やリネーム |
|delete: |ファイルの削除 |
|fix: |バグの修正 |
|docs: |ドキュメントの変更 |
|style: |スペースやフォーマット等の動作に影響しないコードの変更 |
|refactor: |バグの修正や機能の追加をしないコード変更 |
|perf: |パフォーマンスを向上のためのコード変更 |
|test: |テストの追加や変更|
|chore: |ドキュメント生成用などの補助のライブラリやツールの変更 |


## 例

`style: インデントをタブに統一`  

`docs: たいぽ`  

```
refactor: hogeが非推奨になるのでfugaに変更
hoge/fugaのドキュメントのURL
```  



