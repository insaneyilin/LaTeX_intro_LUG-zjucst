# LaTeX Introduction for LUG-CSTZJU
=========
这是为[LUG-CSTZJU](https://github.com/LUG-CSTZJU/)内部成员准备的一次LaTeX入门介绍演讲的相关文件。

latex_tutorial_lug-cstzju.tex 是介绍文档的源文件，slides_latex_lug-cstzju.tex 是slides的源文件。

latex_tutorial_lug-cstzju.pdf 和 slides_latex_lug-cstzju.pdf 分别是对应的pdf文件。其余pdf文件为图片资源。

## 编译tex文件

Linux下安装Tex Live 2014 <http://www.tug.org/texlive/>，参考[LaTeX中文排版（使用XeTeX）](http://linux-wiki.cn/wiki/zh-hans/LaTeX中文排版（使用XeTeX）)进行中文字体设置，使用xelatex命令编译源文件：

```
$ xelatex latex_tutorial_lug-cstzju.tex
$ xelatex slides_latex_lug-cstzju.tex
```