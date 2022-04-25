# RecSys2022
RecSys2022のデータ分析結果やモデルをまとめる．

## 分析ファイルの説明
data_check1.ipynb：データの基礎統計調査や，ナイーブなモデルの結果をまとめている  
prediction_by_pca.ipynb:特徴量に対するPCAによって`item`の距離を定義し，レコメンド．  
  
## ファイル構造
ファイル構造はこんな感じ．`data`の下に必要なデータがすべて入っていて，`分析`フォルダの下から参照している．  

├─.ipynb_checkpoints  
├─data  
│      candidate_items.csv  
│      item_features.csv  
│      README.txt  
│      README_win.txt  
│      test_final_sessions.csv  
│      test_leaderboard_sessions.csv  
│      train_purchases.csv  
│      train_sessions.csv  
│  
├─downloads  
│  │  KT_20220418_蜈ｱ襍ｷ.ipynb  
│  │  
│  └─.ipynb_checkpoints  
│          KT_20220418_蜈ｱ襍ｷ-checkpoint.ipynb  
│  
├─submits  
│      nearest_neighborhood_by_pca.csv  
│      nearest_neighborhood_by_pca_old.csv  
│      rank_table.csv  
│  
└─分析  
    │  data_check1.html  
    │  data_check1.ipynb  
    │  data_check1.pdf  
    │  prediction_by_pca.ipynb  
    │  rank_時間帯ごと.xlsx  
    │  rank_曜日ごと.xlsx  
    │  ランキング_時間帯ごと_20220420.png  
    │  分析まとめ.xlsx  
    │  
    └─.ipynb_checkpoints  
            data_check1-checkpoint.ipynb  
            prediction_by_pca-checkpoint.ipynb  
