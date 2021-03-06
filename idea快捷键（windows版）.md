
## run/debug run

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `Shift` + `F9`           | 等效于点击工具栏的 `Debug` 按钮                              |
| `Shift` + `F10`          | 等效于点击工具栏的 `Run` 按钮                                |
| `alt` + `Shift` + `f9`       | 弹出 `debug`的可选菜单                                       |
| `alt` + `Shift` + `f10`       | 弹出 `run`的可选菜单，也可修改项目配置                                       |
| `ctrl` + `Shift` + `f10`       | `run`已选中工程                                       |
| `double` `ctrl`      | `run` `anything`                                     |
| `Ctrl` + `Shift` + `F9`        | `编译`选中的文件 / 包 / Module                                 |
| `Ctrl` + `F9`            | 编译 Project                                        |
| `F4`     | 编辑源 `（必备）`                                            |
| `Alt` + `U`     | 打开工具栏`Run`                                            |

## debug

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `Ctrl` +`Shift` + `F8`    | 在 Debug 模式下，运行| 查看断点。可通过`Delete`删除断点                           |
| `Alt` + `Shift` + `F7`    | Debug 模式下，下一步，进入当前方法体内，如果方法体还有方法，循环进入 |
| `ctrl` + `f8`             | debug模式下，设置光标当前行为断点，如果当前已经是断点，则去掉 `（必备）`       |
| `Alt` + `F8`              | debug 的状态下，选中对象，弹出可输入计算表达式调试框，查看该输入内容的调试结果 |
| `Shift` + `F7`            | 在 Debug 模式下，智能步入。断点所在行上有多个方法调用，会弹出进入哪个方法 |
| `F7`            | 在 Debug 模式下，进入下一步，若断点是个方法、则`进入当前方法体`内（不循环进入内嵌方法） |
| `F8`            | 在 Debug 模式下，进入下一步，若断点是个方法，`不进入当前方法体`内 |
| `F9`            | 在 Debug 模式下，跳出当前断点 |
| `Alt` + `F9`            | 在 Debug 模式下，运行到光标处 |



## 跳转

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `ctrl` + `alt` + `←` or `→`      | 退回到`上`、`下`一个`操作`的地方 `（必备）`                                       |
| `Ctrl` + `Shift` + `Backspace` | 退回到上次修改的地方 `（必备）`                              |
| `Ctrl` + `Shift` + `B`         | 跳转到类型声明处 `（必备）`                                  |
| `Ctrl` + `B`         | 进入光标所在的方法/变量的接口或是定义处`（必备）` |
| `Ctrl` + `Alt` + `B`           | 在某个调用的方法名上使用会跳到具体的实现处，可以跳过接口 |
| `Ctrl` + `U`         | 前往当前光标所在的方法的父类的方法 / 接口定义 `（必备）` |
| `Ctrl` + `Tab`       | 编辑窗口切换，加`delete`，则是关闭对应选中的窗口 |
| `Alt` + `鼠标点击页面关闭按钮`       | 关闭除当前文件窗口的其他窗口 |
| `Alt` + `↑` or `↓`                           | 当前光标跳转到当前文件的`前`、`后`一个方法名位置 `（必备）`          |
| `Ctrl` + `Alt` + `]` or `[`      | 在打开多个项目的情况下，切换`上`、`下`一个`项目窗口`                                     |
| `Ctrl` + `[` or `]`            | 移动光标到当前所在代码的花括号`开始`、`结束`位置                       |
| `Ctrl` + `Shift` + `[` or `]`        | 选中从光标所在位置到它的`顶部`、`底部`中括号位置 `（必备）`            |
| `Ctrl` + `Alt` + `F7`          | 显示使用的地方。寻找被该类或是变量被调用的地方 |
| `Alt` + `F7`          | 显示使用的地方。寻找被该类或是变量被调用的地方 |
| `Alt` + `←` or `→`       | 切换当前已打开的窗口中的`左`、`右`子视图 `（必备）` |
| `Ctrl` + `End` or `Home`         | 跳到文件`尾`、`头`                                                 |
| `Shift` + `End` or `Home`          | 选中光标到当前行`尾`、`头`位置                                       |
| `Ctrl` + `F3`        | 调转到`所选中的词的下一个引用位置` `（必备）`             |
| `F2` or `Shift` + `F2`           | 跳转到`下一个`、`上一个`高亮错误 或 警告位置               |
| `Ctrl` + `Alt` + `Enter` or `Shift` + `Enter`   | 开始新一行。光标所在`行上`、`行下`空出一行，光标定位到新行位置 `（必备）` |
| `Ctrl` + `Shift` + `J`         | 自动将下一行合并到当前行末尾 `（必备）`                      |
| `Ctrl` + `Shift` + `I`         | 快速查看光标所在的方法 或 类的定义                           |
| `Alt` + `Shift` + `↑` or `↓`  | 移动光标所在`行``向上`、`向下`移动 `（必备）`                |
| `Ctrl` + `Shift` + `↑` or `↓`   | 光标放在`方法`名上，将方法移动到`上`、`下`一个方法前面，调整方法排序 `（必备）` |
| `Ctrl` + `Shift` + `←` or `→`  | 在代码文件上，光标跳转到当前单词 / 中文句的`左`、`右`侧开头位置，同时选中该单词 / 中文句 `（必备）` |
| `F12`    | 回到前一个工具窗口 `（必备）`                                |
| `alt` + `F1` then `enter`    | scroll from source `（必备）`                                |


