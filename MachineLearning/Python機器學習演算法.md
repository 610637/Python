
>* https://detail.tmall.com/item.htm?id=564938366996&ns=1&abbucket=19
>* https://github.com/zhaozhiyong19890102/Python-Machine-Learning-Algorithm


0緒論1

0.1機器學習基礎1

0.1.1機器學習的概念1

0.1.2機器學習演算法的分類2

0.2監督學習3

0.2.1監督學習3

0.2.2監督學習的流程3

0.2.3監督學習演算法4

0.3無監督學習4

0.3.1無監督學習4

0.3.2無監督學習的流程4

0.3.3無監督學習演算法5

0.4推薦系統和深度學習6

0.4.1推薦系統6

0.4.2深度學習6

0.5Python和機器學習演算法實踐6

參考文獻7



第一部分分類演算法

1Logistic Regression10

1.1Logistic Regression模型10

1.1.1線性可分VS線性不可分10

1.1.2Logistic Regression模型11

1.1.3損失函數13

1.2梯度下降法14

1.2.1梯度下降法的流程14

1.2.2凸優化與非凸優化15

1.2.3利用梯度下降法訓練Logistic Regression模型17

1.3梯度下降法的若干問題18

1.3.1選擇下降的方向18

1.3.2步長的選擇19

1.4Logistic Regression演算法實踐20

1.4.1利用訓練樣本訓練Logistic Regression模型20

1.4.2最終的訓練效果22

1.4.3對新資料進行預測23

參考文獻26

2Softmax Regression27

2.1多分類問題27

2.2Softmax Regression演算法模型28

2.2.1Softmax Regression模型28

2.2.2Softmax Regression演算法的代價函數28

2.3Softmax Regression演算法的求解29

2.4Softmax Regression與Logistic Regression的關係31

2.4.1Softmax Regression中的參數特點31

2.4.2由Softmax Regression到Logistic Regression31

2.5Softmax Regression演算法實踐32

2.5.1對Softmax Regression演算法的模型進行訓練33

2.5.2最終的模型34

2.5.3對新的資料的預測35

參考文獻39

3Factorization Machine40

3.1Logistic Regression演算法的不足40

3.2因數分解機FM的模型42

3.2.1因數分解機FM模型42

3.2.2因數分解機FM可以處理的問題43

3.2.3二分類因數分解機FM演算法的損失函數43

3.3FM演算法中交叉項的處理43

3.3.1交叉項係數43

3.3.2模型的求解44

3.4FM演算法的求解45

3.4.1隨機梯度下降（Stochastic Gradient Descent）45

3.4.2基於隨機梯度的方式求解45

3.4.3FM演算法流程46

3.5因數分解機FM演算法實踐49

3.5.1訓練FM模型50

3.5.2最終的訓練效果53

3.5.3對新的資料進行預測55

參考文獻57

4支持向量機58

4.1二分類問題58

4.1.1二分類的分隔超平面58

4.1.2感知機演算法59

4.1.3感知機演算法存在的問題61

4.2函數間隔和幾何間隔61

4.2.1函數間隔62

4.2.2幾何間隔62

4.3支持向量機63

4.3.1間隔最大化63

4.3.2支持向量和間隔邊界64

4.3.3線性支援向量機65

4.4支持向量機的訓練66

4.4.1學習的對偶演算法66

4.4.2由線性支援向量機到非線性支援向量機68

4.4.3序列最小最優化演算法SMO69

4.5支援向量機SVM演算法實踐74

4.5.1訓練SVM模型74

4.5.2利用訓練樣本訓練SVM模型81

4.5.3利用訓練好的SVM模型對新資料進行預測85

參考文獻88

5隨機森林89

5.1決策樹分類器89

5.1.1決策樹的基本概念89

5.1.2選擇最佳劃分的標準91

5.1.3停止劃分的標準94

5.2CART分類樹演算法95

5.2.1CART分類樹演算法的基本原理95

5.2.2CART分類樹的構建95

5.2.3利用構建好的分類樹進行預測98

5.3集成學習（Ensemble Learning）99

5.3.1集成學習的思想99

5.3.2集成學習中的典型方法99

5.4隨機森林（Random Forests）101

5.4.1隨機森林演算法模型101

5.4.2隨機森林演算法流程102

5.5隨機森林RF演算法實踐104

5.5.1訓練隨機森林模型105

5.5.2最終的訓練結果109

5.5.3對新資料的預測110

參考文獻113

6BP神經網路114

6.1神經元概述114

6.1.1神經元的基本結構114

6.1.2啟動函數115

6.2神經網路模型116

6.2.1神經網路的結構116

6.2.2神經網路中的參數說明117

6.2.3神經網路的計算117

