# Universal Sentence Encoder (USE) を学ぶ

## Universal Sentence Encoder (USE)とは

Universal Sentence Encoder (USE) は、テキストデータを512次元の組込データにエンコードするモデルです。

USEにより生成されたデータは、[感情分類](https://en.wikipedia.org/wiki/Sentiment_analysis)や[テキスト類似度](https://en.wikipedia.org/wiki/Semantic_similarity)分析等、自然言語処理の入力データとして使用できます。

この例で利用しているモデルは lite モデルですが、Transformer アーキテクチャをベースにし、8kの語彙[vocabulary](https://storage.googleapis.com/tfjs-models/savedmodel/universal_sentence_encoder/vocab.json)を使用しています。

参照：[https://github.com/tensorflow/tfjs-models/tree/master/universal-sentence-encoder](https://github.com/tensorflow/tfjs-models/tree/master/universal-sentence-encoder)

##  デモ

[https://t-cool.github.io/universal-sentence-encoder-demo/](https://t-cool.github.io/universal-sentence-encoder-demo/)

## ライセンス

Apache License 2.0