## 创建相关类
| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `Alt`+`Enter`        | 选中某个接口，`alter+enter`选中`implement interface` ，创建接口实现类           |
| `Ctrl` + `Shift` + `T`         | 对当前类生成单元测试类 `（必备）` |



## 代码重构

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `Ctrl`+`Alt`+`M`        | 提炼函数 `（必备）`            |
| `Ctrl` + `o`             | 选择可重写的方法                                             |
| `Ctrl` + `Shift` + `T`         | 对当前类生成单元测试类 `（必备）` |
| `Ctrl` + `Alt` + `C`              | 重构-快速提取常量                                            |
| `Ctrl` + `Alt` + `F`               | 重构-快速提取成员变量                                        |
| `Ctrl` + `Alt` + `V`               | 重构-快速提取变量                                            |
| `Ctrl` + `Alt` + `T`               | 对选中的代码弹出环绕选项弹出层 `（必备）`                    |
| `Ctrl` + `Shift` + `Alt` + `T`               | 重构`（必备）`                    |
| `F6`           | 先选中类或者包，按`F6`进行移动`（必备）`                    |



## 代码优化

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `Ctrl` + `Alt` + `L`               | `格式化`代码，可以对当前文件和整个包目录使用 `（必备）`        |
| `Tab` or `Shift` + `Tab`          | 缩进 or 取消缩进 `（必备）`                              |
| `Ctrl` + `Shift` + `+` or `-`          | `展开` or `折叠`所有代码 `（必备）`                |
| `Ctrl` + `alt` + `+` or `-`          | `展开` or `折叠`选中代码块 `（必备）`                |
| `Ctrl` + `Alt` + `O`               | 优化导入的类，可以对当前文件和整个包目录使用 `（必备）`      |
| `Ctrl` + `Alt` + `I`               | 光标所在行 或 选中部分进行自动代码缩进       |
| `alt` + `shift` + `I`               | 检查类存在的问题（如waring、spelling）      |