6.3神經網路中參數的求解118

6.3.1神經網路損失函數118

6.3.2損失函數的求解119

6.3.3BP神經網路的學習過程120

6.4BP神經網路中參數的設置126

6.4.1非線性變換126

6.4.2權重向量的初始化126

6.4.3學習率127

6.4.4隱含層節點的個數127

6.5BP神經網路演算法實踐127

6.5.1訓練BP神經網路模型128

6.5.2最終的訓練效果132

6.5.3對新資料的預測133

參考文獻136



第二部分回歸演算法

7線性回歸138

7.1基本線性回歸138

7.1.1線性回歸的模型138

7.1.2線性回歸模型的損失函數139

7.2線性回歸的最小二乘解法140

7.2.1線性回歸的最小二乘解法140

7.2.2廣義逆的概念141

7.3牛頓法141

7.3.1基本牛頓法的原理141

7.3.2基本牛頓法的流程142

7.3.3全域牛頓法142

7.3.4Armijo搜索144

7.3.5利用全域牛頓法求解線性回歸模型145

7.4利用線性回歸進行預測146

7.4.1訓練線性回歸模型147

7.4.2最終的訓練結果149

7.4.3對新資料的預測150

7.5局部加權線性回歸152

7.5.1 局部加權線性回歸模型152

7.5.2局部加權線性回歸的最終結果153

參考文獻154

8嶺回歸和Lasso回歸155

8.1線性回歸存在的問題155

8.2嶺回歸模型156

8.2.1嶺回歸模型156

8.2.2嶺回歸模型的求解156

8.3Lasso回歸模型157

8.4擬牛頓法158

8.4.1擬牛頓法158

8.4.2BFGS校正公式的推導158

8.4.3BFGS校正的演算法流程159

8.5L-BFGS求解嶺回歸模型162

8.5.1BGFS演算法存在的問題162

8.5.2L-BFGS演算法思路162

8.6嶺回歸對資料的預測165

8.6.1訓練嶺回歸模型166

8.6.2最終的訓練結果168

8.6.3利用嶺回歸模型預測新的資料168

參考文獻171

9CART樹回歸172

9.1複雜的回歸問題172

9.1.1線性回歸模型172

9.1.2局部加權線性回歸173

9.1.3CART演算法174

9.2CART回歸樹生成175

9.2.1CART回歸樹的劃分175

9.2.2CART回歸樹的構建177

9.3CART回歸樹剪枝179

9.3.1前剪枝179

9.3.2後剪枝180

9.4CART回歸樹對資料預測180

9.4.1利用訓練資料訓練CART回歸樹模型180

9.4.2最終的訓練結果182

9.4.3利用訓練好的CART回歸樹模型對新的資料預測185

參考文獻187



第三部分聚類演算法

10K-Means190

10.1相似性的度量190

10.1.1閔可夫斯基距離191

10.1.2曼哈頓距離191

10.1.3歐氏距離191

10.2K-Means演算法原理192

10.2.1K-Means演算法的基本原理192

10.2.2K-Means演算法步驟193

10.2.3K-Means演算法與矩陣分解193

10.3K-Means演算法實踐195

10.3.1導入數據196

10.3.2初始化聚類中心197

10.3.3聚類過程198

10.3.4最終的聚類結果199

10.4K-Means++演算法200

10.4.1K-Means演算法存在的問題200

10.4.2K-Means++演算法的基本思路202

10.4.3K-Means++演算法的過程和最終效果204

參考文獻205

11Mean Shift206

11.1Mean Shift向量206

11.2核函數207

11.3Mean Shift演算法原理209

11.3.1引入核函數的Mean Shift向量209

11.3.2Mean Shift演算法的基本原理210

11.4Mean Shift演算法的解釋212

11.4.1概率密度梯度212

11.4.2Mean Shift向量的修正213

11.4.3Mean Shift演算法流程213

11.5Mean Shift演算法實踐217

11.5.1Mean Shift的主過程218

11.5.2Mean Shift的最終聚類結果219

參考文獻221

12DBSCAN222

12.1基於密度的聚類222

12.1.1基於距離的聚類演算法存在的問題222

12.1.2基於密度的聚類演算法225

12.2DBSCAN演算法原理225

12.2.1DBSCAN演算法的基本概念225

12.2.2DBSCAN演算法原理227

12.2.3DBSCAN演算法流程228

12.3DBSCAN演算法實踐231

12.3.1DBSCAN演算法的主要過程232

12.3.2Mean Shift的最終聚類結果234

參考文獻236

13Label Propagation237

13.1社區劃分237

13.1.1社區以及社區劃分237

13.1.2社區劃分的演算法238

