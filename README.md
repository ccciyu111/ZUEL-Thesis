# 中南财经政法大学本科毕业论文LaTeX模板
本模板适用于中南财经政法大学**本科**毕业论文撰写。参考了教务部对本科毕业论文的[基本规范](http://jwc.zuel.edu.cn/2021/0303/c10880a264631/page.htm)（试行）。

***在使用前，请与您的指导老师协商好确认可以用pdf格式的文件进行论文审阅，并仔细阅读下面的使用说明。本模板并非官方模板，使用本模板的一切后果由您自行承担。***
-----------

## 下载模板
可以在本页面直接下载，如遇网络问题，也可在Gitee上下载。
下载完压缩包后，推荐上传至[Overleaf平台](https://www.overleaf.com/project/)，设置使用 XeLaTeX 编译器开始写作。


## 使用模板
### 填写基本信息
在`main.tex`中，填写您的论文题目、姓名、学号、学院、专业、班级等基本信息。虽然模板会根据信息自动更新封面页、作者声明和标题页，仍然请您再次检查以确认无误。本模板使用系统的当前时间作为论文的完成时间，您也可以手动更改。
### 填写论文主要内容
#### 文字内容
在`content`文件夹中有引言、摘要、正文、结论、后记等示例文件，将示例中的文字替换为您的论文内容。
#### 图表内容
在`content`文件夹中的`chapter1.tex`和`chapter2.tex`有图表的使用演示，根据演示创建您自己的图表并在正文中引用它们。

图片最好放在`imgs`文件夹中。

表格创建推荐使用网站[Tables Generator](https://www.tablesgenerator.com/)，可根据表格生成相应的LaTeX代码。注意：本模板自定义了`\tablecaption`命令来生成表格标题。
#### 公式
LaTeX的数学公式编辑是其一大特色。由于内容较多，请您自行学习并使用（很容易学会）。在`content\chapter2.tex`中给出了一个示例。

##### 推荐网站：
* [在线公式编辑器](https://latexlive.com/)
* [语法手册](http://www.uinio.com/Math/LaTex/)
#### 脚注
本模板采取pifont的带圈脚注解决方案，缺陷是最多支持10个脚注，对于绝大多数情况应当足够使用。
#### 参考文献
在`citations.bib`中填写您的参考文献（BibTex格式），模板会按照中英文分开显示，并根据作者、年份排序。
#### 附录
本模板自定义了`\appdx`命令以生成附录标题。见`content\appendices.tex`。
#### 代码
在`content`文件夹中的`appendices.tex`有代码的使用演示，将代码文件放入`code`文件夹，并根据演示在附录中显示代码。
#### 超链接
见`content\chapter1.tex`。
#### 目录
在`main.tex`中调节行距因子以获得美观的目录。从目录可直接跳转到对应的章节。
### 编译
对于Overleaf，只需点击页面中的`compile`按钮；如果本地编译，则需多次运行。

## 反馈与贡献
本模板是作者在撰写毕业论文时深感word排版痛苦，自学LaTeX在几天内完成的。由于作者水平、时间、精力都有限，本模板一定还有众多不完善的地方，虽然作者有心修正，奈何势单力薄，所以您有任何问题，都可以在[讨论区](https://github.com/ToryDeng/ZUEL-Thesis/discussions)里提出，但作者不保证及时回答。也欢迎新的贡献者能参与维护该项目！~~（以便作者划水）~~

## 软件许可证
* 中南财经政法大学校徽校名图片（`cover_imgs/badge.png`、`cover_imgs/name.png` ）的版权归中南财经政法大学所有。
* `biblatex-gb7714-2015` 样式文件使用 [LPPL](https://www.latex-project.org/lppl.txt) 授权。
* 其它部分使用 [GNU General Public License v3.0](LICENSE) 授权。

