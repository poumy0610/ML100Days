# 5rd-ML100Days

## 機器學習概論
1. [資料介紹與評估資料 (申論+程式碼)]
挑戰是什麼?動手分析前請三思
1. [機器學習概論 (申論題)]
機器學習、深度學習與人工智慧差別是甚麼? 機器學習又有甚麼主題應用?
1. [機器學習-流程與步驟 ( 申論題)]
資料前處理 > 訓練/測試集切分 >選定目標與評估基準 > 建立模型 > 調整參數。熟悉整個 ML 的流程
1. [EDA/讀取資料與分析流程]
如何讀取資料以及萃取出想要了解的信息

## 資料清理數據前處理
5. [如何新建一個 dataframe? 如何讀取其他資料? (非 csv 的資料)]
1 從頭建立一個 dataframe 2. 如何讀取不同形式的資料 (如圖檔、純文字檔、json 等)
5. [EDA: 欄位的資料類型介紹及處理]
了解資料在 pandas 中可以表示的類型
5. [特徵類型]
特徵工程依照特徵類型，做法不同，大致可分為數值/類別/時間型三類特徵
5. [EDA資料分佈]
用統計方式描述資料
5. [EDA: Outlier 及處理]
偵測與處理例外數值點：1. 透過常用的偵測方法找到例外 2. 判斷例外是否正常 (推測可能的發生原因)
5. [數值型特徵 - 去除離群值]
數值型特徵若出現少量的離群值，則需要去除以保持其餘數據不被影響
5. [常用的數值取代：中位數與分位數連續數值標準化]
偵測與處理例外數值 1. 缺值或例外取代 2. 數據標準化
5. [數值型特徵-補缺失值與標準化]
數值型特徵首先必須填補缺值與標準化，在此複習並展示對預測結果的差異
5. [DataFrame operationData frame merge/常用的 DataFrame 操作]
 1 常見的資料操作方法 2. 資料表串接
5. [程式實作 EDA: correlation/相關係數簡介]
 1 了解相關係數 2. 利用相關係數直觀地理解對欄位與預測目標之間的關係
5. [EDA from Correlation]
深入了解資料，從 correlation 的結果下手
5. [EDA: 不同數值範圍間的特徵如何檢視/繪圖與樣式Kernel Density Estimation (KDE)]
1 如何調整視覺化方式檢視數值範圍 2. 美圖修修 - 轉換繪圖樣式
5. [EDA: 把連續型變數離散化]
簡化連續性變數
5. [程式實作 把連續型變數離散化]
深入了解資料，從簡化後的離散變數下手
5. [Subplots]
探索性資料分析 - 資料視覺化 - 多圖檢視 1. 將數據分組一次呈現 2. 把同一組資料相關的數據一次攤在面前
5. [Heatmap & Grid-plot]
探索性資料分析 - 資料視覺化 - 熱像圖 / 格狀圖 1. 熱圖：以直觀的方式檢視變數間的相關性 2. 格圖：繪製變數間的散佈圖及分布
5. [模型初體驗 Logistic Regression]
在我們開始使用任何複雜的模型之前，有一個最簡單的模型當作 baseline 是一個好習慣
## 資料科學特徵工程技術

22. [特徵工程簡介]
介紹機器學習完整步驟中，特徵工程的位置以及流程架構
22. [數值型特徵 - 去除偏態]
數值型特徵若分布明顯偏一邊，則需去除偏態以消除預測的偏差
22. [類別型特徵 - 基礎處理]
介紹類別型特徵最基礎的作法 : 標籤編碼與獨熱編碼
22. [類別型特徵 - 均值編碼]
類別型特徵最重要的編碼 : 均值編碼，將標籤以目標均值取代
22. [類別型特徵 - 其他進階處理]
類別型特徵的其他常見編碼 : 計數編碼對應出現頻率相關的特徵，雜湊編碼對應眾多類別而無法排序的特徵
22. [時間型特徵]
時間型特徵可抽取出多個子特徵，或周期化，或取出連續時段內的次數
22. [特徵組合 - 數值與數值組合]
特徵組合的基礎 : 以四則運算的各種方式，組合成更具預測力的特徵
22. [特徵組合 - 類別與數值組合]
類別型對數值型特徵可以做群聚編碼，與目標均值編碼類似，但用途不同
22. [特徵選擇]
介紹常見的幾種特徵篩選方式
22. [特徵評估]
介紹並比較兩種重要的特徵評估方式，協助檢測特徵的重要性
22. [分類型特徵優化 - 葉編碼]
葉編碼 : 適用於分類問題的樹狀預估模型改良

