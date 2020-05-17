# -
华南理工大学本科生毕业论文模板


halo大家好，这是一个latex写论文的傻瓜版本

单双页页眉已经设置好了！~这个真的很麻烦


1. 封面设置：main.tex 文件，本帅哥已经设置好了大部分东西，只要像word文档中一样输入标题等信息就可以了！

2. 摘要部分： 在文件夹chapter，文件 0_abstract 中， 中英文摘要已经分好了，在相应位置写就好！

3. 目录部分： 目录是自动生成的，只需要添加章节标题就可以。

正文中这样添加标题就好
\chapter{}   %章节标题

\section{}   %二级标题

\subsection{}  %三级标题

章节设置： 目前只有第一章与第二章，自行添加其它章节

第二章中有插入公式，图片，表格的说明。

4. 参考文献

用latex引用参考文献真的很过瘾。完全不用担心不规范。

步骤： （1）几乎所有的参考文献都可以在google scholars中找到引用

打开google scholars, 搜索文章， 在 【 被引用次数：****】 左边，有一个 大大的【“ 】,鼠标放上去，会看到引用
点进去。 最下一行的第一个 BibTeX， 比如以t-SNE搜索，第一篇文章，点开BibTeX后就会出现：

@article{maaten2008visualizing,
  title={Visualizing data using t-SNE},
  author={Maaten, Laurens van der and Hinton, Geoffrey},
  journal={Journal of machine learning research},
  volume={9},
  number={Nov},
  pages={2579--2605},
  year={2008}
}

将它粘贴到文件夹 misc 中的 ref.bib 文件

之后在正文中，引用格式为： \cite{maaten2008visualizing}

比如你提到了t-SNE这个词，你想给它加上角标，那么你就：


t-SNE\cite{maaten2008visualizing}     %%复制到正文中看看效果


5. 好像没什么要说的了。本人学业繁忙，可能也不会经常来维护这个版本。希望可爱的师弟师妹能用latex写论文。
因为真的好好看！！囧rz，一个颜控的推荐。

