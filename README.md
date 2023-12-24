# 自动控制实践A
**new: 直流电机、PWM、步进电机笔记更新，直流电机动特性与选择的答案更新**

文档编写者：[Oliver Wu](https://github.com/OliverWu515)（撰写有关21级部分）

![Static Badge](https://img.shields.io/badge/%E8%80%83%E8%AF%95%E8%AF%BE-red)![Static Badge](https://img.shields.io/badge/%E5%AD%A6%E5%88%86-3-moccasin)

![Static Badge](https://img.shields.io/badge/%E6%88%90%E7%BB%A9%E6%9E%84%E6%88%90（21级）-gold)![Static Badge](https://img.shields.io/badge/%E4%BD%9C%E4%B8%9A-10%25-wheat) ![Static Badge](https://img.shields.io/badge/实验-25%25-wheat)![Static Badge](https://img.shields.io/badge/%E6%9C%9F%E6%9C%AB%E8%80%83%E8%AF%95-65%25-wheat)

![Static Badge](https://img.shields.io/badge/总学时48-wheat) ![Static Badge](https://img.shields.io/badge/讲课学时-40-wheat) ![Static Badge](https://img.shields.io/badge/实验-2学时*4-wheat)

该课程有配套的课程设计（[(必修)自动控制实践A课程设计](https://hoa.moe/docs/junior-autumn/auto3016/)），独立设课，1学分、40学时。

## 教材、参考书、学时安排

教材：梅晓榕主编，自动控制元件及线路（第五版），科学出版社。

参考书及网课：

本课程涵盖三部分内容：电机驱动与拖动；传感与测量元件；简单的电力电子技术（PWM）。以第一块内容为最重。

电机学：

- （哈尔滨理工大学）戈宝军,梁艳萍,温嘉斌，电机学（第三版），中国电力出版社。

  配套网课：[电机学（哈尔滨理工大学）bilibili](https://www.bilibili.com/video/BV1cx411Z76w/?spm_id_from=333.337.search-card.all.click)

- （哈尔滨理工大学）汤蕴璆编著，电机学（第5版），机械工业出版社。
- （大连理工大学）孙建忠、刘凤春等编，电机与拖动（第4版），机械工业出版社。

上面的是传统电机学教材，可以看里面的直流电机、变压器、异步电机和同步电机。关于伺服电机和步进电机，可以参考以下书目：

- [日]坂本正文著，王自强译，步进电机应用技术，科学出版社2010年版。（翻译有些错误，凑合着看）
- （一些奇怪的论坛里的pdf，找到后放上来）

关于电力电子技术，本门课要求很低。如果大家想拓展（学电气的专业课[bushi]），可以参考的书目有：（请大家量力而行，学有余力再去看拓展提高的内容！）

- （西安交通大学）王兆安等，电力电子技术（第5版），机械工业出版社。
- Erickson，Fundamental of power electronics（3rd ed.)，Springer。
- [傅旻帆-上海科技大学](https://space.bilibili.com/519909115)
- [西瓜粥西瓜粥个人主页-哔哩哔哩视频 (bilibili.com)](https://space.bilibili.com/287344644?spm_id_from=333.337.search-card.all.click)

<h4>学时安排表（21级）</h4>   <!--标题-->
<table border="1" cellspacing="10">
<tr>
  <th align="center">授课教师</th>
  <th align="center">授课内容</th>
  <th align="center">学时安排</th>
  <th align="center">建议</th>
</tr>
<tr>
  <td rowspan="10" align="center">隆志力</td>
  <td>绪论</td>
  <td>2</td>
  <td>了解即可。</td>
</tr>
<tr>
  <td>磁路基础</td>
  <td>2</td>
  <td>重要！磁量的关系、磁路定律要很清楚，变压器和交流电机中经常用到。</td>
</tr>
<tr>
  <td>直流电机的结构和工作原理</td>
  <td>2</td>
  <td>结构要认识（不用细到绕法这些，只要知道每个部件名称和属于定子还是转子）、工作原理比较好理解，重点是换向器和电刷，简单描述即可。</td>
</tr>
<tr>
  <td>直流电机的磁场、电枢反应与换向</td>
  <td>2</td>
  <td>理解，重在知道结果，不是重点。</td>
</tr>
<tr>
  <td>直流电机基本方程、机械特性、调节特性</td>
  <td>2</td>
  <td>很重要，需要记忆几乎每个公式！数形结合是很重要的方法！结合图形分析事半功倍！</td>
</tr>
<tr>
  <td>直流电机的调速运行</td>
  <td>2</td>
  <td>很重要，需要结合图形记忆调速方式的特点！</td>
</tr>
<tr>
  <td>直流电机的四象限运行（工作状态）</td>
  <td>2</td>
  <td>很重要，需要结合图形记忆每个象限、曲线的不同阶段对应的工作状态！</td>
</tr>
<tr>
  <td>电力电子技术概述</td>
  <td>2</td>
  <td>理解，主要关注器件分类、工作原理、适用范围。</td>
</tr>
<tr>
  <td>PWM</td>
  <td>2</td>
  <td>很重要，需要理解一个周期PWM元件上的电流流向、导通关断与否以及元件的作用。</td>
</tr>
<tr>
  <td>变压器</td>
  <td>2</td>
  <td>很重要，学时很少，要记忆的东西却很多。重点在负载运行和空载运行的基本方程和T形等效电路。笔记文件夹里的笔记整理得很清楚。</td>
</tr>
<tr>
  <td rowspan="10" align="center">李建刚</td>
  <td>课程概述</td>
  <td>1</td>
  <td>了解即可。</td>
</tr>
<tr>
  <td>步进电机的结构与工作原理</td>
  <td>1</td>
  <td>重要。理解“错齿是使步进电机运动的根本原因”。关于齿数的计算，反应式和混合式其实是有不同的。但是一般按照反应式的公式计算。</td>
</tr>
<tr>
  <td>步进电机的静态特性、动态特性与驱动</td>
  <td>3</td>
  <td>重要。静态特性主要是矩角特性，动态特性主要是从矩角特性出发用合成法来分析启动特性（图解特别重要），以及矩频特性。驱动以细分驱动为主。</td>
</tr>
<tr>
  <td>交流电机概述</td>
  <td>2</td>
  <td>这节课让大家对异步电机和同步电机的结构和工作原理有基本的认识。但是详细的分析还需后面仔细学习。</td>
</tr>
<tr>
  <td>无刷直流电机与交流伺服电机</td>
  <td>5</td>
  <td>讲得最细致的部分，但其实原理相对比较简单，重点理解六步换向和Clark-Park/d-q变换，理解如何将伺服电机的驱动变得像有刷直流那样简单。</td>
</tr>
<tr>
  <td>测量元件、旋转变压器、感应同步器、编码器、光栅</td>
  <td>3</td>
  <td>由于学时剩余很少，讲课速度开始进入倍速模式。大家从这里开始只要尽量听明白就行，笔记课后再做。</td>
</tr>
<tr>
  <td>交流绕组的基本原理，三相异步电机的原理及结构</td>
  <td>2</td>
  <td>是重点，也是难点！！但是学时比较少。旋转磁场理解起来比较困难。详见文件中的异步电机笔记。</td>
</tr>
<tr>
  <td>三相异步电机的等效电路及运行分析，机械特性和调速运行</td>
  <td>约2.5</td>
  <td>是重点，也是难点！！但是你没看错，2学时结束了。等效的流程：电路模型-频率归算-绕组归算。<b>异步电机可以看成“会动的变压器”！</b> 详见文件中的异步电机笔记。</td>
</tr>
<tr>
  <td>单相异步电机的等效电路及运行分析</td>
  <td>约0.5</td>
  <td>需要理解，有小题。</td>
</tr>
<tr>
  <td>小功率同步电机</td>
  <td>0</td>
<td>没时间了，几乎没讲，考试不涉及。</td>
</tr>
</table>


<!--在表格td中，有两个属性控制居中显示
	align——表示左右居中——left，center，right
	valign——控制上下居中——left，center，right
	width——控制单元格宽度，单位像素
	cellspacing——单元格之间的间隔，单位像素
-->

## 授课教师

（21级情况）

- 教师1：隆志力
  - 授课风格：稍显含糊，车轱辘话较多；课件内容较丰富，有别学校课件截下来的内容，不过画质较差，而且比较乱，不适合直接做笔记。
  - 听课建议：基本忠于ppt（不会自由发挥），由于车轱辘话较多，知识讲解得比较抽象，上课不易听懂，课后要多花时间。
- 教师2：李建刚
  - 授课风格：语速很快（因为学时有限、内容又多，到后面会快到起飞）、逻辑较清晰（到后面由于速度快变得不清晰）、答疑有耐心、板书不好看、语气词较多（到后程由于速度极快，
    语气词的数量甚至会超过传递信息的词）、课件较美观（但是由于摘选自外校课件，有时会出现符号的冲突或逻辑不连贯）。
  - 听课建议：因为上课节奏较快，上课只求听懂大概即可，但课后务必整理笔记！！！

## 关于考试

- 考试难度：
