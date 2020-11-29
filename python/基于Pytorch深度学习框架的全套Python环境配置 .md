## 基于Pytorch深度学习框架的全套Python环境配置 windows10+pycharm+cuda10.0+cuDNN7.3+anaconda+python3.6

现在研究生搞科研，都在学深度学习AI，我也是其中的一员。感觉这东西很飘渺，学到的东西不多，就觉得前期就安装python开发环境遇到不少坑，学到了配置环境。记录下来，算是一种收获。我也都是参照CSDN上给位博主的文章。到哪一步附上相应的博客。不打算在操作一遍了。

------



1. #### **首先介绍我用到了那些软件或库。**

   python3.6 + anaconda + cuda 10.0 + cuDNN 7.3 + Pycharm 

2. #### 、安装

   安装是有先后顺序的，有些顺序是可以稍微调整。

   

   1. 安装pycharm

      参考地址：

      https://www.runoob.com/w3cnote/pycharm-windows-install.html

      建议安装到第四步，不安装python解释器。因为我们要使用conda进行不同版本的python环境管理更为方便，可靠，每个环境需要的解释器版本可能不同，第三方库版本可能不同，使用conda为不同项目创建不同环境更为有效。当然可以安装解释器，没什么影响。对于轻微强迫的我来说，不希望电脑上存在无用的安装。

   2. 安装anaconda 我安装anaconda 是适用于python3.6.5的，因为安装anaconda时会同时为你安装某个版本的解释器，这个可以选择，对于后面使用conda 创建自己的python环境没有关系。简单来说conda是一个python环境管理器，为我们管理所需要的各种第三方库。

      参考地址：

      https://blog.csdn.net/ITLearnHall/article/details/81708148

      里面有conda使用命令，基础的必须掌握。另外也有为pycharm和解释器的连接。做到这步我们就可以写自己的程序了。

   3. 安装cuda 10.0 + cuDNN 7.3 

      因为深度学习对于训练时间有很大需求，现在大都有GPU，使用GPU加速训练相当重要，所以我们使用CUDA,用于使用GPU训练模型，并使用cuDNN加速。

      我这里使用了cuda 10.0，其兼容性好，我也尝试过使用最新的cuda ,装了一次没有成功果断放弃。

      参考地址：

      https://blog.csdn.net/Bushka_/article/details/105396989

      ------

      https://blog.csdn.net/weixin_43593330/article/details/103098728?utm_medium=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-1.channel_param&depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-1.channel_param

      对于新手来说，不建议自定义安装，总之有几个必不可少的步骤，安装vs;将cuDNN 解压后的文件复制到相应的文件，是文件里的,不是真个文件的复制。添加环境变量。

   4. 安装pytorch

      安装pytorch可以安装基于cuda的，也可以不使用，如果我们要使用GPU就必须安装cuda的。要不然不能使用。

      参考地址：

      https://www.cnblogs.com/jaysonteng/p/12544405.html

3. #### 大功告成！

   参考了很多博客，有对有错，有繁有简，算一个综述，将不少内容汇聚到一起。因为太懒了，不想在重做一遍。

