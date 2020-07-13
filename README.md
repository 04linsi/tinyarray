# tinyarray

### 前言

hi，我是小洁。这是我基于自己的数据分析需求写的R包，很高兴被你看到了。我会在公众号《生信星球》更新这里面一些好用的小函数，也做一些其他的分享。

### 函数介绍
geo_download() : 提供geo编号，返回表达矩阵、临床信息表格和使用的平台编号。
get_deg() ：提供芯片表达矩阵、分组信息、探针注释，返回差异分析结果。
multi_deg() : 多个分组（最多5个）的差异分析
cor.full()和cor.one() :批量计算基因间的相关性
几个绘图函数：draw_heatmap,draw_volcano,draw_venn
trans_exp():将tcga或tcga+gtex数据进行id转换
t_choose():批量做单个基因的t检验
point_cut():批量计算生存分析最佳截点
surv_KM():批量做KM生存分析，支持用最佳截点分组
surv_cox():批量做cox生存分析，支持用最佳截点分组

### 尚未发表，还会继续更新
