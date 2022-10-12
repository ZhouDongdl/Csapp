# Csapp
作为一名跨考到计算机的学生，很早就听说过csapp的大名了，然而由于自己懒狗的本质拖了好久也没看。9月份开学后，身边人都在努力学习，我觉得我也要学点什么，于是想起了暑假买的那一本csapp，遂决定在研一上学期争取看完这本著作，并完成相关的课后习题和实验。  
这篇文章仅仅是对学习过程中的一个记录，想到哪写到哪，所以可能看起来比较乱（不过自己能理解就好  

[课程主页](http://csapp.cs.cmu.edu/3e/home.html)  
[课题练习答案](https://dreamanddead.github.io/CSAPP-3e-Solutions/)  
## 实验前准备  
由于所有实验均为linux环境下进行的，需安装Linux系统或者docker，这里选择VMware+Ubuntu的方式  
安装好Ubuntu后，在终端输入以下命令  
```
sudo apt-get install build-essential  
sudo apt-get install gcc-multilib  
sudo apt-get install gdb
```  
注意可能有一些包装不上，这时候可以执行以下代码，更新apt，然后再执行上述命令即可  
```  
sudo apt -f install  
sudo apt update
```
## 实验进度  
Lab 1  
