# PN_text_score

# 単語のポジティブ/ネガティブによるテキストスコアリング

## 環境
macOS Sierra 10.12.6  
pyenv 1.1.3  
Anaconda 4.4.0 (64-bit)  
Python 3.6.1  
mecab of 0.996  
mecab-ipadic-neologd  

## フロー

1. テキストデータから 「助詞」「助動詞」「記号」以外の単語（日本語） に対して形態素解析  
1. 各単語の PN値 を取得する  
1. 各単語の PN値の平均 をとってテキストのスコアとする  

## 参考
[【Python】MeCabと極性辞書を使ったツイートの感情分析入門](http://www.statsbeginner.net/entry/2017/05/07/091435)  
[単語感情極性対応表](http://www.lr.pi.titech.ac.jp/~takamura/pndic_ja.html)  

