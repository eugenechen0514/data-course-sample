
上一份作業的連結: [A4: 實作「Content-based Filtering」的推薦系統](https://lighthouse.alphacamp.co/courses/125/assignments/3733/submissions/179858?assignment_id=3733&batch_id=269&choice_cohort=all_cohort&course_id=125&from=other-submission&question_id=6428)

### 你認為你有達到這個專案的目的嗎？為什麼？
本次作業的目地是學習從結構化和非結構化資料抽取出特徵向量，並使用 similarity_matrix 做出商品的分類，以分類做出推薦。
我這次針為結構化和非結構化都有試圖做做看，雖然看起來效果不好，但我覺得有達到目的。

### 過程中遇到什麼挑戰？有嘗試如何克服？
從教案的非結構化(title)試跑，就有發現 recall 是 0，但沒有特別注意。等到自己開始做非結構化(description)，也是做到 recall 是 0，就有點怕怕的。

但後來亂調整 k 值後發現，雖然都是 0，但還是有些微不同的地方， k 值的也是會影響到 recall 的變化。 

### 從個人學習的角度，從這個專案最大的學習是什麼？
圖解 k 值對 recall 的變化，學習 matplotlib 畫圖。

### 如果你有更多時間，你會如何優化這個專案？或是再做一次，你是否會想嘗試用不同方法？
我覺得結構化(rank, 最近一次的評論的新鮮度) 中的，”最近一次的評論的新鮮度” 做法來做分類的因子，有點不確定他是否合理，因該要做一些資料調查才是。
另外，我覺得商品價格應該也可以做為分類的因子。
