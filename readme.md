# 第一步任务

## Lexie part

1、比对预测数据和训练数据

2、整理总用户数和微博数

3、找出需要预测用户在训练数据中的历史数据

## Elaine part

1、对数据进行分析，找出无用用户（Done）

2、将无用用户整理成一个文档（Done）

3、处理有用用户的转赞评数据（均值、中位数等）(Done)

## Koko part

1、整合以上两项内容（整合了一部分）

2、制作一个预测模型

3、生成预测数据，上传到平台检测

### 12.7工作：

1、对数据进行初步分析，结果如下:

>训练数据由\t依次分隔为：用户id, 微博id, 时间, 转发数, 评论数, 赞数, 内容

>预测数据由\t依次分隔为：用户id, 微博id, 时间, 内容

>预测数据的微博总数是 178297， 且每一条都能够根据'\t'分割成有四个元素的数据
 
>训练数据的微博总数是 1229618，且每一条都能够根据'\t'分割成有七个元素的数据
 
>其中训练数据中转赞评都为零的用户数为35967用户，发了790423条微博。

2、 将所有用户预测的转赞评预测为零，并上传至平台。

**注意：**

***每人可以在这个文件下更新自己的进度，并将代码实时性上传，方便大家了解各自的进度。有问题可以在issue提问，或者我们直接群内交流。加油加油加油~***