## 機器學習基礎模型建立
33. [機器如何學習?]
了解機器學習的定義，過擬合 (Overfit) 是甚麼，該如何解決
33. [訓練/測試集切分的概念]
為何要做訓練/測試集切分？有什麼切分的方法？
33. [regression vs. classification]
回歸問題與分類問題的區別？如何定義專案的目標
33. [評估指標選定/evaluation metrics]
專案該如何選擇評估指標？常用指標有哪些？
33. [regression model 介紹 - 線性迴歸/羅吉斯回歸]
線性迴歸/羅吉斯回歸模型的理論基礎與使用時的注意事項
33. [regression model 程式碼撰寫]
如何使用 Scikit-learn 撰寫線性迴歸/羅吉斯回歸模型的程式碼
33. [regression model 介紹 - LASSO 回歸/ Ridge 回歸]
LASSO 回歸/ Ridge 回歸的理論基礎與與使用時的注意事項

33. [regression model 程式碼撰寫]
使用 Scikit-learn 撰寫 LASSO 回歸/ Ridge 回歸模型的程式碼
33. [tree based model - 決策樹 (Decision Tree) 模型介紹]
決策樹 (Decision Tree) 模型的理論基礎與使用時的注意事項
33. [tree based model - 決策樹程式碼撰寫]
使用 Scikit-learn 撰寫決策樹 (Decision Tree) 模型的程式碼
33. [tree based model - 隨機森林 (Random Forest) 介紹]
隨機森林 (Random Forest)模型的理論基礎與使用時的注意事項
33. [tree based model - 隨機森林程式碼撰寫]
使用 Scikit-learn 撰寫隨機森林 (Random Forest) 模型的程式碼
33. [tree based model - 梯度提升機 (Gradient Boosting Machine) 介紹]
梯度提升機 (Gradient Boosting Machine) 模型的理論基礎與使用時的注意事項
33. [tree based model - 梯度提升機程式碼撰寫]
使用 Scikit-learn 撰寫梯度提升機 (Gradient Boosting Machine) 模型的程式碼

## 機器學習調整參數
47. [超參數調整與優化]
什麼是超參數 (Hyper-paramter) ? 如何正確的調整超參數？常用的調參方法為何？
47. [Kaggle 競賽平台介紹]
介紹全球最大的資料科學競賽網站。如何參加競賽？
47. [集成方法 : 混合泛化(Blending)]
什麼是集成? 集成方法有哪些? Blending 的寫作方法與效果為何?
47. [集成方法 : 堆疊泛化(Stacking)]

51-53 [Kaggle 第一次期中考]

## 非監督式機器學習
54. [clustering 1 非監督式機器學習簡介]
非監督式學習簡介、應用場景
54. [clustering 2 聚類算法]
K-means
54. [K-mean 觀察 : 使用輪廓分析]
非監督模型要以特殊評估方法(而非評估函數)來衡量, 今日介紹大家了解並使用其中一種方法 : 輪廓分析
54. [clustering 3 階層分群算法]
hierarchical clustering
54. [階層分群法 觀察 : 使用 2D 樣版資料集]
非監督評估方法 : 2D樣版資料集是什麼? 如何生成與使用?
54. [dimension reduction 1 降維方法-主成份分析]
PCA
54. [PCA 觀察 : 使用手寫辨識資料集]
以較複雜的範例 : sklearn版手寫辨識資料集, 展示PCA的降維與資料解釋能力
54. [dimension reduction 2 降維方法-T-SNE]
TSNE
54. [t-sne 觀察 : 分群與流形還原]
什麼是流形還原? 除了 t-sne 之外還有那些常見的流形還原方法?

