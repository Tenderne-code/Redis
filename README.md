# Redis
大数据Redis实习

本次实习目标是考虑基于Redis实现网站的“点赞”和“关注” 功能。

首先在Redis中选择合适的数据结构，保存如下信息：

1.保存某个用户是否点赞过某个帖子。  
2.保存一个帖子的点赞总数。  
3.保存每个用户的关注和被关注集合。  
4.保存每个用户的被关注次数。  

然后实现如下查询操作：

1.用户浏览一个帖子时，返回帖子的点赞数。  
2.用户浏览一个帖子时，返回该用户以前是否点赞过这个帖子。  
3.给出点赞数排名前十的帖子。  
4.给定一个用户，给出和他互相关注的其他用户。  
5.给定一个用户，给出和他共同关注的好友数排在前3的其他用户。
