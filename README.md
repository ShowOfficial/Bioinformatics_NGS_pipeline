# Bioinformatics NGS Pipeline

## 项目概述
这个仓库包含了一系列用于下一代测序(NGS)数据分析的生物信息学流程脚本，是我在研究生期间自行总结并在课题组的数据分析中经过长期实战验证的pipeline。这些脚本涵盖了从原始数据处理到下游分析的多个方面，包括染色质免疫沉淀-测序(ChIP-seq)、双亚硫酸盐测序(Bisulfite-seq)、RNA测序(RNA-seq)和转录起始位点(TSS)富集分析等。

## 包含的流程

### TSS 富集热图分析
`TSS_enrich_heatMap` 目录包含用于生成转录起始位点(TSS)和转录终止位点(TES)周围富集水平热图的脚本。这对于评估ChIP-seq或ATAC-seq数据质量和可视化启动子区域的蛋白质结合模式非常有用。

### 双亚硫酸盐测序分析
`bisulfite-seq` 目录提供了处理和分析双亚硫酸盐测序数据的脚本，用于DNA甲基化研究。

### ChIP-seq组蛋白分析
`chip-seq` 目录中的脚本专门用于处理ChIP-seq数据，特别关注组蛋白修饰的分析。

### tDNA插入重测序
`resequencing_tDNA_insert` 目录包含用于分析转基因DNA(tDNA)插入位点的脚本，利用双末端(PE)测序数据。

### RNA-seq分析
`rna-seq` 目录提供了RNA测序数据分析的完整流程，用于基因表达研究。

## 使用方法

### 环境要求
- Bash shell环境(我使用Linux系统，其余系统未尝试)
- 生物信息学工具：流程中提到的软件皆可用bioconda下载
- R 统计环境(用于数据可视化)
- Python 3
