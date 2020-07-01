# md

## 软件启动

    （全局操作）
    cmd ->code
    ctrl-shift-p 进入命令面板(搜索和执行命令)
    ctrl p 搜索文件
    切换页面：ctrl pgdn pgup
    移动行：alt+up/down
    代码格式化：shift + alt +f
    选中代码行：shift + 鼠标左键
    ctrl+home文章首页
    ctrl+/单行注释  取消单行注释(按下ctrl不放，再按k + u)
    多行注释alt shift a
    
    ctrl j 打开和关闭终端
    多光标：ctrl alt up/down
    ctrl g：行跳转
    ctrl k + ctrl T 调背景颜色
对于左边图标消失，右击左边方框，勾选所需要或者缺失的。
查看md文件预览ctrl+shift+v

## md使用

***

是分割线

  查看图片并用相对路径，必须打开整个文件

公式：
    $ ^是上面 _下面 多个用{} $

     文字作为角标，文字放在\mbox{}文字模式中
    {\mbox{\me文本}}    
    角标位置不明显时，可以强制改变脚本大小
    y_N, y_{_N}, y_{_{\scrptstyle N}【依次更为分隔】    
    分式\frac{分子}{分母}    
    根式
     ：二次根式命令：\sqrt{表达式}
     ：n次根式命令：\sqrt[n]{表达式}

## 求和与积分

- 求和命令：\sum_{k=1}^n表达式（求和项紧随其后,下同）  
- 积分命令：\int_a^b表达式  
  > 例如：无穷级数$\sum_{k=1}^\infty\frac{x^n}{n!}$显示为：∑∞k=1xnn! 可以化为积分$\int_0^\infty e^x$显示为∫∞0ex，也即是：∑∞0xnn!=∫∞0ex  
- 改变上下限位置的命令：\limits(强制上下限在上下侧) 和 \nolimits(强制上下限在左右侧)  
  > 例如： $\sum\limits_{k=1}^n$ 和 $\sum\nolimits_{k=1}^n$  

显示结果为：∑k=1n 和 ∑nk=1  
∫n=0∞x和∫∞n=0x  
显示结果为：∫n=0∞xn和∫∞n=0xn  
