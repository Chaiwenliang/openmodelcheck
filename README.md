# modelcheck

模型检查评测工具：openmodelcheck

采用最简单的html来实现

v1，重点针对模型问答对测试评估相关类型；

<img width="1457" height="703" alt="image" src="https://github.com/user-attachments/assets/0479a8c9-04e0-41c8-b4de-aedbefa9de91" />

v2，加入模型prompt输出对比；

<img width="1465" height="701" alt="image" src="https://github.com/user-attachments/assets/9b6a71ab-74ef-4163-a21e-65f993092f0e" />


评测结果导出样例：
[模型评测记录_2026-3-19.csv](https://github.com/user-attachments/files/26130976/_2026-3-19.csv)
"时间","Prompt","模型A","模型A输出","模型B","模型B输出","评估结论","场景标签","备注"
"2026/3/19 14:10:17","帮我写一个13字的小故事，要求很恐怖。主角必须有小明。","GLM-4.7","小明躲床底，看见自己睡在床上。","DeepSeek-V3.2","明明的试卷第2页写着：“我也叫小明。”","A更好","指令遵循","字数严格控制，而且内容确实恐怖。"