## 修正代码

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `Ctrl` + `J`         | 插入自定义动态代码模板 `（必备）`                        |
| `ctrl` + `shift` + `space`       | 智能代码提示 `（必备）`                                       |
| `ctrl` + `shift` + `enter`       | 自动结束代码，行末自动添加分号 `（必备）`                                     |
| `f2`       | 跳转到下一个高亮错误 或 警告位置 `（必备）`                                        |
| `ctrl` + `f1`        | 在光标所在的错误代码处显示错误信息 `（必备）`            |
| `ctrl` + `,`       | 基础代码补全（原本ctrl+space会被输入法占用） `（必备）`            |
| `Alt` + `Enter`         | 根据光标所在问题，提供快速修复选择，光标放在的位置不同提示的结果也不同 `（必备）` |
| `Ctrl` + `Delete` or `BackSpace`    | 删除光标`后面`、`前面`的单词或是中文句 `（必备）`                  |
| `Ctrl` + `Alt` + `Space`           | 类名自动完成                                                 |
| `Shift` + `F6`           | 对文件 / 文件夹 重命名                                       |
| `Ctrl` + `Shift` + `U`         | 对选中的代码进行`大 / 小`写轮流转换 `（必备）`                 |
| `alt` + `Shift` + `u`         | 对选中的代码进行`驼峰转换`（必备）`                 |
| `Ctrl` + `Shift` + `R`         | 根据输入内容替换对应内容，范围为整个项目 或 指定目录内文件 `（必备）` |
| `Ctrl` + `Shift` + `alt` + `J`       | 可`多行`统一修改选中代码 `（必备）` |
| `Ctrl` + `Shift` + `alt` + `鼠标左击选中` or `alt` + `鼠标拖拽`        | 可选`多行`统一修改选中代码 `（必备）` 



## 代码层次关系

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `ctrl` + `shift` + `alt` + `u`            | 查看继承关系 （extends） （按住alt移动鼠标有放大镜功效） |
| `Ctrl` + `H`             | 显示当前类的层次结构                                         |
| `Ctrl` + `Alt` + `H`               | 调用层次                                                     |
| `Ctrl` + `f12` or `alt` + `7`              | 查看类结构（弹窗） or 打开Structure·查看类结构 |


## 书签

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `f11`         | 设定/取消书签                                                |
| `ctrl` + `f11`         | 设定书签                                                |
| `Shift` + `f11`       | 弹出 `书签` 弹出层                                       |
| `Ctrl` + `1,2,3...9`     | 定位到对应数值的书签位置 `（必备）`                          |
| `Ctrl` + `Shift` + `1,2,3...9` | 快速添加指定数值的书签 `（必备）`                            |


## idea 窗口

| 快捷键           | 介绍                            |
| ---------------- | ------------------------------- |
| `ctrl` + `shift` + `T`     | 打开新terminal窗口 `（必备）`   |
| `alt` + `f12`          | 打开terminal窗口 `（必备）`   |
| `ESC`    | 从工具窗口进入代码文件窗口 `（必备）`                        |
| `Alt` + `1,2,3...9`         | 显示对应数值的选项卡，其中 1 是 Project 用得最多 `（必备）`  |
| `Alt` + `6`         | 查看项目中`todo`  |
| `Ctrl` + `Shift` + `F12`       | 编辑器最大化 `（必备）`                                      |
| `Shift` + `Ctrl` + `A`       | 切割屏幕，弹出框中搜索`split` `（必备）`                                      |
| `Shift` + `Ctrl` + `左右`       | 调整左右窗口左右大小 `（必备）`                                      |
| `Shift` + `Ctrl` + `上下`       | 调整左右窗口上下大小 `（必备）`                                      |
| `Shift` + `Ctrl` + `"`       | 最大化或者最小化窗口 `（必备）`                                      |