13.1.3社區劃分的評價標準239

13.2Label Propagation演算法原理239

13.2.1Label Propagation演算法的基本原理239

13.2.2標籤傳播240

13.2.3反覆運算的終止條件242

13.3Label Propagation演算法過程244

13.4Label Propagation演算法實踐244

13.4.1導入數據245

13.4.2社區的劃分246

13.4.3最終的結果247

參考文獻248



第四部分推薦演算法

14協同過濾演算法250

14.1推薦系統的概述250

14.1.1推薦系統250

14.1.2推薦問題的描述251

14.1.3推薦的常用方法251

14.2基於協同過濾的推薦252

14.2.1協同過濾演算法概述252

14.2.2協同過濾演算法的分類252

14.3相似度的度量方法253

14.3.1歐氏距離254

14.3.2皮爾遜相關係數（Pearson Correlation）254

14.3.3余弦相似度254

14.4基於協同過濾的推薦演算法256

14.4.1基於使用者的協同過濾演算法256

14.4.2基於項的協同過濾演算法258

14.5利用協同過濾演算法進行推薦260

14.5.1導入使用者-商品資料260

14.5.2利用基於使用者的協同過濾演算法進行推薦261

14.5.3利用基於項的協同過濾演算法進行推薦262

參考文獻264

15基於矩陣分解的推薦演算法265

15.1矩陣分解265

15.2基於矩陣分解的推薦演算法266

15.2.1損失函數266

15.2.2損失函數的求解266

15.2.3加入正則項的損失函數即求解方法267

15.2.4預測269

15.3利用矩陣分解進行推薦270

15.3.1利用梯度下降對用戶商品矩陣分解和預測270

15.3.2最終的結果272

15.4非負矩陣分解273

15.4.1非負矩陣分解的形式化定義274

15.4.2損失函數274

15.4.3優化問題的求解274

15.5利用非負矩陣分解進行推薦277

15.5.1利用乘法規則進行分解和預測277

15.5.2最終的結果278

參考文獻279

16基於圖的推薦演算法280

16.1二部圖與推薦演算法280

16.1.1二部圖280

16.1.2由用戶商品矩陣到二部圖281

16.2PageRank演算法282

16.2.1PageRank演算法的概念282

16.2.2PageRank的兩個假設283

16.2.3PageRank的計算方法283

16.3PersonalRank演算法285

16.3.1PersonalRank演算法原理285

16.3.2PersonalRank演算法的流程286

16.4利用PersonalRank演算法進行推薦288

16.4.1利用PersonalRank演算法進行推薦288

16.4.2最終的結果291

參考文獻291



第五部分深度學習

17AutoEncoder294

17.1多層神經網路294

17.1.1三層神經網路模型294

17.1.2由三層神經網路到多層神經網路295

17.2AutoEncoder模型296

17.2.1AutoEncoder模型結構296

17.2.2AutoEncoder的損失函數297

17.3降噪自編碼器Denoising AutoEncoder298

17.3.1Denoising AutoEncoder原理298

17.3.2Denoising AutoEncoder實現299

17.4利用Denoising AutoEncoders構建深度網路302

17.4.1無監督的逐層訓練302

17.4.2有監督的微調303

17.5利用TensorFlow實現Stacked Denoising AutoEncoders306

17.5.1訓練Stacked Denoising AutoEncoders模型306

17.5.2訓練的過程307

參考文獻308

18卷積神經網路309

18.1傳統神經網路模型存在的問題309

18.2卷積神經網路311

18.2.1卷積神經網路中的核心概念311

18.2.2卷積神經網路模型312

18.3卷積神經網路的求解313

18.3.1卷積層（Convolution Layer）313

18.3.2下採樣層（Sub-Sampling Layer）316

18.3.3全連接層（Fully-Connected Layer）316

18.4利用TensorFlow實現CNN316

18.4.1CNN的實現316

18.4.2訓練CNN模型320

18.4.3訓練的過程321

參考文獻321



第六部分專案實踐

19微博精准推薦324

19.1精准推薦324

19.1.1精准推薦的專案背景324

19.1.2精准推薦的技術架構325

19.1.3離線資料採擷326

19.2基於用戶行為的挖掘327

19.2.1基於互動內容的興趣挖掘327

19.2.2基於與博主互動的興趣挖掘328

19.3基於相似用戶的挖掘329

19.3.1基於“@”人的相似用戶挖掘329

19.3.2基於社區的相似用戶挖掘329

19.3.3基於協同過濾的相似用戶挖掘331

19.4點擊率預估332

19.4.1點擊率預估的概念332

19.4.2點擊率預估的方法332

19.5各種資料技術的效果334

參考文獻335

附錄A336

附錄B341
