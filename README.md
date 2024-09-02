# Sensor-Weapon-Target-Assignment

## Dataset Overview
This dataset is a simulated scenario dataset designed to address the problem of weapon, radar, and target allocation. Each entry in the dataset represents a specific battlefield configuration, including a fixed number of weapons and radars, as well as varying numbers of targets. The dataset is used to study how to optimize the allocation of weapons and radars under different conditions to counter target threats.

## Dataset Structure
Each sample in the dataset contains the following components:

  target_list: A list of target threats, describing relevant features of each target.
  
  damage_matrix: A damage probability matrix that describes the extent of damage each weapon inflicts on various targets.
  
  detect_matrix: A detection probability matrix that describes the probability of radars detecting each target.
  
  matching_matrix: A matching matrix that describes the relationship between weapons and radars, indicating which weapon-radar combinations are effective.
  
  ssl: The optimal allocation scheme, which is the best weapon-target assignment result calculated by an exact algorithm.
  
## Dataset Composition
This dataset consists of 3,500 samples, structured as follows:

  **Number of Weapons:** The number of weapons is fixed at 4.
  
  **Number of Radars:** The number of radars is fixed at 5.
  
  **Number of Targets:** The number of targets ranges from 2 to 8, covering 7 possible battlefield scenarios.
  
**500 Samples Per Scenario:** For each target number, 500 data samples are generated, each corresponding to different initial conditions and allocation results.

## Dataset Applications
This dataset is suitable for:
**Research on Weapon-Target Allocation Problems:** Exploring the performance of different allocation strategies under varying target numbers.
**Algorithm Benchmarking:** Used to evaluate the performance and effectiveness of different allocation algorithms.
**Training and Testing Machine Learning Models:** Can be used to train models that predict optimal allocation schemes.


## 数据集概述
该数据集是一个模拟生成的场景数据集，旨在解决武器、雷达与目标的分配问题。数据集的每一个条目代表一种特定的战场配置，包括固定数量的武器和雷达，以及不同数量的目标。数据集用于研究如何在不同条件下，优化武器和雷达的分配，以应对目标威胁。

## 数据集结构
数据集中的每个样本包含以下内容：

  target_list: 目标的威胁度列表，描述了每个目标的相关特征。
  
  damage_matrix: 毁伤概率矩阵，描述了每个武器对各个目标造成的损害程度。
  
  detect_matrix: 探测概率矩阵，描述了雷达对每个目标的检测概率。
  
  matching_matrix: 匹配矩阵，描述了武器和雷达之间的匹配关系，表示哪些武器和雷达组合是有效的。
  
  ssl: 最优分配方案，由精确算法计算得到的最佳武器-目标分配结果。
  
## 数据集组成
该数据集包含 3500 个样本，具体构成如下：

  武器数量: 数据集中武器数量固定为 4。
  
  雷达数量: 数据集中雷达数量固定为 5。
  
  目标数量: 目标数量从 2 至 8，覆盖了7种战场场景的可能性。
  
每个场景500个样本: 对于每一种目标数量，生成500个数据样本，每个样本对应不同的初始条件和分配结果。

## 数据集用途
该数据集适用于：
武器-目标分配问题的研究: 探索不同分配策略在不同目标数量下的表现。
算法基准测试: 用于评估不同分配算法的性能和效果。
机器学习模型的训练与测试: 可用于训练预测最优分配方案的模型。
