# Data Science

このリポジトリの目的は，データサイエンスについて学んだ内容を整理することです．データ分析を行いながら，PythonでEDA，可視化を行う方法，パイプラインクラスやAutoML，その他ライブラリの実践的な使い方を整理，実装しました．また，データ収集に必要なスクレイピングを行うためのライブラリの使い方についても整理，実装しました．

具体的には，回帰タスクと分類タスクを設定し，取り組みました．

---

## スクレイピング

- Requests
- BeautifulSoup4

## EDA・可視化

- Pandas
- Pandas-profiling
- Matplotlib
- seaborn

## 分析（回帰・分類），仮説検証

- Scikit-Learn（PipeLine）
- LightGBM
- Oputuna
- XGBoost

## AutoML

- Pycaret

## モデル解釈

- SHAP

# 課題

## Bostonデータの予測・モデル構築

データ：ボストンの住宅価格

この課題の目的は，回帰タスクを行う上で基本的なライブラリの使い方，評価指標について整理することです．

- [lgbm_reg.ipynb](https://github.com/HirotaYusuke/My-project/blob/main/Data-science/lgbm_reg.ipynb)
- [lgbm_oputuna_trainingapi.ipynb](https://github.com/HirotaYusuke/My-project/blob/main/Data-science/lgbm_oputuna_trainingapi.ipynb)
- [xgboost_reg.ipynb](https://github.com/HirotaYusuke/My-project/blob/main/Data-science/xgboost_reg.ipynb)
- [pipeline1.ipynb](https://github.com/HirotaYusuke/My-project/blob/main/Data-science/pipeline1.ipynb)
- [pipeline2.ipynb](https://github.com/HirotaYusuke/My-project/blob/main/Data-science/pipeline2.ipynb)
- [pipeline3.ipynb](https://github.com/HirotaYusuke/My-project/blob/main/Data-science/pipeline3.ipynb)
- [pycaret_reg.ipynb](https://github.com/HirotaYusuke/My-project/blob/main/Data-science/pycaret_reg.ipynb)

## Breast Cancerの分類・モデル構築

データ：乳癌の検査結果(悪性,良性)

この課題の目的は，分類タスクを行う上で基本的なライブラリの使い方，評価指標について整理することです．

- [lgbm_clf.ipynb](https://github.com/HirotaYusuke/My-project/blob/main/Data-science/lgbm_clf.ipynb)
- [xgboost_clf.ipynb](https://github.com/HirotaYusuke/My-project/blob/main/Data-science/xgboost_clf.ipynb)
- [pycaret_clf.ipynb](https://github.com/HirotaYusuke/My-project/blob/main/Data-science/pycaret_clf.ipynb)

## 住宅価格データのスクレイピング

分析するための実データを収集するため，ライブラリの使い方を整理したものです．データは，[SUMO](https://suumo.jp/chintai/tokyo/sc_shinjuku/?page=1)より，1ページ目から100ページ目まで，計8381件を収集しました．

- [Sumo_scraping.ipynb](https://github.com/HirotaYusuke/My-project/blob/main/Data-science/Sumo_scraping.ipynb)

# 環境

- Windows10
- Python3.8.10
