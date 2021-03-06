# 数据库原理及应用 习题二 答案作者：陈九礼

*原文链接：[数据库原理及应用教程(第4版|微课版)陈志泊-第二章习题_陈九礼](https://blog.csdn.net/weixin_41640994/article/details/103636998)*

# 一、选择题

>  
 1、设有如下关系表： 


R

|A|B|C|
|--|--|--|
|1|1|2|
|2|2|3|

S

|A|B|C|
|--|--|--|
|3|1|3|

T

|A|B|C|
|--|--|--|
|1|1|2|
|2|2|3|
|3|1|3|

>  
 则下列操作中正确的是() 

 <mark>A）T = R∪S</mark>  B）T = R ∩ S C）T = R × S D）T = R / S



>  
 2、关系代数运算是以()为基础的运算 

 A）关系运算 B）谓词运算 <mark>C）集合运算</mark> D）代数运算



>  
 3、按条件f对关系R进行选取，其关系代数表达式为() 

 A）R⋈R B）R⋈<sub>f</sub>R <mark>C）σ<sub>f</sub>( R)</mark> D）π<sub>f</sub>( R)



>  
 4、关系数据库的概念模型是() 

 A）关系模型的集合  <mark>B）关系模式的集合</mark>  C）关系子模式的集合  D）存储模式的集合



>   5、关系数据库管理系统能实现的专门关系运算包括() 

 A）排序、索引、统计 <mark>B）选取、投影、连接</mark>  C）关联、更新、排序 D）显示、打印、制表



>  
 6、设有如下关系表： 


R

|A|B|C|
|--|--|--|
|a|b|c|
|b|a|f|
|c|b|d|

S

|A|B|C|
|--|--|--|
|b|a|f|
|d|a|d|

W

|A|B|C|
|--|--|--|
|a|b|c|
|c|b|d|

>  
 则下列操作中正确的是() 

 A）W = R ∩ S B）W = R∪ S <mark>C）W = R - S</mark> D）W = R × S



>  
 7、设有一个学生档案的关系数据库，关系模式是：S(SNo, SN, Sex, Age)，其中SNo、SN、Sex，Age分别为学生的学号、姓名、性别、年龄。则“从学生档案数据库中检索学生年龄大于20岁的学生的姓名”的关系代数式是() 

 A）σ<sub>sn</sub>(π<sub>Age&gt;20</sub>(S)) <mark>B）π<sub>SN</sub>(σ<sub>Age&gt;20</sub>(S))</mark>  C）π<sub>SN</sub>(π<sub>Age&gt;20</sub>(S)) D）σ<sub>sn</sub>(σ<sub>Age&gt;20</sub>(S))



>  
 8、一个关系只有一个() 

 A）超码 B）外码 C）候选码 <mark>D）主码</mark>



>  
 9、在关系模型中，以下有关码的描述正确的是() 

 A）可以由任意多个属性组成  B）至多由一个属性组成 <mark> C）由一个或多个属性组成，其值能唯一标识关系中的一个元组</mark>  D）以上都不对



>  
 10、同一个关系模型的任意两个元组值() 

 <mark>A）不能完全相同</mark> B）可以完全相同 C）必须完全相同 D）以上都不对



>  
 11、一个关系数据库文件中的各条记录() 

 A）前后顺序不能任意颠倒，一个要按照输入的顺序排列  <mark>B）前后顺序可以任意颠倒，不影响库中的数据关系</mark>  C）前后顺序可以任意颠倒，但排列顺序不同，统计处理的结果就可能不同  D）前后顺序不能任意颠倒，一定按照关键字字段值的顺序排列



>  
 12、关系模式的任意属性() 

 <mark>A）不可再分</mark> B）可再分 C）命名在关系模式中可以不唯一 D）以上都不对



>  
 13、设有关系R和S，关系代数表达式R - (R - S)，表达的是() 

 <mark>A）R ∩ S</mark> B）R ∪ S C）R - S D）R × S



>  
 14、关系运算中花费时间可能最长的是() 

 A）选取 B）投影 C）差运算 <mark>D）笛卡尔积</mark>



>  
 15、设有关系模式R和S，下列各关系代数表达式不正确的是() 

 A）R - S = R - (R ∩ S)  B）R = (R - S) ∪ (R ∩ S)  C）R ∩ S = S - (S - R)  <mark>D）R ∩ S = S - (R - S)</mark>



>  
 16、设两个关系R和S，分别含有15和10个元组，则在R∪S， R - S和R ∩ S中不可能出现的元组数据的情况是() 

 A）15、5、10  <mark>B）18、7、7</mark>  C）21、11、4  D）25、15、0



>  
 17、在关系模型中，一个候选码是() 

 A）必须由多个任意属性组成  B）至多由一个属性组成  <mark>C）可由一个属性或多个其值能唯一标识元组的属性组成</mark>  D）以上都不是



# 二、填空题

1、在关系运算中，查找满足一定条件的元组的运算称之为<mark>选择</mark>；

2、在关系代数中，从两个关系中找出相同元组的运算称之为<mark>交</mark>运算；

3、传统的集合“并、差、交”运算施加于两个关系时，这两个关系必须<mark>相容</mark>（或是同类关系）；

4、在关系代数运算中，基本的运算是<mark>并</mark>、<mark>差</mark>、<mark>笛卡尔积</mark>、<mark>选择</mark>、<mark>投影</mark>；

5、在关系代数运算中，传统的集合运算有<mark>并</mark>、<mark>差</mark>、<mark>交</mark>、<mark>笛卡尔积</mark>；

6、关系代数运算中，专门的关系运算有<mark>选择</mark> 、<mark>投影</mark> 、<mark>连接</mark>；

7、设有关系R，从关系R中选择条合条件f的元组，则关系代数表达式应是<mark>σ<sub>f</sub>( R)</mark>；

8、关系运算分为<mark>关系代数</mark>和<mark>关系演算</mark>；

9、当对两个关系R和S进行自然连接运算时，要求R和S含有一个或多个共同的<mark>属性</mark>；

10、在一个关系中，列必须是<mark>同质</mark>的，即每一列中的分量是同类型的数据，来自同一域；

11、如果关系R2的外部关系键X与R1的主关系键相符合，则外部关系键X的每个值必须在R1中主关系键的值中找到，或者为空，这是关系的<mark>参照完整性</mark>规则；

>  
 注：12的加粗字体代表了有下划线 


12、设有关系模式为：系(**系编号**，系名称，电话，办公地点)，则该关系模型的主关系键是<mark>系编号</mark>主属性是<mark>系名称</mark>、<mark>电话</mark>、<mark>办公地点</mark>；

13、关系演算分为<mark>元组主键</mark>演算和<mark>域关系</mark>演算；

14、实体完整性规则是对<mark>主键</mark>的约束，参照完整性规则是对<mark>外部关系键</mark>的约束；

15、等式R ⋈ S = R × S成立的条件是<mark>R和S没有公共属性</mark>；

16、在关系数据库中，把数据表示成二维表，每一个二维表称为<mark>关系</mark>；

# 三、简答题

>  
 1、关系模型的完整性规则有哪几类 

关系模型中，有三类完整性约束，即<mark>实体完整性</mark>、<mark>参照完整性</mark>和<mark>用户自定义的完整性</mark>。 其中，实体完整性和参照完整性是关系模型必须满足的完整性约束条件，被称作关系的两个不变性。任何关系数据库系统都应该支持这两类完整性。除此之外，不同的关系数据库系统由于应用环境的不同，往往还需要一些特殊的约束条件，这就是用户自定义完整性，用户自定义完整性体现了具体领域中的语义约束。



>  
 2、举例说明什么是实体完整性和参照完整性 

实体完整性是指主码的值不能为空或部分为空。例如，学生关系中的主码“学号”不能为空，选课关系中的主码“学号+课程号”不能部分为空，即“学号”和“课程号”两个属性都不能为空。 参照完整性是指如果关系R2的外码X与关系R1的主码相符，则X的每个值或者等于R1中主码的某一个值或者取空值。例如，学生关系S的“系别”属性与系别关系D的主码“系别”相对应，因此，学生关系S的“系别”属性是该关系S的外码，学生关系S是参照关系，系别关系D是被参照关系，学生关系中某个学生（如S1或S2）“系别”的取值，必须在参照的系别关系中主码“系别”的值中能够找到，如果某个学生（如S11）“系别”取空值，则表示该学生尚未分配到任何一个系；否则，它只能取系别关系中某个元组的系别号值。



>  
 3、关系的性质主要包括哪些方面？为什么只限用规范化关系？ 


关系具有如下性质： 1）列是同质的，即每一列中的分量必须来自同一个域，必须是同一类型的数据；

2）不同的属性可来自同一个域，但不同的属性必须有不同的名字；

3）列的顺序可以任意交换。但交换时，应连同属性名一起交换，否则将得到不同的关系；

4）关系中元组的顺序（即行序）可任意，在一个关系中可以任意交换两行的次序。因为关系是以元组为元素的集合，而集合中的元素是无序的，所以作为集合元素的元组也是无序的；

5）关系中不允许出现相同的元组。因为数学上集合中没有相同的元素，而关系是元组的集合，所以作为集合元素的元组应该是唯一的；

6）关系中每一分量必须是不可分的数据项，或者说所有属性值都是原子的，即是一个确定的值，而不是值的集合。属性值可以为空值，表示“未知”或“不可使用”，但不可“表中有表”；

由于非规划化关系会导致数据冗余、插入异常、删除异常、更新异常等问题，因此在构建关系时，应使用规范化关系。



>  
 4、举例说明等值连接与自然连接的区别和联系 


所谓自然连接就是在等值连接的情况下，当连接属性X与Y具有相同属性组时，把在连接结果中重复的属性列去掉

R

|A|B|C|
|--|--|--|
|a1|b1|2|
|a1|b2|4|
|a2|b3|6|
|a2|b4|8|

S

|B|D|
|---|---|
|b1|5|
|b2|6|
|b3|7|
|b4|8|

等值连接与自然连接的区别如下： 1）等值连接中不要求相等属性值的属性名相同，而自然连接要求相等属性值的属性名必须相同，即两关系只有同名属性才能进行自然连接。如上图R中的C列和S中的D列可进行等值连接，但因为属性名不同，不能进行自然连接;

2）在连接结果中，等值连接不将重复属性去掉，而自然连接去掉重复属性，也可以说，自然连接是去掉重复列的等值连接。如上图R中的B列和S中的B列进行等值连接时，结果有两个重复的属性列B，而进行自然连接时，结果只有一个属性列B



>  
 5、解释下列概念：笛卡尔积、关系、同类关系、关系头、关系体、属性、元组、域、关系键、候选键、主键、外部键、关系模式、关系数据库模式、关系数据库、关系数据库的型与值 

<mark>笛卡儿积</mark>（Cartesian Product）：给定一组域D1，D2，…，Dn（它们可以包含相同的元素，既可以完全不同，也可以部分或全部相同），则D1，D2，…，Dn的笛卡儿积为： D1×D2×…×Dn={（d1，d2，…，dn）|di∈Di，i=1，2，…，n}；



<mark>关系</mark>（Relation）：笛卡儿积D1×D2×…×Dn的任一子集称为定义在域D1，D2，…，Dn上的n元关系（Relation），可用R（D1，D2，…，Dn）表示。 具有相同关系框架的关系称为同类关系；



<mark>关系头</mark>（Heading）：关系头由属性名A1，A2，…，An的集合组成，每个属性Ai对应一个域Di（i=1，2，…，n）。关系头（关系框架）是关系的数据结构的描述，它是固定不变的；



<mark>关系体</mark>（Body）：关系体是指关系结构中的内容或者数据，它随元组的插入、删除或修改而变化；

由于不同域（列）的取值可以相同，为了加以区别，必须对每个域（列）起一个名字，称为<mark>属性</mark>（Attribute）；

关系中的每个元素是关系中的<mark>元组</mark>；



<mark>域</mark>（Domain）。域是一组具有相同数据类型的值的集合，又称为值域（用D表示）；

<mark>关系键</mark>是一个表中的一个或几个属性，用来标识该表的每一行或与另一个表产生联系；

<mark>候选码</mark>（Candidate Key）：能唯一标识关系中元组的一个属性或属性集，称为候选码，也称候选关键字或候选键；



<mark>主码</mark>（Primary Key）：如果一个关系中有多个候选码，可以从中选择一个作为查询、插入或删除元组的操作变量，被选用的候选码称为主码，或称为主关系键、主键、关系键、关键字等；

如果关系R2的一个或一组属性X不是R2的主码，而是另一关系R1的主码，则该属性或属性组X称为关系R2的外码（Foreign key）或<mark>外部关系键</mark>；

关系的描述称为<mark>关系模式</mark>（Relation Schema）。它可以形式化地表示为： R（U，D，DOM，F）

关系数据库的型称为<mark>关系数据库模式</mark>，是对关系数据库的描述，它包括若干域的定义以及在这些域上定义的若干关系模式；

在一个给定的应用领域中，所有实体以及实体之间联系所对应的关系的集合构成一个<mark>关系数据库</mark>；

<mark>关系数据库的型</mark>称为关系数据库模式，是对关系数据库的描述，它包括若干域的定义以及在这些域上定义的若干关系模式;<mark>关系数据库的值</mark>也称为关系数据库，是这些关系模式在某一时刻对应的关系的集合;



>  
 6、以第1章的图1-21所示的教学管理数据库为例，用关系代数表达式表示以下各种查询要求 


1）查询T1老师所授课程的课程号和课程名

Π<sub>CNO，CN</sub> (σ<sub>TNO=</sub> <sub>‘T1’</sub>(TC)⋈Π <sub>CNO,CN</sub>( C))

2）查询年龄大于18岁的男同学的课程号、课程名、系别

Π<sub>SNO,SN,Dept</sub>(σ<sub>Age&gt;18∧Sex=‘男’</sub> (S))

3）查询“李力”老师所讲授课程的课程号、课程名和课时

Π<sub>CNo</sub> (Π<sub>TNo</sub>(σ<sub>TN=‘李力’</sub>(T)⋈TC) ⋈ C

4）查询学号为S1的同学所选修课程的课程号、课程名和成绩

Π<sub>CNo,CN,Score</sub> (σ<sub>SNo=‘S1’</sub> (SC) ⋈ Π<sub>CNo,CN</sub> ( C))

5）查询“钱尔”同学所选修课程的课程号、课程名和成绩

Π<sub>CNo,CN,Score</sub>(Π<sub>SNo</sub> (σ<sub>SNo=‘钱尔’</sub>(S)) ⋈ Π<sub>Cno</sub>, <sub>CN</sub>( C) ⋈ SC)

6）查询至少选修“刘伟”老师所授全部课程的学生姓名

Π<sub>SN</sub> (Π<sub>SNo,SN</sub> (S)⋈Π<sub>SNo,CNo</sub>(SC)÷ Π<sub>CNO</sub> (σ<sub>TN=‘刘伟’</sub>(T⋈TC)))

7）查询“李思”同学未选修的课程号和课程名

Π<sub>CNo,CN</sub>((Π<sub>CNo</sub> ( C) - Π<sub>CNo</sub> (σ<sub>TN=‘李思’</sub> (S)⋈SC))⋈C）

8）查询全部学生都选修了的课程的课程号、课程名

Π<sub>CNo,CN</sub> (C⋈(Π<sub>SNo,CNo</sub> (SC) ÷ Π<sub>SNo</sub> (S)))

9）查询选修了课程号为C1和C2的学生的学号和姓名

Π<sub>SNo,CNo</sub>(SC) ÷ Π<sub>CNo</sub> (σ<sub>CNo=</sub> <sub>‘C1’</sub> <sub>⋁</sub> <sub>CNo=‘C2’</sub> ) ( C))⋈Π<sub>SNo,SN</sub> (S)

10）查询选修了全部课程的学生的学号和姓名

Π<sub>SNo,SN</sub> (S⋈(Π<sub>SNo,CNo</sub>(SC)÷ Π<sub>CNo</sub>( C)))