## 查找替换

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `double` `shift`     | 弹出 `Search Everywhere` 弹出层。可以`文件名 + :行号` 查询        |
| `Ctrl` + `G`             | 在当前文件跳转到指定行处                                     |
| `Ctrl` + `E`             | 显示最近打开的文件记录列表 `（必备）`                        |
| `Alt` + `Home`           | 定位 / 显示到当前文件的 `Navigation Bar`                     |
| `Ctrl` + `Shift` + `F7`        | `高亮显示`所有该选中文本，按Esc高亮消失 `（必备）`             |
| `F3`     | 在查找模式下，定位到下一个匹配处                             |
| `Ctrl` + `Shift` + `N`         | 通过文件名定位 / 打开文件 / 目录，打开目录需要在输入的内容后面多加一个正斜杠 `（必备）` |
| `Ctrl` + `Shift` + `F`        | 根据输入内容查找整个项目 或 指定目录内文件 `（必备）`        |
| `Shift` + `F3`           | 在查找模式下，查找匹配上一个                                 |
| `Alt` + `F3`             | 选中文本，逐个往下查找相同文本，并高亮显示                   |
| `Ctrl` + `Shift` + `A`         | 查找动作 / 设置                                              |
| `Alt` + `Shift` + `C`        | 查看最近操作项目的`变化情况列表`                               |
| `Alt` + `F1`               | 显示当前文件选择目标弹出层，弹出层中有很多目标可以进行选择 `（必备）` |
| `Ctrl` + `Shift` + `W`         | `递进式取消`选择代码块。可选中光标所在的单词或段落，连续按会在原有选中的基础上再扩展取消选中范围 `（必备）` |
| `Ctrl` + `Alt` + `Home`            | 弹出跟当前文件`有关联`的文件弹出层                             |



## 文件比较

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `项目文件比较`         | 项目工程中选中两个文件，`ctrl` + `D` 进行比较                     |
| `文件与剪切板内容比较`  | 复制某个文件到剪切板，打开需要对比的文件，右击选择`Compare with Clipboard`          |
| `本地文件与控制版本比较`       | Select a modified file anywhere in the `Version Control` tool window.  `ctrl`+`D` |


## 复制粘贴

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `Ctrl` + `Shift` + `C`         | 复制当前文件`磁盘路径`到剪贴板 `（必备）`                      |
| `Ctrl` + `Shift` + `Alt` + `C` | 复制当前文件`项目路径`到剪切板          |
| `Ctrl` + `Shift` + `V`         | 弹出缓存的最近拷贝的内容管理器弹出层                         |
| `Ctrl` + `Shift` + `Z`         | 取消撤销 `（必备）`                                          |



## 提示

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `Ctrl` + `Q`             | 光标所在的`变量 / 类名 / 方法名`等上面（也可以在提示补充的时候按），`显示文档内容` |
| `Alt` + `Q`              | 弹出一个提示，显示`当前类`的声明 / 上下文信息                  |
| `Ctrl` + `P`             | `方法参数`提示显示 `（必备）`                                  |
| `Shift` + `F4`           | 对当前打开的文件，使用新Windows窗口打开，旧窗口保留          |


## 版本控制

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `Ctrl` + `alt` + `z`       | revert 选中文件 git change           |
| `Alt` + \`         | 显示版本控制常用操作菜单弹出层 `（必备）` |      
| `Alt` + `Shift` + `N`        | 选择 / 添加 task `（必备）`                                  |



## datagrip

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `Ctrl` + `F6`       | modify table      |
| `F4`       | open console      |
| `shift` + `F4`       | 打开表结构      |


## maven

| 快捷键           | 介绍                                                     |
| ---------------- | -------------------------------------------------------- |
| `Ctrl` + `Alt` + `R`           | quick run maven goal                |


## 其他

| 快捷键               | 介绍                                                         |
| -------------------- | ------------------------------------------------------------ |
| Ctrl + I             | 选择可继承的方法                                             |
| Ctrl + Alt + J               | 弹出模板选择窗口，将选定的代码加入动态模板中                 |
| Ctrl + Alt + Y               | 同步、刷新                                                   |




## 插件

## Translation
| 快捷键               | 介绍                                                         |
| -------------------- | ------------------------------------------------------------ |
| `Ctrl` + `shift` + `Y`             | 翻译选中单词                                             |
| `Ctrl` + `shift` + `X`              | 翻译并替换选中单词                |


