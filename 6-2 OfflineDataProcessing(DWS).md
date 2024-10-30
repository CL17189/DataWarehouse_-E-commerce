# 数据处理(DWS)

## DWS层设计

（1）DWS层的设计参考指标体系。

（2）DWS层的数据存储格式为ORC列式存储 + snappy压缩。

（3）DWS层表名的命名规范为dws_数据域_统计粒度_业务过程_统计周期（1d/nd/td）

注：1d表示最近1日，nd表示最近n日，td表示历史至今。