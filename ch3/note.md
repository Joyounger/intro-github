####创建一个pull request  
![图3-10](https://raw.githubusercontent.com/Joyounger/intro-github/master/ch3/3-10.PNG 'Create pull request')
Open a pull request界面提供了讲述将更改纳入到其他项目的原因的机会.  
默认标题是最近提交的提交信息的第一行,如果你已经在试图合并的分支上进行一次以上的提交,描述中将有一个包含所有提交信息第一行的无序列表,这些提交信息是pull request的一部分  

![图3-11](https://raw.githubusercontent.com/Joyounger/intro-github/master/ch3/3-11.PNG '成功创建的一个pull request')
请注意现在是在原始项目pragmaticlearning下,我们想创建一个pull request将我们的工作拉入这一项目中,所以pull request是该项目的一部分,
不属于我们的fork的副本.

![图3-17](https://raw.githubusercontent.com/Joyounger/intro-github/master/ch3/3-17.PNG '原始项目提交历史')
项目中有两个原始提交,"create new_file.md"提交是在我的副本上进行的;当我们合并pull request时,会产生一个新的合并提交,将所做工作合并到原始项目.
每当你合并一个pull request时,将创建这些合并提交中的一个.它们真的很有用,因为提交消息(可以在合并一个pull request时对其进行编辑)允许记录为什么
决定包含该项工作.如果想放弃所有通过pull request合并的工作,可以请求一个开发人员"revert the merge commit for that pull requset".


####重命名或移动一个文件  
![图3-22](https://raw.githubusercontent.com/Joyounger/intro-github/master/ch3/3-22.PNG '编辑文件的文件夹或文件名')
假设要将构建的new_file.md文件移动到一个documentation文件夹,并重命名为chapter_1.md  
转向页面上方有文件名的文本框,输入document/chapter_1.md.在输入到/时GitHub马上将前面文本断开作为新文件夹显示  
如果想把文件放在上一级目录,在框中输入../filename  


#####创建一个空文件夹  
1 当需要创建一个空文件夹时,在该文件夹下创建一个名为.gitkeep的空文件  


#####重命名一个文件夹  
github上不能直接重命名一个文件夹,只能将该文件夹下的文件名逐个修改  