# crawl_shenzhen_rent
this is a project which crawl information from the https://order.zuche.com/order/OrderSecondControl.do.
The information includes:
the name of the car
the price of the car
and some other information

To run:
python shenzhou_spider.py beijng.txt

requirements:
python 2.7
selenium-3.4.3
geckodriver-v0.18.0 as firefox driver

The spider result seems like as follow and it is saved in excel:
number	name	info	price_per_day	price_total
1	雪佛兰科鲁兹	三厢 | 1.6自动 | 乘坐5人	136	271
2	大众朗逸	三厢 | 1.6自动 | 乘坐5人	150	300
3	大众斯柯达明锐	三厢 | 1.6自动 | 乘坐5人	126	251
4	雪佛兰新科鲁兹	三厢 | 1.5自动 | 乘坐5人	136	272
5	别克英朗	三厢 | 1.5自动 | 乘坐5人	150	300
6	别克威朗	三厢 | 1.5自动 | 乘坐5人	189	377
7	2016别克昂科拉	SUV | 1.4T自动 | 乘坐5人	208	415
8	丰田凯美瑞	三厢 | 2.0自动 | 乘坐5人	278	556
9	别克新君越	三厢 | 2.4自动 | 乘坐5人	285	570
10	大众帕萨特	三厢 | 1.8T自动 | 乘坐5人	315	630
11	别克GL8	7座 | 2.4自动 | 乘坐7人	424	847
12	雪佛兰迈锐宝	三厢 | 1.5T自动 | 乘坐5人	218	435
13	大通G10	7座 | 2.0自动 | 乘坐7人	278	555
14	大众途观	SUV | 1.8T自动 | 乘坐5人	584	1167
15	大众桑塔纳	三厢 | 1.6自动 | 乘坐5人	126	251
16	起亚K2	三厢 | 1.4自动 | 乘坐5人	139	277
17	丰田致炫	两厢 | 1.3自动 | 乘坐5人	139	277
18	别克凯越	三厢 | 1.6自动 | 乘坐5人	164	328
19	2014雪铁龙爱丽舍	三厢 | 1.6自动 | 乘坐5人	164	328
20	现代索纳塔8代	三厢 | 2.0自动 | 乘坐5人	268	535
21	起亚K5	三厢 | 2.0自动 | 乘坐5人	277	554
22	别克昂科威	SUV | 1.5T自动 | 乘坐5人	449	898
23	起亚狮跑	SUV | 2.0自动 | 乘坐5人	557	1114
24	三菱帕杰罗劲畅	SUV | 3.0自动 | 乘坐5人	736	1472

