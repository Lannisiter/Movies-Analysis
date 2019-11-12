# Movies_Analysis
### 电影信息爬取

#### 电影名称

 &ensp;  &ensp; 首先在[1905](http://www.1905.com/mdb/film)上随机爬取各个年份(1991-2017)的电影名称，爬取后按年份存放电影。

#### 电影票房

 &ensp;  &ensp; 在[CBO](http://www.cbooo.cn/)上爬取对应电影的票房，爬取后记录每部电影对应的票房。

#### 电影评价(星数)

 &ensp;  &ensp; 在[豆瓣](https://www.douban.com/)上爬取每部电影的评价打分，爬取后记录每部电影的评价。

#### 电影详细信息

 &ensp;  &ensp; 同意在[豆瓣](https://www.douban.com/)上爬取电影的详细信息(评分人数、想看人数、看过人数、年代、短评数量、影评数量、影片类型)，爬取后把之前爬取的数据全部整合存放在同一个文件中。

### 数据分析

 &ensp;  &ensp; 根据上面爬取到的数据使用8种回归方法来分别进行电影票房的预测，并作出每种方法预测结果和实际结果的可视化界面，最终选取效果最好的4种。