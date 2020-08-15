# mac os 配置记录


1. 安装typora，一款不错的markdown编辑器 https://www.typora.io

2. 安装搜狗输入法，https://pinyin.sogou.com/mac/

3. 安装google浏览器， https://www.google.cn/intl/zh-CN/chrome/thank-you.html?statcb=0&installdataindex=empty&defaultbrowser=0 ；同步账号

4. *系统偏好设置* -> *触控板* -> *轻点来点按* 

   <img src="./1.png" alt="1" style="zoom: 25%;" />

5. *系统偏好设置* -> *辅助功能* -> *指针控制* -> *触控板选项*

   <img src="./2.png" alt="2" style="zoom:25%;" />

6. 安装sublime, http://www.sublimetext.com/

7. 解决github缓慢问题

   ```shell
   # GitHub Start
   52.74.223.119 github.com
   192.30.253.119 gist.github.com
   54.169.195.247 api.github.com
   185.199.111.153 assets-cdn.github.com
   151.101.76.133 raw.githubusercontent.com
   151.101.108.133 user-images.githubusercontent.com
   151.101.76.133 gist.githubusercontent.com
   151.101.76.133 cloud.githubusercontent.com
   151.101.76.133 camo.githubusercontent.com
   151.101.76.133 avatars0.githubusercontent.com
   151.101.76.133 avatars1.githubusercontent.com
   151.101.76.133 avatars2.githubusercontent.com
   151.101.76.133 avatars3.githubusercontent.com
   151.101.76.133 avatars4.githubusercontent.com
   151.101.76.133 avatars5.githubusercontent.com
   151.101.76.133 avatars6.githubusercontent.com
   151.101.76.133 avatars7.githubusercontent.com
   151.101.76.133 avatars8.githubusercontent.com
   # GitHub End
   
   sudo vim /etc/hosts
   sudo dscacheutil -flushcache # 刷新dns缓存 
   ```

8. 安装ohmyzsh

   ```shell
   ssh-keygen  # 一路回车
   cat ~/.ssh/id_rsa.pub  # 配置到github账号ssh keys
   git clone git@github.com:ohmyzsh/ohmyzsh.git
   sh ~/ohmyzsh/tools/install.sh
   ```

9. 安装brew

   ```
      /bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"   
      brew install wget
      brew install aria2  # 下载工具 
   ```

10. Apple Store 安装SSH工具termius 

11. Apple Store 安装网易云音乐

12. Anaconda

    ```shell
    https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/
    Anaconda3-5.3.1-MacOSX-x86_64.sh
    chmod a+x Anaconda3-5.3.1-MacOSX-x86_64.sh  # 权限修改
    ./Anaconda3-5.3.1-MacOSX-x86_64.sh
    vim ~/.zshrc # 添加 source .bash_profile
    ```

13. 安装wps，https://mac.wps.cn/

14. 安装微信，https://mac.weixin.qq.com/?t=mac&lang=zh_CN

15. 安装pycharm教育版 ，常用功能基本具备 https://www.jetbrains.com/edu-products/download/#section=pycharm-edu

16. 安装vimplus https://github.com/chxuan/vimplus

17. 安装office2019 https://zhuanlan.zhihu.com/p/96530082

18. 在线屏幕监测 https://screen.51240.com/#welcome

