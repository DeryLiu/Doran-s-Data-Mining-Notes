                                                         Doran的数据挖掘笔记
===
[**Gitlab** 地址](https://github.com/DeryLiu/Doran-Data-Mining-Notes)

[**在线阅读地址**](https://deryliu.github.io/Doran-Data-Mining-Notes/)

**说明**（2020-02-26）：本文档是Doran的学习进阶笔记。**`不对外负责`**

---

## RoadMap
* [序言](000_序言/preface.md)
* [100_基础知识](100_基础知识/README.md)
   * [110_SQL技能](100_基础知识/110_SQL技能/README.md)
     - [111_SQL技能](100_基础知识/110_SQL技能/111_SQL技能.md)
   * [120_Python技能](100_基础知识/120_Python技能/README.md)
     - [120_Python技能](100_基础知识/120_Python技能/121_Python技能.md)
* [200_算法推导](200_算法推导/README.md)
   * [01_基础逻辑](200_算法推导/01_基础逻辑.md)
   * [02_订单结算](200_算法推导/02_订单结算.md)
   * [03_爬虫方案](200_算法推导/03_爬虫方案.md)
   * [04_比价覆盖房态](200_算法推导/04_比价覆盖房态.md)
* [300_框架工具](300_框架工具/README.md)
   * [310_Echart](300_框架工具/310_Echart/README.md)
   * [320_XGBoost](300_框架工具/320_XGBoost/README.md)
   * [330_Tensorflow](300_框架工具/330_Tensorflow/README.md)
* [400_项目案例](400_项目案例/README.md)
   * [410_Kaggle](400_项目案例/410_Kaggle/README.md)
* [500_面试准备](500_面试准备/README.md)
   * [01_Gitlab配置](500_面试准备/01_Gitlab配置.md)
* [600_其它资料](600_其它资料/README.md)
   * [01_Gitlab配置](600_其它资料/01_Gitlab配置.md)

工具
---
- 在线 LaTeX 公式编辑器 http://www.codecogs.com/latex/eqneditor.php
- 在线表格转 HTML 语言 http://www.tablesgenerator.com/html_tables

常用命令
---
- 文件初始化 gitbook init
- 下载新插件 gitbook install ./
- 书籍编译 gitbook build
- 网页端查看 gitbook serve
- 生成pdf文件 gitbook pdf
- 打包文件 gitbook build Doran-Data-Mining-Notes/outbook
- html文件不能调转
  - outbook/gitbook/theme.js
  - 将 `if(m)for(n.handler&&` 修改为 `if(false)for(n.handler&&`                                                                                                                                                                                                                                                                                                                                                                                                     
