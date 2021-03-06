# NJU-Thesis

　　本项目提供了一个用于排版南京大学学位论文的LaTeX模板。该模板基于校友[Haixing-Hu的模板](https://github.com/Haixing-Hu/nju-thesis)，源模板侧重博士毕业论文。本项目的模板修改为更适合本科/硕士学位的毕业论文格式和风格，可根据文档注释说明，将本模板修改为硕士或博士学位论文模板。  
  
## 使用说明:
* 默认Windows系统下，**安装[ctex](http://www.ctex.org/CTeXDownload/)完整版**。Mac,Linux操作系统需按照sample.tex中的注释说明，修改字体等参数。已给出样例sample.tex，编辑修改该文件即可。
* **必须使用XeLaTeX**。建议使用TeXworks编辑，选择**XeLaTeX+MakeIndex+BibTex**编译运行。WinEdt需要使用**UTF-8**编码打开.tex文件，并且使用XeLaTeX编译。
* 切换本科生、研究生、博士生论文模版，需修改.tex文件中\documentclass[参数]
* 使用bibtex文献管理，用编辑器编辑sample.bib文件即可。或使用[JabRef](http://www.jabref.org/)打开。

## 文件说明:
|文件(夹)|说明|
|-|-|
|sample.tex | 示例文档，可作为学位论文的基本模板|
|sample.bib | 示例文档的参考文献数据库|
|njuthesis.cls | 模板类文件|
|njuthesis.cfg | 模板配置文件|
|njulogo.eps | 南京大学校徽图片|
|njuname.eps | 南京大学校名图片|
|gbt7714-2005.bst | 符合国标GB/T 7714-2005 的参考文献样式文件|
|figures/ | 示例文档图片目录|
