# proj-la-xv6-automated-scoring-system
xv6 automated scoring system for loongarch64

## 项目名称
基于LoongArch架构的xv6实验自动评判系统

## 支持单位
龙芯中科技术股份有限公司、中国科学院计算技术研究所

## 项目描述
对现有的龙芯xv6实验，设计一个自动批改系统，学生提交指定实验的代码后可以获得是否通过的判定结果。实验内容见https://github.com/SKT-CPUOS/xv6-loongarc
h-exp（具体见其中的龙芯-xv6操作系统实验-22-11-13（整洁-无修订）.pdf）。

## 编程语言
Python等

## 所属赛道
2023全国大学生操作系统比赛的“OS功能挑战”赛道 

## 参赛要求
* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生；
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖；
* 请遵循“2023全国大学生操作系统比赛”的章程和技术方案要求。
## 项目导师
* 张福新
    - github github.com/foxsen
    - Email  fxzhang@ict.ac.cn

## 难度
中-低

# License
GPL V3.0.

## 预期目标
1. 评测系统提前定制每个实验的初始xv6源代码，学生下载从系统下载对应的初始代码；
2. 学生基于上述源代码进行修改，编写代码完成实验要求功能，然后提交代码到评测系统；
3. 评测系统结合运行结果，xv6操作系统内部数据、状态，进行综合分析，给出测试结果。同时将代码的diff结果保存等待教师进一步查阅；
4. 上述服务封装成独立服务，完成初始代码的下载，提交，以及返回平台结果；
5. 提供评测系统项目的编译，运行，测试文档。

## 参考资源
* [龙芯-xv6操作系统源代码 以及 龙芯-xv6操作系统实验-22-11-13（整洁-无修订）.pdf](https://github.com/SKT-CPUOS/xv6-loongarch-exp)

## 备注
进入决赛的团队，龙芯可提供所需平台，在龙芯3A5000等真实机器上调试运行目标系统并完成性能优化
