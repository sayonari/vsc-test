
# マークダウンの書き方

## テストのしまくり
改行は  
どのようにいれるのか
半角スペースを2つ入れる

*これは*
**アスタリスク**で
***並べている***
_アンダースコアでも_
おなじ
*強調のテスト*
_強調のテスト_

順番に
イタリック
Bold
イタリック＆Bold
となるみたい．

~~やっぱりやめた~~

プログラムは`printf("西村良太は，%02d歳", ryota.Age);`です

* だんだんリストになるよ
	- りすと
		+ リスト

1. 番号付きリスト
1. 番号付きリスト

> ここは引用
> 引用されています
>> 二重引用になります
>>このように

	class Hoge
 		def hoge
 			print 'hoge'
		end
	end

---
[Google先生](https://www.google.co.jp/)

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

|header1|header2|header3|
|:--|--:|:--:|
|align left|align right|align center|
|a|b|c|


