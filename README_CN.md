# 编程键盘
专业编程键盘


### 1
40年前，电脑键盘大概长这样：  
![computer keyboard](https://programming-keyboard.oss-cn-shanghai.aliyuncs.com/images/appearance_of_typical_keyboard.jpeg "appearance of typical keyboard")

40年后，一直到现在，电脑键盘基本上还是长这样，没多大变化。  
对于我们年轻人来说，从最初我们开始学键盘时它就是这样，而我们也习惯了它这个样子。  
我们对它太熟悉了以至于我们可能会忽略掉一些问题。比如，估计很多人都不会在意在我们的键盘上，有很多符号都是跟另外一个符号共用一个按键的。  
“@“和”2“共用一个按键，”*“和”8“共用一个按键，”?“和”/“共用一个按键等等；当你按这些按键时，默认输入的是下面那个符号，你如果想输入上面那一个符号，你得同时按着”shift“键。  
有些人可能不经常用到那些符号，所以也并不感觉有多不方便；但是对于程序员来说，那些符号每一个都很常用，他们一天可能得按“shift“键上千次，增加的工作量还是挺大的。  
如果你的编程语言是PHP，那么我敢肯定，你一天编程下来，肯定打“$“符打得崩溃。  
![php programming](https://programming-keyboard.oss-cn-shanghai.aliyuncs.com/images/php_codes.png "php codes")


### 2
另外还有个问题，如果你的母语不是英语，那么你使用键盘的时候肯定得经常切换输入法，特别是如果你是一个程序员。而切换中英文输入法的按键在Windows里面默认的是“shift“键。（其实如果你的母语不是英语，你多半也不知道”shift“就是切换的意思，对于你来说它就是一个”shift“键）。当你想输入上面的符号，就得去按着”shift“键，一不小心按错了，你就把中英文输入法给切换掉了；这一点挺烦人的。  
![shift mode](https://programming-keyboard.oss-cn-shanghai.aliyuncs.com/images/input_mode_shift.png "shift mode")

所以，我们为什么不把那些需要“shift“键才能输入的符号放到一个独立的按键上呢？这样的话，当我们输入那些符号的时候，我们就不需要再按着“shift”按键了；就像下图这样：  
![above characters](https://programming-keyboard.oss-cn-shanghai.aliyuncs.com/design/characters_above.png "above characters")

如果我们不需要按“shift“键，也就不会有输入法切换问题，特别是也可以让程序员省事很多。  


### 3
还有一点，为提高我们的输入效率，IDE或者其他类型软件都会给我们提供很多快捷键，最常用的快捷键莫过于Ctrl+c 和 Ctrl+v；这些快捷键的使用频率这么高，我们为什么不把它独立成一个按键来实现这些功能呢？其实实现这些根本没有什么技术上的难度；如果我们按一个按键就可以实现这些功能，谁还愿意去按两个按键呢？  
![ctrl c v](https://programming-keyboard.oss-cn-shanghai.aliyuncs.com/images/ctrl_c_v.jpg "ctrl c v") 

其实2键快捷键还好，最要命的是3键甚至是4键快捷键，比如：“ctrl+alt+del” or “alt+shift+esc” or “ctrl+shift+alt+j”。   
那么最常用的一些快捷键组合，我们都可以把他们独立成一个按键，这样我们的快捷键使用起来会更加便捷，就像下图这样：  
![shortcut combinations](https://programming-keyboard.oss-cn-shanghai.aliyuncs.com/design/regular_shortcut_combination.png "shortcut combinations")

你觉得这个主意这么样？  
反正我觉得程序员挺需要这些的。  
普通使用者也需要啊，毕竟谁能离得了Ctrl+c 和 Ctrl+v呢？  


### 4
完整的设计如下图所示：  
![keyboard layout](https://programming-keyboard.oss-cn-shanghai.aliyuncs.com/design/draft_design.png "keyboard layout")  

下面是渲染图：   
![typical orange style](https://programming-keyboard.oss-cn-shanghai.aliyuncs.com/design/typical_orange.png "typical orange")  
![classic black style](https://programming-keyboard.oss-cn-shanghai.aliyuncs.com/design/classic_black.png "classic black")  

如果你不认可这个设计也没关系，你可以看一下设计图，这个设计并没有改变太多原有的键盘布局，你仍然可以按照你原来的习惯来使用这个键盘。  

zhulibin410@163.com  