## 深度學習理論與實作
63. [神經網路介紹](
63. [深度學習體驗 : 模型調整與學習曲線]
介紹體驗平台 TensorFlow PlayGround，並初步了解模型的調整
63. [深度學習體驗 : 啟動函數與正規化]
在 TF PlayGround 上，體驗進階版的深度學習參數調整

##  初探深度學習使用Keras
66. [Keras 安裝與介紹]
66. [Keras Dataset]
66. [Keras Sequential API]
66. [Keras Module API]
66. [Multi-layer Perception多層感知]
MLP簡介
66. [損失函數]
66. [啟動函數]
66. [梯度下降Gradient Descent]
66. [Gradient Descent 數學原理]
介紹梯度下降的基礎數學原理
66. [BackPropagation]
反向式傳播簡介
66. [優化器optimizers]
66. [訓練神經網路的細節與技巧 - Validation and overfit]
檢視並了解 overfit 現象
66. [訓練神經網路前的注意事項]
資料是否經過妥善的處理？運算資源為何？超參數的設置是否正確？
66. [訓練神經網路的細節與技巧 - Learning rate effect]
比較不同 Learning rate 對訓練過程及結果的差異
66. [[練習 Day] 優化器與學習率的組合與比較]
66. [訓練神經網路的細節與技巧 - Regularization]
66. [訓練神經網路的細節與技巧 - Dropout]
66. [訓練神經網路的細節與技巧 - Batch normalization]
因應 overfit 的方法概述 - 批次正規化 (Batch Normalization)
66. [[練習 Day] 正規化/機移除/批次標準化的 組合與比較]
練習時間：Hyper-parameters 大雜燴
66. [訓練神經網路的細節與技巧 - 使用 callbacks 函數做 earlystop]
因應 overfit 的方法概述 - 悔不當初的煞車機制 (EarlyStopping)
66. [訓練神經網路的細節與技巧 - 使用 callbacks 函數儲存 model]
使用 Keras 內建的 callback 函數儲存訓練完的模型
66. [訓練神經網路的細節與技巧 - 使用 callbacks 函數做 reduce learning rate]
使用 Keras 內建的 callback 函數做學習率遞減
66. [訓練神經網路的細節與技巧 - 撰寫自己的 callbacks 函數]
66. [訓練神經網路的細節與技巧 - 撰寫自己的 Loss function]
66. [使用傳統電腦視覺與機器學習進行影像辨識]
了解在神經網路發展前，如何使用傳統機器學習演算法處理影像辨識
66. [[練習 Day] 使用傳統電腦視覺與機器學習進行影像辨識]
應用傳統電腦視覺方法＋機器學習進行 CIFAR-10 分類

## 深度學習應用卷積神經網路
92. [卷積神經網路 (Convolution Neural Network, CNN) 簡介]
了解CNN的重要性, 以及CNN的組成結構
92. [卷積神經網路架構細節]
為什麼比DNN更適合處理影像問題, 以及Keras上如何實作CNN
92. [卷積神經網路 - 卷積(Convolution)層與參數調整]
卷積層原理與參數說明
92. [卷積神經網路 - 池化(Pooling)層與參數調整]
介紹 Keras 中常用的 CNN layers
92. [Keras 中的 CNN layers]
92. [使用 CNN 完成 CIFAR-10 資料集]
透過 CNN 訓練 CIFAR-10 並比較其與 DNN 的差異
92. [訓練卷積神經網路的細節與技巧 - 處理大量數據]
資料無法放進記憶體該如何解決？如何使用 Python 的生成器 generator?
92. [訓練卷積神經網路的細節與技巧 - 處理小量數據]
資料太少準確率不高怎麼辦？如何使用資料增強提升準確率？
92. [訓練卷積神經網路的細節與技巧 - 轉移學習 (Transfer learning)]
何謂轉移學習 Transfer learning？該如何使用？

## Kaggle 期末考
101. [透過 Kaggle 影像辨識測驗, 綜合應用深度學習的課程內容, 並體驗遷移學習的威力]




