<img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/Maching_Reading_Robot_Auto-Text_to_Knowledge.jpg" alt="machine learning" width="500px">

(img from [wikimedia](https://upload.wikimedia.org/wikipedia/commons/6/6a/Maching_Reading_Robot_Auto-Text_to_Knowledge.jpg))

## 前言

如果說前幾年最熱門的 buzzword 是 "雲端"，那麼這兩年最熱門的關鍵字應該就是 "Big Data" 了！看看這個全民 Big Data 時代，每個跟網路相關的產業大大好像不扯點 Data Mining、Machine Learning 就顯得你落伍了，連台灣的 Wired 雜誌都出了一本[特刊](http://www.books.com.tw/exep/prod/magazine/mag_retail.php?item=R030044308)來告訴大家 Big Data 到底是多麼重要！

慚愧的是身為資訊本科系的小弟，在念書的時候對這方面修業不足，導致在這個全民 Big Data 時代沒辦法跟上潮流扯上兩句。好在 [Coursera](https://www.coursera.org/) 補足了我這方面的遺憾！Stanford 的教授 Andrew Ng 在 Coursera 上面開了 Machine Learning 課程，讓我有機會初探 Machine Learning，希望有朝一日可以跟著眾多專家們深入 Big Data 的世界！

這一系列基本上會是我的 Machine Learning 筆記，如果有什麼可以指教的地方歡迎打臉！

## 簡介

平常在我們的生活中處處充滿了 Machine Learning 的應用，下面隨手舉幾個例子：

* Gmail 垃圾郵件的判定
* iPhoto 幫你自動整理照片
* Amazon 的推薦商品
* Google 的無人駕駛汽車
* 手寫辨識系統

可以看到關於 Machine Learning 的應用是無所不在。Machine Learning 人人會說，那麼到底什麼是 Machine Learning 呢？[Tom Mitchell](http://en.wikipedia.org/wiki/Tom_M._Mitchell) 對於 Machine Learning 這個 Term 提供了一個正規的定義：

> A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E.

以 Gmail 判定垃圾郵件來說，experience E 是使用者按下 "判定為垃圾信" 這個動作，task T 是 gmail 把郵件判定是否為垃圾信，performance measure P 則是 gmail 正確判定垃圾信的機率。

## Machine Learning 的分類

Machine Learning 的分類基本上可以分為 Supervised Learning 以及 Unupervised Learning 兩種，這兩種的分類分別說明如下：

### Supervised Learning

Supervised Learning 有人翻作「監督式學習」。簡單的說，如果在你的 Machine Learning 問題當中會給予「正確答案」的都可以算是 Supervised Learning。舉幾個例子：

* 明天的氣溫幾度
* 明天某某股票會不會漲
* 某封 E-mail 是不是垃圾郵件

而在 Supervised Learning 當中，又可以再分出兩類，分別為 Regression 以及 Classification。Regression 是拿來預測一個 "continuous value"，Classification 則是如字面上所見，是拿來做分類用的。一時之間搞不懂嗎？像是上面的例子來說，「明天的氣溫幾度」就是屬於 Regression，而「明天某某股票會不會漲」還有「某封 E-mail 是不是垃圾郵件」則是屬於 Classification。


### Unupervised Learning

相對於 Supervised Learning，Unupervised Learning 就是沒有給予「正確答案」的 Machine Learning 問題。舉例來說，我們會發現 Google News 會自動幫我們把類似的新聞 group 在一起，這種就是透過 Unupervised Learning 來完成。

關於 Machine Learning 的基本介紹就到此為止，算是暖身結束，接下來的文章我們會從 Regression 開始做更進一步的介紹。