# 北京航空航天大学学位论文LaTeX模板

> **本模板仅为个人兴趣之作，非官方模板。**

本项目为北京航空航天大学学位论文模板BUAAThesis，包含Word模板和LaTeX模板(基于[ctexbook](https://ctan.org/pkg/ctex))。模板按照2015年8月版《研究生手册》制定，适用于理工类博士、硕士、专业硕士学位论文（中文）。


## 下载地址

+ [GitHub](https://github.com/CheckBoxStudio): [https://github.com/CheckBoxStudio/BUAAThesis/releases](https://github.com/CheckBoxStudio/BUAAThesis/releases)

## 文件列表

```
BUAAThesis
 |- buaa.cls              // LaTeX宏模板文件
 |- buaa_mac.cls          // LaTeX宏模板文件(For Mac with XeLaTeX)
 |- GBT7714-2005.bst      // 国标参考文献BibTeX样式文件2005版
 |- GBT7714-2015.bst      // 国标参考文献BibTeX样式文件2015版
 |- logo-buaa.eps         // 论文封皮北航字样
 |- head-doctor.eps       // 论文封皮北博士学位论文标题(华文行楷字体替代解决方案)
 |- head-master.eps       // 论文封皮北学硕学位论文标题(华文行楷字体替代解决方案)
 |- head-professional.eps // 论文封皮北专硕学位论文标题(华文行楷字体替代解决方案)
 |- Template.tex          // LaTeX模板
 |- tex/*.tex             // LaTeX模板样例中的独立章节
 |- ref.bib               // LaTeX模板中的参考文献Bib文件
 |- Template.docx         // Word模板
 |- .gitignore            // Git忽略规则
 +- ReadMe.md             // 本文件
```

## 模板使用

+ Word: 直接在其上进行修改编写，请记得预先备份；
+ LaTeX: 参看LaTeX模板示例template.tex及相应插入章节tex/*.tex；
+ Mac: Mac系统请使用buaa_mac.cls并使用XeLaTeX编译。

## 关于图书馆查重

+ By [Qiao Junfeng](https://github.com/qiaojunfeng), 2018/11/22

    实际经验表明，使用此模板经XeLaTeX编译生成的pdf，图书馆查重时未遇到乱码问题。

    我的环境：Manjaro Linux + TeX Live 2018 + TeXstudio 2.12.10。

## 建议及问题反馈

+ E-mail: [weiqm@buaa.edu.cn](weiqm@buaa.edu.cn)
+ GitHub: [https://github.com/CheckBoxStudio/BUAAThesis/issues](https://github.com/CheckBoxStudio/BUAAThesis/issues)

## 我的环境

+ Windows 10 64bits
+ TeXStudio 2.12.4
+ MiKTeX 2.9
+ CTeX 2017-07-18

## 致谢

感谢[Haixing Hu](https://github.com/Haixing-Hu)提供的2005版参考文献著录BibTeX样式[GBT7714-2005](https://github.com/Haixing-Hu/GBT7714-2005-BibTeX-Style)及[Zeping Lee](https://github.com/zepinglee)提供的2015版参考文献著录BibTeX样式[GBT7714-2015](https://github.com/zepinglee/gbt7714-bibtex-style)，为本项目LaTeX模板的形成提供了很大的帮助。感谢[BwCai](https://github.com/BwCai)提供的Mac编译环境。

***

By [WeiQM](https://weiquanmao.github.io/).
