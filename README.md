# 翻牌小游戏
- 通过Java GUI实现的桌面小游戏
## 大致思路
1. 创建1个JFrame，2个JPanel，一个25个元素的JButton数组，一个开始按钮，2个ImageIcon  
2. 将JFrame分为2个区域，上面为按钮组成的5*5的图片矩阵，下面为开始按钮  
3. 在上面的JPanel做一个5*5的网格布局，使用for循环，循环写入按钮，图片和监听器  
4. 监听器监听按钮，switch对外围的一圈按钮进行处理，并给一个默认情况  
5. 多线程添加背景音乐，在JFrame的构造方法中启动BGM  

> 由于这个游戏我玩不通关，所以我加了一个作弊按钮（23333）
