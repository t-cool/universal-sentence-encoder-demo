# Universal Sentence Encoder (USE) を学ぶ

## 説明

Universal Sentence Encoder (USE) は、テキストデータを512次元の組込データにエンコードするモデルです。

これらのデータは、[感情分類](https://en.wikipedia.org/wiki/Sentiment_analysis)や[テキスト類似度](https://en.wikipedia.org/wiki/Semantic_similarity)分析などの自然言語処理タスクの入力として使用できます。

このモジュールは TensorFlow.js の[`GraphModel`](https://js.tensorflow.org/api/latest/#loadGraphModel)を USE lite([TFHub上のモジュール](https://tfhub.dev/google/universal-sentence-encoder-lite/2)) に変換したもので、オリジナルの軽量版です。

lite モデルは、Transformer アーキテクチャをベースにしており、8kの語彙[vocabulary](https://storage.googleapis.com/tfjs-models/savedmodel/universal_sentence_encoder/vocab.json)を使用しています。

参照: [https://github.com/tensorflow/tfjs-models/tree/master/universal-sentence-encoder](https://github.com/tensorflow/tfjs-models/tree/master/universal-sentence-encoder)


## ライセンス

Apache License 2.0
