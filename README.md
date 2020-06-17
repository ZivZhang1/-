# -
《防火墙技术》实践考核方案



一、考核内容
熟悉防火墙技术的原理、应用，使学生了解防火墙技术的发展和分类，掌握防火墙的工作原理和功能配置，掌握防火墙在网络规划设计中具体应用方案。


二、考核方式
通过设计一个综合的网络规划项目，考核学生运用所学知识解决实际问题的能力。


三、考核题目：
信阳农林学院校园占地1430余亩，校舍建筑面积44.5万余平方米，包含羊山校区、浉河校区、南湾校区。在校学生1.4万余人，主校区羊山校区主要建筑有三大区域，分别是行政楼区域、图书馆区域、学生宿舍区域。图书馆区域主要为服务器数据中心，行政楼主要为教师上网区域人数为300左右，学生宿舍区域为20栋学生宿舍楼，学生上网人数为1.4万余人。
学校中心机房位于图书馆四楼，拥有教务系统、学校官网，校内办公网三台web服务器；整个网络通过华为防火墙接入互联网。
根据上面的情况请对信阳农林学院的网络规划进行设计，设计报告要做好需求分析，设计方案中要体现设计原则、设计思路、设计标准、画出校园网拓扑图，并在华为模拟器中对合适设备进行的选取，保证学校网络及不同校区之间网络通信的安全稳定。


四、考核要求：
1、对信阳农林学院网络规划进行需求分析，写出简单的需求分析报告。  
2、对信阳农林学院整体网络进行规划设计，规划设计要科学合理有据，使用华为模拟器设计出拓扑结构图，测试网络规划的可行性与安全性。
3、规划要求：
（1）请根据行政楼区域，学生宿舍楼区域，图书馆区域以及浉河区校区（人数较少）的上网人数需求合理分配IP网段，满足各区域上网需求。
（2）整个网络规划为三层网络架构，接入层、汇聚层、核心层，出口使用华为防火墙，请根据需求划分好防火墙安全区域，行政楼、学生宿舍至图书馆机房带宽应不低于2000M。
（3）羊山校区内所有交换机设备应可以在局域网内任意一台设备可通过Telnet远程管理。
（4）行政楼及学生宿舍区域上网设备应可自动获取IP地址。
（5）行政楼区域可对图书馆中心机房中web服务随意访问，学生宿舍区域不能访问校内办公网服务器，外网用户只可访问学校官网服务器。
（6）为保障网络稳定，核心交换机要部署双机热备。
（7）请配置好出口nat地址转换，以及学校官网服务器外网访问端口映射
（8）为保证羊山校区和浉河校区通信安全，两校区通信采用ipsec vpn方式进行通信。
4、请根据上述要求完成网络规划设计报告。
5、请根据上述要求使用华为模拟器设计网络拓扑，并测试网络可行性。


五、成绩评定：
1、记分制：百分制
2、评分标准：
网络规划设计设计报告 60分
网络拓扑 40分
合计   100分
3、项目提交要求：
（1）设计说明书应包括封面、目录、摘要、正文、体会、参考文献等内容，以及附图或附件等材料。
（2）题目《信阳农林学院网络规划设计报告》；
（3）页边距：版面上页边距30mm，下页边距25mm，左页边距30mm，右页边距20mm；
行间距为单倍行距；
图的编号由“图”和阿拉伯数字组成，例如“图1”、“图2”等；每个图号后面都必须有图题，图的编号和图题要置于图下方的居中位置。
（4）设计报告电子版与网络拓扑压缩包以“学号姓名”格式命名，发至教师邮箱。

