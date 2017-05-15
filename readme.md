## 编程题答题说明
点击编程题进入答题页面后，您可以看到导航栏处三个标签，分别为：**题目说明**，**提交作业**，**运行结果**
### 题目说明
题目说明标签内包含：
![All text](http://static.zybuluo.com/zhongjianxin/u6p1ant46n7jri1891kg4kvn/image.png)
![Alt text](http://static.zybuluo.com/zhongjianxin/xixspyics0snvp7psbv61mss/image.png)
![Alt text](http://static.zybuluo.com/zhongjianxin/9ist8gnc8iz1zwyb9krll9jx/exam-run.png)
NOTE：编程题模板库是便于用户的答题操作，根据题目的难易程度可能提供或者不提供
### 提交作业
提交作业标签内包含：
**编程题模板库地址**，**github仓库地址**，**github仓库分支**
![Alt text](http://static.zybuluo.com/zhongjianxin/m7oobulo91885g0650t4b2gf/exam-system-instruction-ui.png)
用户在本地做完每道编程题后在此标签内提交编程题的github地址
### 运行结果
- 用户在提交题目后，系统会自行进行处理
![Alt text](http://static.zybuluo.com/zhongjianxin/du7fov4cwwteoxnaql6muzka/image.png)
- 若结果正确，则下一题解锁，用户继续完成下一题目
![Alt text](http://static.zybuluo.com/zhongjianxin/05zq2lez577wggikzln8dl5j/image.png)
- 若错误，请继续完成本题目，直至正确或答题超时
![Alt text](http://static.zybuluo.com/zhongjianxin/cysqrq9e6b9l6rijc15jagm9/image.png)
  
## 编程题答题注意事项
- 每道题设有答题时间期限，超时后用户将失去答题资格
- 因题目难度不同，**答题流程也不太相同**
- 因题目难度不同，**题目运行结果时间不定**，请耐心等待
- 因题目难度不同，**编程题模板库可能不提供**

# 以下为本题内容
## 题目要求
- 请在开始答题后 `7` 天内完成,逾期将无法再答题
#### 题目描述
根据如下顺序完成题目：
- 请新建一个github账户
- 请初始化一个github仓库
- 请在该库内新建一个名为`HELLOWORLD.md`的文件，并保证测试通过
## 答题流程
1. 请用户仔细阅读题目要求和题目描述
2. 使用以下命令初始化git（如果不会使用git和github，请先学习参考资料的内容）
```
git init
```
3. 使用以下命令设置github远程仓库地址 (url代表你自己的新的github地址)
```
 git remote add origin url
```
4. 请使用**git提交(commit)**并**上传(push)**，之后将此github仓库地址(用户自建的) eg:（https://github.com/username/repo） 填入到提交地址一栏 
5. 获取分支
6. 提交
7. 等待结果
## 考察要点
- github仓库的使用
- git基础
## 编程题模板库地址
本题不存在编程题模板库地址
## 参考资料
1. [Git for Windows](https://github.com/doggy8088/Learn-Git-in-30-days/blob/master/zh-tw/02.md)
2. [try git](https://try.github.io/levels/1/challenges/1)
3. [Git 参考手册](http://gitref.org/zh/index.html)
4. [github用法](https://guides.github.com/activities/hello-world/)
## 答题流程
- 请用户仔细阅读题目要求和题目描述
- 在命令行中使用以下命令在用户本地任意目录下clone此题目库
```
git clone repo_of_this_template
```
NOTE：如果提示git命令未找到请先阅读参考资料
- 用任意编辑器打开clone下来的文件夹，内部会存在两个文件夹
```
spec  //测试文件夹
src   //源文件
```
`请在src文件下的main.js文件内实现main函数`
- 完成函数后，使用以下命令设置github远程仓库地址 (my_url代表你自己的新的github地址)
```
 git remote set-url origin my_url
```
- 请使用**git提交(commit)**并**上传(push)**，之后将此github仓库地址(用户自建的) eg:（https://github.com/username/repo） 填入到提交地址一栏 
- 获取分支
- 提交
- 等待结果
## 如何本地运行
首先初次下载完需要安装依赖：

```
  npm install
```
然后才能执行测试：

```
npm test
```
可以通过测试来检测本地代码是否完成作业要求，测试通过即可提交到github，把git库地址填到答题页面，并提交表单。
