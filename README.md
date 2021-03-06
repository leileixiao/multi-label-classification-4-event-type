### 多标签文本分类

- 数据来源：[2020语言与智能技术竞赛：事件抽取任务](https://aistudio.baidu.com/aistudio/competition/detail/32?isFromCcf=true)

- 模型结构：采用ALBERT对文本进行特征提取，最大文本长度为200，采用的深度学习模型如下：

![](https://img-blog.csdnimg.cn/20200409220551541.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2pjbGlhbjkx,size_16,color_FFFFFF,t_70#pic_center)

- 模型训练效果如下图：

- 在新数据上进行预测，结果如下：

>预测语句: 北京时间6月7日，中国男足在广州天河体育场与菲律宾进行了一场热身赛，最终国足以2-0击败了对手，里皮也赢得了再度执教国足后的首场比赛胜利！
预测事件类型: 竞赛行为-胜负

>预测语句: 巴西亚马孙雨林大火持续多日，引发全球关注。
预测事件类型: 灾害/意外-起火

>预测语句: 19里加大师赛资格赛前两天战报 中国选手8人晋级6人遭淘汰2人弃赛
预测事件类型: 竞赛行为-晋级

>预测语句: 日本电车卡车相撞，车头部分脱轨并倾斜，现场起火浓烟滚滚
预测事件类型: 灾害/意外-车祸

>预测语句: 截止到11日13：30 ，因台风致浙江32人死亡，16人失联。具体如下：永嘉县岩坦镇山早村23死9失联，乐清6死，临安区岛石镇银坑村3死4失联，临海市东塍镇王加山村3失联。
预测事件类型: 人生-失联|人生-死亡

> 预测语句: 定位B端应用，BeBop发布Quest专属版柔性VR手套
预测事件类型: 产品行为-发布

> 预测语句: 8月17日。凌晨3点20分左右，济南消防支队领秀城中队接到指挥中心调度命令，济南市中区中海环宇城往南方向发生车祸，有人员被困。
预测事件类型: 灾害/意外-车祸

> 预测语句: 注意！济南可能有雷电事故｜英才学院14.9亿被收购｜八里桥蔬菜市场今日拆除，未来将建新的商业综合体
预测事件类型: 财经/交易-出售/收购

> 预测语句: 昨天18：30，陕西宁强县胡家坝镇向家沟村三组发生山体坍塌，5人被埋。当晚，3人被救出，其中1人在医院抢救无效死亡，2人在送医途中死亡。今天凌晨，另外2人被发现，已无生命迹象。
预测事件类型: 人生-死亡|灾害/意外-坍/垮塌