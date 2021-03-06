# 数据库原理及应用 习题一 答案作者：陈九礼

*原文链接：[数据库原理及应用教程(第4版|微课版)陈志泊-第一章习题_陈九礼](https://blog.csdn.net/weixin_41640994/article/details/103517155)*

# 一、选择题

>  
 1、数据库(DB)、数据库系统(DBS)、数据库管理系统(DBMS)之间的关系是() 

 A）DB包含DBS和DBMS  B）DBMS包含DB和DBS  <mark>C）DBS包含DB和DBMS</mark>  D）没有任何关系



>  
 2、数据库系统的核心软件是() 

 A）数据模型 <mark>B）数据库管理系统</mark> C）数据库 D）数据库管理员



>  
 3、数据独立性是数据库技术的重要特点之一。所谓数据独立性是指() 

 A）数据与程序独立存放  B）不同的数据被存放在不同的文件中  C）不同的数据只能被对应的应用程序所使用  <mark>D）以上三种说法都不对</mark>



>  
 4、用树形结构表示实体之间联系的模型是() 

 A）关系模型 B）网状模型 <mark>C）层次模型</mark>  D）以上三种都是



>  
 5、“商品”与“顾客”两个实体集之间联系一般是() 

 A）一对一 B）一对多 C）多对一 <mark>D）多对多</mark>



>  
 6、下列关于数据库的正确叙述是() 

 A）数据库中只存在数据项之间的联系  <mark>B）数据库的数据项之间和记录之间都存在联系</mark>  C）数据库的数据项之间无联系，记录之间存在联系  D）数据库的数据项之间和记录之间都不存在联系



>  
 7、在数据库管理系统提供的数据语言中，负责数据的模式定义与数据的物理存取构建的是() 

 <mark>A）数据定义语言</mark> B）数据转换语言 C）数据操纵语言 D）数据控制语言



>  
 8、数据库系统的三级模式结构中，下列不属于三级模式的是() 

 A）内模式 <mark>B）抽象模式</mark> C）外模式 D）模式



>  
 9、在数据库管理系统提供的语言中，负责数据的完整性、安全性的定义与检查以及并发控制、故障恢复等功能的是() 

 A）数据定义语言 B）数据转换语言 C）数据操纵语言 <mark>D）数据控制语言</mark>



>  
 10、下面关于数据系统叙述正确的是() 

 A）数据库系统避免了一切冗余  <mark>B）数据库系统减少了数据冗余</mark>  C）数据库系统比文件系统能管理更多的数据  D）数据库系统中数据的一致性是指数据类型的一致



>  
 11、下列叙述中，错误的是() 

 A）数据库技术的根本目标是要解决数据共享的问题  B）数据库设计是指设计一个能满足用户的要求，性能良好的数据库  <mark>C）数据库系统中，数据的物理结构必须与逻辑结构一致</mark>  D）数据库系统是一个独立的系统，但是需要操作系统的支持



>  
 12、在数据库管理系统提供的数据语言中，负责数据的查询及增、删、改等操作的是() 

 A）数据定义语言 B）数据转换语言 C）数据控制语言 <mark>D）数据操纵语言</mark>



>   13、下列有关数据库的描述，正确的是() 

 A）<mark>数据库是一个结构化的数据集合</mark>  B）数据库是一个关系  C）数据库是一个DBF文件  D）数据库是一组文件



>  
 14、在数据库的三级模式结构中，模式数据库中全体数据的全局逻辑结构和特征的是() 

 A）外模式 B）内模式 C）存储模式 <mark>D）模式</mark>



>  
 15、()是存储在计算机内有结构的数据的集合。 

 A）数据库系统 <mark>B）数据库</mark> C）数据库管理系统 D）数据结构



>  
 16、()是位于用户与操作系统之间的一层数据管理软件。 

 A）数据库系统 B）数据库应用软件 <mark>C）数据库管理系统</mark> D）数据库



>  
 17、数据库系统的三级模式中，表达物理数据库的是() 

 A）外模式 B）模式 C）用户模式 <mark>D）内模式</mark>



>  
 18、供应商可以给某个工程提供多种材料，同一种材料也可以由不同的供应商提供，从材料到供应商之间的联系类型是() 


 <mark>A）多对多</mark> B）一对一 C）多对一 D）一对多

>  
 19、子模式是() 

 A）模式的副本 B）存储模式 C）多个模式的集合 <mark>D）模式的逻辑子集</mark>



>  
 20、数据库中不仅能够保存数据本身，而且能保存数据之间的相互联系，保证了对数据修改的() 

 <mark>A）独立性</mark> B）安全性 C）共享性 D）一致性



>  
 21、一个数据库系统的外模式() 

 A）只能有一个 B）最多只能有一个 C）至少两个 <mark>D）可以有多个</mark>



>  
 22、数据库三级模式中，真正存在的是() 

 A）外模式 B）子模式 C）模式 <mark>D）内模式</mark>



>  
 23、在数据库中，数据的物理独立性是指() 

 A）数据库与数据管理系统的相互独立  B）用户程序与DBMS的相互独立  <mark>C）用户的应用程序与存储磁盘上数据的相互独立</mark>  D）应用程序与数据库中数据的逻辑结果相互独立



>  
 24、为了保证数据库的逻辑独立性，需要修改的是() 

 <mark>A）模式与外模式之间的映射</mark>  B）模式与内模式之间的映射  C）模式  D）三级模式



>  
 25、层次模式不能直接表示() 

 A）1:1联系 B）1:n联系 <mark>C）m:n联系</mark> D）1:1和1:n联系



# 二、填空题

1、数据管理技术发展过程经过人工管理、文件系统和数据库三个阶段，其中数据独立性最高的阶段是<mark>数据库系统</mark>



2、在关系数据库中，把数据表示为二维表，每一个二维表称为<mark>一个关系</mark>



3、在数据库理论中，数据物理结构的改变如存储设备的更换、物理存储的更换、存取方式等都不影响数据库的逻辑结构，从而不引起应用程序的变化，称为<mark>物理独立性</mark>



4、数据库管理系统是位于用户与<mark>操作系统</mark>之间的软件系统



5、数据库系统中，实现数据管理功能的核心软件称为<mark>数据库管理系统</mark>



6、一个项目具有一个项目主管，一个项目主管可管理多个项目，则实体“项目主管”与实体“项目”间的关系属于<mark>一对多</mark>的关系



7、数据库三级模式体系结构的划分，有利于保持数据的<mark>独立性</mark>



8、数据库保护分为：安全性控制、<mark>完整性控制</mark>、并发性控制和数据恢复



9、在数据库理论中，数据库总体逻辑结构的改变，如修改数据模式、增加新的数据类型、改变数据间联系等，不需要修改相应的应用程序，称为<mark>逻辑独立性</mark>



10、数据库管理系统常见的数据模型有层次模型、网状模型和<mark>关系模型</mark>



11、对现实世界进行第一层抽象的模型，称为<mark>概念</mark>模型；对现实世界进行第二层抽象的模型，称为<mark>结构</mark>(或<mark>逻辑</mark>)模型



12、层次模型的数据结构是<mark>树</mark>结构；网状模型的数据结构是<mark>有向图</mark>结构；关系模型的数据结构是<mark>二维表</mark>结构；面向对象的数据结构之间可以<mark>嵌套和递归</mark>



13、在数据库技术中，编写应用程序的语言一般是C、Basic等高级语言，这些语言被称为<mark>宿主语言(或主语言)</mark>



14、数据库系统中，用来存放三级结构定义的数据库称为<mark>数据字典</mark>



15、从最终用户来看，数据库系统的外部体系结构可分为五种类型：<mark>单用户结构</mark>，<mark>主从式结构</mark>，<mark>分布式结构</mark>，<mark>客户/服务器结构</mark>，<mark>浏览器/服务器结构</mark>



16、现实世界的事物反映到人的头脑中经过思维加工成数据，这一过程需要结果的三个世界的转换，依次是<mark>现实世界</mark>，<mark>信息世界</mark>，<mark>数据世界</mark>



# 三、简答题

>  
 1、简述数据管理技术发展的三个阶段和各个阶段的特点是什么？ 


随着计算机硬件和软件的发展，数据管理经历了人工管理、文件系统和数据库系统三个发展阶段。

<mark>人工管理阶段</mark>： 1）数据没有专门的存储设备 2）数据没有专门的管理软件 3）数据不共享 4）数据不具有独立性

<mark>文件系统阶段</mark>： 1）数据以文件形式长期保存 2）由文件系统管理数据 3）数据与数据间有一定独立性 4）文件的形式已经多样化 5）数据具有一定的共享性

<mark>数据库系统阶段</mark>： 1）结构化的数据及其联系的集合 2）数据共享性高、冗余度低 3）数据独立性高 4）有统一的数据管理和控制功能



>  
 2、从程序和数据之间的关系分析文件系统和数据库系统之间的区别和联系 

<mark>文件系统阶段</mark>中，我们关注的是系统功能的设计，程序设计处于主导地位，数据服从于程序设计； <mark>数据库系统阶段</mark>中，数据占据位置的中心，数据的结构设计成为信息系统首先关心的问题。



>  
 3、简述数据库、数据库管理系统、数据库系统三个概念的含义和联系 


<mark>数据库系统</mark>(DataBase System,，DBS)：指在计算机系统中引入数据库后的系统

<mark>数据库管理系统</mark>(DBMS)：是对数据进行管理的大型系统软件

<mark>数据库</mark>(DataBase，DB)：是指存储在计算机内、有组织、可共享的数据和数据对象的集合

数据库是数据库系统的<mark>基础</mark>，数据库管理系统是数据库系统的<mark>核心软件</mark>，用户通过数据库管理系统实现对数据库中数据的<mark>存取、维护和管理</mark>



>  
 4、数据库系统包括哪几个主要组成部分？各部分的功能时什么？画虎成整个数据库系统的层级结构图。 


数据库系统主要由数据库、数据库用户、计算机硬件系统和计算机软件系统等几部分组成。

<mark>数据库</mark>：按一定的数据模型（或结构）组织、描述并长期存储，同时能以安全和可靠的方法进行数据的检索和存储。

数据库<mark>用户</mark>：可对数据库进行存储、维护和检索等操作。

计算机<mark>硬件系统</mark>：为数据库系统的存储和运行提供硬件环境。

计算机<mark>软件系统</mark>：实现对硬件的访问并实现对数据库中数据的存取、维护和管理。

<img src="https://img-blog.csdnimg.cn/20191213212818303.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MTY0MDk5NA==,size_16,color_FFFFFF,t_70" alt="在这里插入图片描述">



>  
 5、简述数据库管理系统的组成和功能 


一个完整的数据库管理系统通常应由： 1）语言编译处理程序 2）系统运行控制程序 3）系统建立、维护程序 4）数据字典

数据库管理系统的主要功能包括： 1）数据定义功能 2）数据操纵功能 3）数据库运行管理功能 4）数据库的建立和维护功能 5）数据通信接口 6）数据组织、存储和管理功能。



>  
 6、DBA指什么？它的主要职责是什么？ 

DBA即<mark>数据库管理员</mark>（DataBase Administrator， DBA）数据库管理员是负责设计、建立、管理和维护数据库以及协调用户对数据库要求的个人或工作团队。



>  
 7、试述数据三级模式结构，说明三级模式结构的优点是什么？ 


数据库三级模式结构把数据库系统内部的体系结构从逻辑上分为<mark>外模式</mark>、<mark>模式</mark>和<mark>内模式</mark>三级抽象模式结构和二级映像功能，即ANSI/SPARC体系结构。

数据库系统的三级模式与二级映像使数据库系统具有以下优点。 1）<mark>保证数据的独立性</mark>。将模式和内模式分开，保证了数据的物理独立性；将外模式和模式分开，保证了数据的逻辑独立性。 2）<mark>简化了用户接口</mark>。按照外模式编写应用程序或输入命令，而不需了解数据库内部的存储结构，方便用户使用系统。 3）<mark>有利于数据共享</mark>。在不同的外模式下可由多个用户共享系统中的数据，减少了数据冗余。 4）<mark>有利于数据的安全保密</mark>。在外模式下根据要求进行操作，只能对限定的数据操作，保证了其他数据的安全。



>  
 8、什么是数据库的数据独立性？它包含哪些内容？ 

数据库的数据独立性是指数据库中的数据与应用程序间相互独立，即数据的逻辑结构、存储结构以及存取方式的改变不影响应用程序。数据独立性包括物理独立性和逻辑独立性，其中，数据的物理独立性是指当数据库物理结构（如存储结构、存取方式、外部存储设备等）改变时，通过修改映射，使数据库逻辑结构不受影响，进而用户逻辑结构以及应用程序不用改变；数据的逻辑独立性是指当数据库逻辑结构（如修改数据定义、增加新的数据类型、改变数据间的关系等）发生改变时，通过修改映射，用户逻辑结构以及应用程序不用改变。



>  
 9、什么是数据字典？它的主要作用是什么？ 


数据字典（Data Dictionary，DD）用来描述数据库中有关信息的数据目录，包括数据库的三级模式、数据类型、用户名和用户权限等有关数据库系统的信息。

数据字典起着系统状态的目录表的作用，帮助用户、DBA和DBMS本身使用和管理数据库。



>  
 10、简述数据库管理系统的数据存储过程 

DBMS对数据的存取通常需要以下几个步骤。 1）用户使用某种特定的数据操作语言向DBMS发出存取请求 2）DBMS接受请求并将该请求解释转换成机器代码指令 3）DBMS依次检查外模式、外模式/模式映像、模式、模式/内模式映像及存储结构定义 4）DBMS对存储数据库执行必要的存取操作 5）从对数据库的存取操作中接受结果 6）对得到的结果进行必要的处理，如格式转换等 7）将处理的结果返回给用户。



>  
 11、解释实体、属性、码、实体集、实体型、实体联系类型、记录、数据项、字段、记录型、文件、实体模型和数据模型的含义 


<mark>实体</mark>（Entity）：客观存在并且可以相互区别的“事物”称为实体

<mark>属性</mark>（Attribute）：实体所具有的某一特性称为属性

<mark>码</mark>（Key）：在实体型中，能唯一标识一个实体的属性或属性集称为实体的码

<mark>实体集</mark>（Entity Set）：同型实体的集合称为实体集

<mark>实体型</mark>（Entity Type）：用实体名及其属性名集合来抽象和描述同类实体，称为实体型

<mark>实体联系类型</mark>：指不同的实体集间的联系的类型，可分为一对一联系（1:1）、一对多联系（1：n）、多对多联系（m:n）三种

<mark>记录</mark>（Record）：字段的有序集合称为记录

<mark>字段</mark>（Field）：标记实体属性的命名单位称为字段，也称为数据项

<mark>文件</mark>（File）：同一类记录的集合称为文件

<mark>记录型</mark>：层次模型的树形结构中，每个结点表示一个记录型，每个记录型可包含若干个字段，记录型描述的是实体，字段描述实体的属性

<mark>文件</mark>（File）：同一类记录的集合称为文件

<mark>实体模型</mark>：按用户的观点对数据和信息建模，是对现实世界的事物及其联系的第一级抽象，它不依赖与具体的计算机系统，不涉及信息在计算机内如何表示，如何处理等问题，只是用来描述某个特定组织所关心的信息结构。

<mark>数据模型</mark>：数据库的框架，该框架描述了数据及其联系的组织方式、表达方式和存取路径。



>   12、数据模型的主要作用是什么？三类基本数据模型的划分依据是什么？各有哪些优点 


数据模型是现实世界中的事物及其联系的一种模拟和抽象表示，是一种形式化描述数据、数据间联系以及有关语义约束规则的方法。

三类基本数据模型的划分基于模型的数据结构类型。

<mark>层次模型</mark>（Hierarchical Model） 优点： 1）层次模型结构比较简单，层次分明，便于在计算机内实现 2）结点间联系简单，从根结点到树中任一结点均存在一条唯一的层次路径，当要存取某个结点的记录值时，沿着这条路径很快就能找到该记录值，因此，以该种模型建立的数据库系统查询效率很高 3）它提供了良好的数据完整性支持

缺点： 1）不能直接表示两个以上的实体型间的复杂联系和实体型间的多对多联系，只能通过引入冗余数据或创建虚拟结点的方法来解决，易产生不一致性 2）对数据插入和删除的操作限制太多 3）查询子女结点必须通过双亲结点

<mark>网状模型</mark>（Network Model） 优点： 1）能更为直接地描述客观世界，可表示实体间的多种复杂联系 2）具有良好的性能和存储效率

缺点： 1）数据结构复杂，并且随着应用环境的扩大，数据库的结构变得越来越复杂，不便于终端用户掌握 2）其数据定义语言（DDL）和数据操纵语言（DML）极其复杂，不易使用户掌握 3）由于记录间的联系本质上是通过存取路径实现的，应用程序在访问数据库时要指定存取路径，即用户需要了解网状模型的实现细节，加重了编写应用程序的负担

<mark>关系模型</mark>（Relational Model） 优点： 1）关系模型与非关系模型不同，它有严格的数学理论根据 2）数据结构简单、清晰，用户易懂、易用，不仅用关系描述实体，而且用关系描述实体间的联系。此外，对数据的操纵结果也是关系 3）关系模型的存取路径对用户透明，从而具有更高的数据独立性、更好的安全保密性，也简化了程序员的工作和数据库建立和开发的工作

缺点： 关系模型的缺点是查询效率不如非关系模型，增加了开发数据库管理系统的负担



>  
 13、实体型间的联系有哪几种？其含义是什么？并举例说明 


实体型间的联系有如下三种类型 1）<mark>一对一联系</mark>（1:1）：实体集A中的一个实体至多与实体集B中的一个实体相对应，反之，实体集B中的一个实体至多与实体集A中的一个实体相对应，则称实体集A与实体集B为一对一的联系，记作1:1

2）<mark>一对多联系</mark>（1:n）：实体集A中的一个实体与实体集B中的n（n≥0）个实体相联系，反之，实体集B中的一个实体至多与实体集A中的一个实体相联系，记作1:n

3）<mark>多对多联系</mark>（m:n）：实体集A中的一个实体与实体集B中的n（n≥0）个实体相联系，反之，实体集B中的一个实体与实体集A中的m（m≥0）个实体相联系，记作m:n



>  
 14、解释模式、内模式、外模式、DDL和DML的含义 


<mark>模式</mark>：模式也称为概念模式，处于三级模式结构的中间层，是数据库中全体数据的逻辑结构和特征的描述

<mark>内模式</mark>：内模式（Internal Schema）又称存储模式（Storage Schema）或物理模式（Physical Schema），是三级结构中的最内层，是对数据库存储结构的描述，是数据在数据库内部的表示方式

<mark>外模式</mark>：外模式（External Schema）又称为子模式（Subschema）或用户模式（User Schema），是三级结构的最外层，是数据库用户能看到并允许使用的那部分数据的逻辑结构和特征的描述，是与某一应用有关的数据的逻辑表示，也是数据库用户的数据视图，即用户视图

<mark>DDL</mark>：数据定义语言（Data Define Language），用于定义数据的模式、外模式和内模式三级模式结构，定义模式/内模式和外模式/模式二级映像，定义有关的约束条件

<mark>DML</mark>：数据操纵语言（Data Manipulation Language），实现对数据库的基本操作，包括检索、更新（包括插入、修改和删除）等



>  
 15、试述传统数据库的局限性 

传统数据库通常为集中式系统，不在同一地点的数据无法共享；系统过于庞大、复杂，显得不灵活且安全性较差；存储容量有限，不能完全适应信息资源存储要求等。传统数据库对数据的处理无法满足决策需求。传统数据库通常用于处理结构化数据，无法满足非结构化数据的处理需求



>  
 16、面向对象数据库的主要研究内容是什么？ 

面向对象数据库是面向对象概念与数据库技术相结合的产物，用于描述具有复杂数据结构的数据类型



>  
 17、什么是分布式数据库？其特点是什么？ 


分布式数据库是一组结构化的数据集合，它们在逻辑上属于同一系统，而在物理上分布在计算机网络的不同结点上。网络中的各个结点（也称为“场地”）一般都是集中式数据库系统，由计算机、数据库和若干终端组成。

分布式数据库具有如下特点： 1）<mark>自治与共享</mark>：分布式数据库有集中式数据库的共享性与集成性，但它更强调自治及可控制的共享

2）<mark>冗余的控制</mark>：分布式数据库允许冗余，这种冗余增加了自治性，不仅改善了系统性能，同时也增加了系统的可用性，但同时增加了存储代价，也增加了副本更新时的一致性代价

3）<mark>分布事务执行的复杂性</mark>：分布式数据库存取的事务是一种全局性事务，它是由许多在不同结点上执行对各局部数据库存取的局部子事务组成的。如果仍保持事务执行的原子性，则必须保证全局事务的原子性

4）<mark>数据的独立性</mark>：使用分布式数据库时，应该像使用集中式数据库时一样，即系统要提供一种完全透明的性能，具体包括：逻辑数据透明性、物理数据透明性、数据分布透明性、数据冗余透明性



>  
 18、简述数据挖掘的处理过程分为几个阶段？ 


数据挖掘的处理过程可分为以下八个阶段。 1）<mark>信息收集</mark>：根据确定的数据分析对象抽象出在数据分析中所需要的特征信息，然后选择合适的信息收集方法，将收集到的信息存入数据库

2）<mark>数据集成</mark>：把不同来源、格式、特点性质的数据在逻辑上或物理上有机地集中，从而为企业提供全面的数据共享

3）<mark>数据规约</mark>：数据规约技术用来得到数据集的规约表示，它小得多，但仍然接近于保持原数据的完整性，并且规约后执行数据挖掘结果与规约前执行结果相同或几乎相同

4）<mark>数据清理</mark>：在数据库中的数据有一些是不完整、含噪声、并且是不一致的，因此需要进行数据清理，将完整、正确、一致的数据信息存入数据仓库中

5）<mark>数据变换</mark>：通过平滑聚集，数据概化，规范化等方式将数据转换成适用于数据挖掘的形式。对于有些实数型数据,通过概念分层和数据的离散化来转换数据也是重要的一步

6）<mark>数据挖掘过程</mark>：根据数据仓库中的数据信息，选择合适的分析工具，应用统计方法、事例推理、决策树、规则推理、模糊集、甚至神经网络、遗传算法的方法处理信息，得出有用的分析信息

7）<mark>模式评估</mark>：从商业角度，由行业专家来验证数据挖掘结果的正确性

8）<mark>知识表示</mark>：将数据挖掘所得到的分析信息以可视化的方式呈现给用户，或作为新的知识存放在知识库中，供其他应用程序使用



>  
 19、大数据定义的4V阶段包括哪些？ 


大数据的4V特性即： 1）数据量大（Volume） 2）数据类型繁多（Variety） 3）数据处理速度快（Velocity） 4）数据价值密度低（Value）

“<mark>数据量大</mark>”是从数据规模的角度描述大数据的

“<mark>数据类型繁多</mark>”是从数据来源和数据种类的角度描述大数据的

“<mark>数据处理速度快</mark>”是从数据的产生和处理的角度描述大数据的

“<mark>数据价值密度低</mark>”是从大数据潜藏的价值分布情况描述大数据的



>  
 20、简述大数据的关键技术 


目前大数据所涉及的关键技术主要包括数据的<mark>采集和迁移</mark>、<mark>数据的存储和管理</mark>、<mark>数据的处理和分析</mark>、<mark>数据安全和隐私保护</mark>

数据采集技术将分布在异构数据源或异构采集设备上的数据通过清洗、转换和集成技术，存储到分布式文件系统中，成为数据分析、挖掘和应用的基础。数据迁移技术将数据从关系型数据库迁移到分布式文件系统或NoSQL数据库中

数据处理和分析技术利用分布式并行编程模型和计算框架，结合模式识别、人工智能、机器学习、数据挖掘等算法，实现对大数据的离线分析和大数据流的在线分析

数据安全和隐私保护是指在确保大数据被良性利用的同时，通过隐私保护策略和数据安全等手段，构建大数据环境下的数据隐私和安全保护
