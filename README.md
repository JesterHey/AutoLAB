# auto-labsafe-exam 
本程序用于自动完成湖大实验室安全考试答题  
推荐在虚拟环境中运行本程序  
## 环境配置  
1. 确保安装Google Chrome浏览器和对应版本的驱动chromedriver  
   [谷歌浏览器下载](https://www.google.com/intl/zh-CN/chrome/)  
   [谷歌浏览器驱动下载(请下载对应浏览器版本的驱动版本)](https://googlechromelabs.github.io/chrome-for-testing/)  
   下载完成后，将chromedriver配置到相应位置，具体教程如下：  
   [谷歌浏览器驱动chromedriver配置教程](https://www.cnblogs.com/lfri/p/10542797.html)
2. 所需Python库
   * selenium
   * lxml
       
   在电脑(或者你的虚拟环境)的终端依次输入  
`pip install selenium`  
`pip install lxml`

## 使用方法
1. 下载本项目的压缩包并解压在合适位置
2. 在您的IDE中打开此项目文件并运行**main.py**,您应当会被要求输入信息
 ![输入示意图](https://github.com/JesterHey/img_file/blob/main/%E6%88%AA%E5%B1%8F2023-10-25%2016.46.18.png)
   
4. 完成后，您只需稍作等待，在程序执行到最后一页时，您就可以提交试卷了
## 演示视频  



https://github.com/JesterHey/auto-labsafe-exam/assets/144512889/a0c289a9-c39a-4bb9-9500-6b722a2a5667



## 关于题库
网站似乎对于不同专业的考试抽取题目的比例不同，如有自行构建题库的需要，您可以修改**题库抓取.py**中的相应参数进行抓取  

## 注意事项  
1. 尽管经过多次提取，本项目的题库仍然有极小部分缺陷，不能保证每次执行都是100分，但经过统计，使用本程序所得到的平均分在95以上,您也可以选择*自己完成*剩余的少量无答案题目  
2. 使用本程序即代表您愿意承担使用此程序带来的相应后果

## 致谢  
本程序的答案点击部分受到[HunterJ-Lin](https://github.com/HunterJ-Lin/AutoAnswer2XMU)的项目启发。
