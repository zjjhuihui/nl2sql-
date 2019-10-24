# nl2sql-
大赛官网地址：
大赛季军github地址：http://github.com/beader/tianchi_nl2sql
季军的ppt中TEXT类型的cond_val从Table中生成可能考虑是question中的文本可能不准，从数据库的表中选择肯定得到的where-value肯定是正确的，不需要修正。
real类型的cond_val从question中获取。
根据Model 1 选择的cond_col，枚举cond_op与cond_val，生成候选( cond_col,  cond_op,  cond_val ) 组合，在枚举的时候因为text类型的只能是=号，real类型的有> < =三种符号，数值型可组合出这三种。




大赛冠军方案github地址：top1 ppt，
地址1: https://github.com/nudtnlp/tianchi-nl2sql-top1，
地址2: https://github.com/xyzhang16/tianchi-nl2sql-top1

冠军参考资料：
https://tianchi.aliyun.com/competition/entrance/231716/introduction
https://github.com/salesforce/WikiSQL
