# 关于demo文件夹的说明

demo_main_using_standalone.tex展示的是基于standalone的方案，该方案可以将图片文件生成独立的pdf文件，然后再插入到main文件中。其编译命令必须加上`-shell-escape`选项。

```shell
	latexmk -pdf -shell-escape demo_main_using_standalone
```

demo_main_using_tikzinclude.tex展示的是基于tikzinclude的方案，tikzinclude适用于同一个图片具有多个不同的版本的场景。