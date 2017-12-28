# learn-scrapy
ubuntu安装scrapy
第一步：切换到root用户，sudo su
再来安装。
遇到的问题：1.pip无法使用（错误描述：no module names ‘pip’）.
无法解决问题，重新安装ubuntu，python版本为2.7（之前为3.5）,利用apt install python-pip，生效（之前命令不生效）。（此时pip版本为8.1，后面发现版本过低，需要跟新 pip install --upgrade pip，最后跟新为9.0.1）

第二步：安装完pip后，开始进行scrapy的安装。
sudo apt-get install python-dev
sudo apt-get install libevent-dev
sudo apt-get install libssl-dev 
安装完这三个之后（虽然也不知道为啥要先安装这三个）
pip install scrapy
就安装完成了。
scrapy version，版本为1.4.0
