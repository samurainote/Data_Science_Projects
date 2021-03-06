# Data Science Portfolio
## 自然言語処理を中心とした機械学習およびディープラーニングの個人プロジェクト
This Repository contains following 3 kinds of projects what I have done as a self-taught ML/NLP Enthusiast.
約3ヶ月の間に実装した機械学習理論や自然言語処理のコードがまとめてあります.
I've also published several articles on Medium about Data Science and Natural Language Processing.
機械学習や自然言語処理に関する記事をMediumに投稿しています. [#ShortcutNLP_medium.com](https://medium.com/shortcutnlp)

## Implementation Project


### Natural Language Processing 自然言語処理

- #### Seq2Seq センテンスtoセンテンス
  - [Automatic Encoder-Decoder Seq2Seq: English Chatbot](https://github.com/samurainote/chatbot_slack_keras) Seq2Seqによる英語チャットボット.
  - [Encoder-Decoder Seq2Seq with Attention: English-Japanese Machine Translation](https://github.com/samurainote/seq2seq_translate_slackbot) アテンションを用いた日英翻訳.
  - [Bidirectional LSTM: Abstract Text Summarization](https://github.com/samurainote/Text_Summarization_using_Bidirectional_LSTM) 双方向LSTMを用いた文脈を捉える抽象型文章要約.
  - [GRU: Text_Generation](https://github.com/samurainote/Text_Generation_using_GRU) GRUリカーレントネットワークを用いた文章生成.

- #### Multi-modal Deep Learning マルチモーダルディープラーニング.
  - [CNN and RNN: Image Caption Generation](https://github.com/samurainote/CaptionGeneration_CNNandLSTM_Keras) VGG16とGloveで転移学習を行なった画像キャプション生成.
  - [Convolutional Neural Network: Speech Recognition](https://github.com/samurainote/Speech_Recognition_CNN)　畳み込みニューラルネットワークを用いた音声認識.
  - [OpenCV: Text Extraction from Image](https://github.com/samurainote/OCR_Text_Detection_from_Image) 画像からテキスト情報を抽出する文字起こし機能の実装.

- #### Recommend System レコメンドエンジン × 自然言語処理
  - [Question-Answer Recommendation Engine from Kaggle]

- #### Classification 分類 × 自然言語処理
  - [LDA from Topic Model: News Contents Classification](https://github.com/samurainote/Topic_Model_LDA_for_Text_Classification_with_abcnews) 潜在的ディリクレ配分法（LDA）を用いたコンテンツ分類.
  - [LSTM for Tweet: Sentiment Analysis on Twitter](https://github.com/samurainote/LSTM_for_Sentiment_Analysis_with_Twitter_textdata) LSTMを用いたツイートに対する感情分析.
  - [Doc2Vec: Hate Speech Detection from Tweet](https://github.com/samurainote/Sentimentment_Analysis_for_hatespeech) Doc2Vecを用いたツイートからのヘイトスピーチ検出.
  - [Bidirectional LSTM: Sentiment Analysis on reviews](https://github.com/samurainote/Bidirectional_LSTM_Sentiment_Analysis_imbd) 双方向LSTMを用いた映画レビューにおける感情分析.
  - [CNN for Long Text: News Article Classifications](https://github.com/samurainote/CNN_Convolutional_NN_for_news_contents_classification) 長文テキストにCNNを用いたニュース記事分類.
  - [Gaussian Naive Bayes for text: Spam Filter for e-mail](https://github.com/samurainote/Text_Classificasion_Spamfilter_with_GaussianNB) ナイーブベイズ分類器によるEメールスパムフィルター.
  - [TF-idf and NaiveBayes: Author Identification](https://github.com/samurainote/TF-idf_and_NaiveBayes_for_Author_Identification) Tf-idfとナイーブベイズ分類器による著者判定.
  - [Stacked RNN vs Simple RNN: Sentiment Analysis on movie review](https://github.com/samurainote/StackedRNN_for_Sentiment_Analysis) 複数のリカーレントネットワークを用いた感情分類.
  - [LSTM with Chainer: Text Classification](https://github.com/samurainote/Text_Classification_LSTM_Chainer/blob/master/code/main_code.ipynb) ChainerによるLSTMを用いた文章分類のモディフィケーション.

- #### Regression 回帰 × 自然言語処理
  - [Regression: Mercari Price Suggestion Challenge](https://github.com/samurainote/mercari_price_prediction): ＊現在進行中　CtoC second-hand market platform "mercari" における出品アイテムの価格予測.

- #### Preprocessing 前処理 × 自然言語処理
  - [Preprocessing Simplest Code-kit for NLP](https://github.com/samurainote/nlp_preprocessing_tool-kit) 自然言語処理における前処理:


### Computer Vision by Machine Learning コンピュータビジョンと画像認識

- #### Image Processing 画像認識 × ディープラーニング
	- [Face Detection](https://github.com/samurainote/Face_Detection_with_OpenCV/blob/master/Face%20Detection.ipynb) 人間の顔認識:
  - [Dog or Cat by CNN](https://github.com/samurainote/Image_Classifier_Dog_or_Cat_with_Keras/blob/master/dogvscat.ipynb) 犬と猫のバイナリ分類問題:
  - [CNN for Sign Language Images](https://github.com/samurainote/CNN_for_Sign_Language_Images) 手話画像認識:
  - [CNN for Hand-written Digits](https://github.com/samurainote/CNN_for_Image_Processing_with_MNIST) 手書き数字認識:
  - [Simple Neural Network for Hand-written Digits](https://github.com/samurainote/SimpleNN_for_Handwritten_digits) 手書き数字認識:

### Recommend System by Machine Learning レコメンドシステム

- #### Recommendation Engine 推薦エンジン
  - [Collaborative Filtering with SVD: Book Recommender System](https://github.com/samurainote/Book_Recommendation) 本レコメンドエンジン:
  - [Content Based: Movie Recommender System](https://github.com/samurainote/Content_based_movie_recommendation)　映画レコメンドエンジン:


### Kaggle Challenfes: Prediction by Machine Learning ディープラーニングと機械学習を用いた予測モデル

- #### Regression 回帰 × 予測
  - [Regression: HR Salary Prediction](https://github.com/samurainote/Regression_HR_Salary_Prediction/blob/master/maincode_hitters.ipynb) 年収予想:
  - [Simple RNN for Time-Series Data: Apple Stock Price Prediction](https://github.com/samurainote/Simple_RNN_for_Apple_stock_price_prediction) 株価予測:
  - [Regression: Boston House Price](https://github.com/samurainote/Boston_House_Price_with_Linear_Regression/blob/master/Boston_House_Price_with_Linear_Regression.ipynb) ボストンハウスプライスML:
  - [Regression: Multi-layerNN_for_Regression_BHP](https://github.com/samurainote/Multi-layerNN_for_Regression_BHP) ボストンハウスプライスDL:

- #### Classification 分類 × 予測
  - [Classification: IBM Attrition Prediction](https://github.com/samurainote/ibm_attrition_classification): IBMの退職者予測.

  - [First Neural Network from scratch](https://github.com/samurainote/Neural_Network_from_scratch) ディープラーニングフロムスクラッチ.


### Machine Learning Foundation 機械学習のワークフロー Github&Medium

- #### Machine Learning Workflow 機械学習ワークフロー
  - [1. Data Preparation Phase on Medium](https://github.com/samurainote/1._Web_Scraping): Check it out [notebook on Github]
  - [2. Data Visualization Phase on Medium](https://github.com/samurainote/2._Data_Visualization):
  - [3. Data Cleaning Phase on Medium](https://github.com/samurainote/3._Data_Cleaning):
  - [4. Feature Engineering Phase on Medium](https://github.com/samurainote/4._Feature_Engineering):
  - [5. Apply Multiple Machine Learning Model Phase on Medium](https://github.com/samurainote/5._Model_Selection):
  - [6. Training&Testing Model Phase on Medium](https://github.com/samurainote/6._Model_Validation):
  - [7. Model Validation Phase on Medium](https://github.com/samurainote/7._Hyperparameter_Tuning):
  - [8. Hyperparameter Tuning Phase on Medium](https://github.com/samurainote/8._Gradient_Descent_and_Optimazation_Algorithm):
