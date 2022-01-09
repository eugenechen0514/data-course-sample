
上一份作業的連結: [A6: Collaborative filtering 推薦算法 實作作業](https://lighthouse.alphacamp.co/courses/125/assignments/3731/submissions/179857?assignment_id=3731&batch_id=269&choice_cohort=all_cohort&course_id=125&from=other-submission&question_id=6433)

### 在這次的實作結果比較中，你發現了什麼？
我發現在 cf 中，user-item 的連結太弱的話，幾乎做不出來。 這次來話有9成以上都是沒辨法做出推薦的，看來 rule-base 對於資料不夠的情況下真的很重要。


### 過程中遇到什麼挑戰？有嘗試如何克服？
快要不知道要分析什麼東西了，很容易不知道目標或是算出的結果都不好。

目前是從結果中，慢慢找尋可能的因子，在做出猜想並分折。

舉個列子，我去從推薦答案（測試資料）中找尋因子，想要增加推薦命中，是要加入 rank 還是 price 的因子？　之後，才去做 EDA，反而不是從 EDA　發現東西。
又或是找一些可能的因素，組合看看，算算結果才能做出結論。

我不確定這是不是正常的做法？

### 從個人學習的角度，從這個專案最大的學習是什麼？
好像越來越了解 pandas 的 dataframe/series 物件， 這次也學到 quantile 的用法，用來分析因子是不是重要的。

上次看到有同學用 plt.hist() 畫圖，這東西太好用了，之前我還自己算，長知識了。

### 如果你有更多時間，你會如何選擇你的推薦系統算法？或是如何後續優化他？為什麼？
大部分的測試資料都沒有受到推薦，應該要混合 rule-base。另外，我發現低 price 的商品購買次數很多，因該也適合做為 rule-base 考慮的因子。   

