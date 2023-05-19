# Git 练习题
这里是一些关于 Git 的小练习，主要用于学习 Git 的基本操作，以及Github(其他平台大同小异啦)的简单使用。各位可以积极贡献

## Git基本操作

### 1. git clone

大多数人从Github上下载代码是直接 `Download Zip` 的，这当然是可行的，因为非常之方便。但如果要维护一个自己的Git项目，或者想要方便地与一个开源项目保持同步更新，`Download Zip`显然不是一个优雅地操作。
这个时候就需要用到`git clone`命令出场了。

`git clone`命令是最基本的`git`命令之一，它的作用就像它名字解释的那样，clone(克隆)。那么是从哪里克隆到哪里呢？一般来说，是从托管代码的服务器上（例如GitHub）克隆到你自己的本地机器上（比如你现在正在使用的这台电脑）
该命令最基本的使用方法为：
```
git clone <repo url>
```
> **小练习：Clone本仓库到本地**

### 2. git commit

### 3. git push

### 4. git pull



## GitHub的使用

### 1. 将别人的食物（Others' repo）叉（Fork）到自己碗里（Your Own Repo）

Fork的作用是将一个公开的仓库复制一份到自己的仓库中，它主要用在两个场景中：
1. 你想在一个开源项目上按照自己的想法进行修改和使用，由于该项目的所有者并不是你，所以需要把该开源项目Fork到自己的仓库中进行修改。
2. 你想要对一个开源项目做出贡献，也就是提一个PR(Pull Request)。那么也需要先把该项目Fork到自己的仓库中进行修改，至于提PR(Pull Request)的操作，在后文中将有对应的讲解和练习。

Fork操作非常简单，主要分为两步：
1. 打开你想要Fork的仓库，比如本仓库https://github.com/XJTU-IPDC/Git_Practice
2. 点击右上角的Fork按钮即可。（如果没登录Github账号，在这一步需要登录）

> **小练习：Fork本仓库到自己的repo中**

### 2. 在Fork来的仓库上进行修改

### 3. 提交PR(Pull Request)

### 4. 审核(review)并合并(merge)PR
