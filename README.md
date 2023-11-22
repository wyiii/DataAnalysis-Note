# DataAnalysis-Note
notes of learning data analysis

## Hadoop
  是Apache旗下的一个用java语言实现的开源软件框架，是一个开发和运行处理大规模数据的软件平台。    
  Hadoop核心组件：  
  
    1 HDFS（分布式文件系统）：解决海量数据存储  
    2 MapReduce（分布式运算编程框架）：解决海量数据计算  
    3 YARN（作业调度和集群资源管理的框架）：解决资源任务调度  
  
## MapReduce 
  一个MapReduce作业（job）通常会把输入的数据集切分成若干独立的数据块，由map任务（task）以完全并行的方式处理它们。框架会对map的输出排序，然后把结果输入给reduce任务。
  
  2个工作阶段： 
  
    1 Map（分割、映射）  
    2 Reduce（重排、还原）  

  时间顺序4个阶段：

    1 输入分片 input split
    2 映射 mapping
    3 重排 shuffling
    5 Reduce reducing

  

## 数据治理

## 报表工具

    1 TableAU  
    2 PowerBI  
    3 FineBI  
