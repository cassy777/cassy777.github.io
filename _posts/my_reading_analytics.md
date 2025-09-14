---
##整体框架：my_reading_analytics/
|--data/
|      reading_data.csv
|--src/
|      analyze_reading.py
|--output/
---

##1.创建文件夹
---
git clone https://github.com/用户名/仓库名.git;/
---
此步用于链接github and VScode/
---

##2.在git bash中创建文件夹
---
>>cd my_reading_analytics/导航到此目录下
>>git init/
>>mkdir -p data src output/导航目录
>>---

##3.手动输入data
---
csv
data book reading_minutes
...
---

##4.写脚本，配置pandas环境
---
4.1在vscode中打开终端git bash,编写脚本，试运行，缺少pandas包
---
4.2由于我的路径中包含非ASCII字符，缺少编译依赖，所以我使用miniconda来帮助我安装pandas包
---
4.3打开Anaconda Promot终端，激活环境,并为git bash进行初始化（链接canda and git bash）
---
conda activate base
---
conda init bash
---
4.4导航到目录
---
cd ~/my_reading_analytics //注意空格
---
##little tips:
1.conda是管理python环境的利器
---
2.cd .. :进入上级命令
---
3.pwd:打印出当前的绝对路径
---
