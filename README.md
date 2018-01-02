# Typora-i18n-zh

这儿是Emphasia的Typora的简体中文的翻译资源。

如果你对我的这版翻译有任何意见或建议，欢迎在此项目提issue，也可访问[Typora-i18n](https://github.com/typora/Typora-i18n)或直接向[作者 hi@typora.io](mailto:hi@typora.io)反馈。

如果你想独立完成一份简中的版本或参与其他语言的翻译，请访问[Typora-i18n](https://github.com/typora/Typora-i18n)。

### 注意

- Typora是一款跨平台的软件，支持macOS、Windows和Linux系统，对于不同的系统乃至不同的版本，需要结合实际来确定翻译以优化用户的使用体验。

  此版本翻译基于Windows，翻译主要参考Office等软件以及个人的理解，对于不同地域、不同系统、不同版本可能会存在有不合适的情况，请谅解。

- 因为限制，无法测试翻译的实际显示情况，很多地方只能靠对照和猜，文本没对齐与标点等情况我也只能等下个版本才能发现与修正。

- 注释支持`/* 一段注释 */`格式，而**不**支持`// 注释`格式。

### 结构

- `Menu.strings`：菜单栏。以macOS为主要应用环境，因此需按照[localize-mainmenu](https://github.com/martnst/localize-mainmenu)规范。
- `Menu-electron.strings`：菜单栏。若[localize-mainmenu](https://github.com/martnst/localize-mainmenu)中的翻译在Windows/Linux上与macOS上不同，将合适的翻译添加至此处。
- `Panel.strings`：设置面板与对话框。
- `Front.strings`：主界面。

### 分支

- `master`：此分支下为这版翻译的所有资源，供作者选用。
- `fix`：此分支下为最基本的翻译，主要用于修正[Typora-i18n](https://github.com/typora/Typora-i18n)中简体中文部分的基本错误。

