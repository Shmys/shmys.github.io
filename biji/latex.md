# LaTeX

> 系统：Win10 64位

## 环境

- TeX Live
- Sumatra PDF
- VS Code
  - LaTeX Workshop
    - 使用 xelatex 编译

## 获取字体名称

- cd <一个目录>
- fc-list :lang=zh >> 123.txt

这种方式可以查看已安装的字体，从而获取字体的名称。为了防止命令行下产生乱码，所以要将结果写到文件里。

但这种方法只能看见`C:\Windows\Fonts`目录下的中文字体，如果字体没有安装到这里，是无法直接使用字体名称的。

## “强力”安装字体

右击字体文件，**为所有用户安装**。

这样就能出现在`C:\Windows\Fonts`目录下了。

## 反向搜索

以后再写
