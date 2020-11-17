<h1 align="center">
  易班自动打卡(20201117更新)
  <br>
</h1>
<p align="center">
<img src="https://cdn.looyeagee.cn/github/yiban/license.svg"/>
<img src="https://cdn.looyeagee.cn/github/yiban/platform.svg"/>
<img src="https://cdn.looyeagee.cn/github/yiban/python.svg"/>
</p>


## 👀简介

长沙理工大学易班疫情一键上报今日体温自动打卡程序。

现在已经搭建长沙理工大学专属自动打卡自助网站：https://yiban.looyeagee.cn/

对原理感兴趣的话，建议看看抓包过程视频：https://www.bilibili.com/video/BV1a741117hQ/

博客文章地址：https://looyeagee.cn/software/yiban/

## :sparkles: 使用说明

我将易班的相关接口封装成了一个类，打卡主程序是main.py，请详细查看注释含有`FIXME`的部分修改成自己的内容后再运行。

Linux/Windows环境下，克隆本仓库后转到目录下执行


```shell
# 创建虚拟环境
python3 -m venv venv

# Linux进入虚拟环境
source ./venv/bin/activate

# 使用豆瓣源安装必要依赖
pip3 install -r requirements.txt -i https://pypi.douban.com/simple

# 启动打卡
python3 main.py
```


