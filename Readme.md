# 2019-Kaggle-Elo-Merchant-Category-Recommendation

Public LB：  

![image](https://raw.githubusercontent.com/tools-only/2019-Kaggle-Elo-Merchant-Category-Recommendation/master/Public%20LB.png)

Private LB：  

![image](https://raw.githubusercontent.com/tools-only/2019-Kaggle-Elo-Merchant-Category-Recommendation/master/Private%20LB.png)

没有花时间做题，前两天过了一遍社区里kaggler分享的Kernel，全当是熟悉DM的过程了。    

另外这次的比赛最终的Shake up非常大，由于数据中存在离群点，很多队伍为了提升自己在Public LB的排名，利用覆盖离群点来提升模型准确率，而比赛结束后的确如一些kaggler预测的那样，Public LB的top名次掉得很夸张。  

我的Kernel主要参考了：  

[Statistical Analysis for Elo ](https://www.kaggle.com/mjbahmani/statistical-analysis-for-elo) ： 包括数据处理、分析，基础的特征工程，模型训练等，我当时看完原作者的kernel之后就打算以此作为base model，作为熟悉kaggle比赛的一个重要参考。  

[Simple LightGBM without blending](https://www.kaggle.com/mfjwr1/simple-lightgbm-without-blending) ：最终提交kernel的参考，我在notebook中有详细的特征工程介绍（部分特征构建我并没有直观感受，可能是因为完整的特征工程需要不断尝试，而我并没有经历这一过程，后面再完整地做一次比赛来提升吧）。模型部分利用LightGBM进行训练，没有进行融合。社区里有人分享自己的观点，认为坚持single model的本地CV要比融合后的效果好，证实待补充。  



**后续：**  

后面我会在社区里选一些比较有意思的trick，补充进来。  

[如何选择合适的特征？](https://www.kaggle.com/c/elo-merchant-category-recommendation/discussion/82052)

[为什么要信赖你的local CV？](https://www.kaggle.com/tunguz/elo-adversarial-validation) ：非常有意思的trick



