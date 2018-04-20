# Word Count

## 项目简介

Word Count 1.0 能够统计纯英文 txt 文件的字符数、单词数和行数

### 基本用法
 1. 打开WordCount.exe文件得到运行窗口![](https://i.imgur.com/0dX4HNk.png)
 2. 输入[参量名]和[文件名]：wc.exe [parameter][file_name]之后得到结果
 
(注：文件应为纯英文文本文件，文本文件与应用程序文件应放在同一目录下)
### 功能列表
1. -c : char count(数字符数)
2. -w : word count（数单词数）
3. -s : sentence count（数句子数）
4. -a : annotation count（数代码注释行数）
5. 输入的文件名错误或文件不存在时：输出EXEC failure
6. 输入的[parameter]不存在时：输出There is no function called "   "

#文件列表

#例程运行&结果



- 输入test1（empty）文件，内容空
![](https://i.imgur.com/lBMivyH.png)
![](https://i.imgur.com/q7HOLD4.png)

- 输入纯英文文本（文本选自动画短片 小蜘蛛Lucas 台词）
![](https://i.imgur.com/P6ZtpEx.png)
![](https://i.imgur.com/VL0ej7C.png)
- 输入的[parameter]不存在（不存在这一功能）
![](https://i.imgur.com/CXDj9Vh.png)

- 输入的文件不存在或文件名错误时（打不开文件）
![](https://i.imgur.com/EoFTxc0.png)
- 附加功能输入的文本内容为代码，计数代码注释行（输入文件内容为，分支程序：附加功能1.0的文本）
![](https://i.imgur.com/OrIgVrm.png)
![](https://i.imgur.com/wFXfbIa.png)
![](https://i.imgur.com/N4ML0fU.png)
