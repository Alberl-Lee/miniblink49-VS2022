# 简介
miniblink是基于chromium的浏览器控件，也可以用来开发软件（类似于electron），更多信息请见官网http://miniblink.net 
而blinkUI是基于blink的UI界面库，只保留UI相关的部分，去掉了所有浏览器的功能，单纯只用来开发UI界面
用web(js+HTML+CSS)写界面，C++写逻辑。既有web的开发效率，又有C++的运行速度

由于blink耦合性太高、而且无关UI的代码太多，所以我选择从miniblink去裁剪和提取UI代码，并且去掉了nodejs，改用C++来开发逻辑，这样才能有C++的运行速度

----

# 特性 

- 极致小巧的体积
- C++，C#，Delphi等语言调用
- 支持Windows xp、npapi
- HTML5支持，对各种前端库友好，比如vue等

----

# 未来计划的特性 

- 跨PC平台
- 跨移动端平台

----

# 联系方式

Q群956223415

----

# 致谢 Thanks

特别感谢好基友weolar，他是miniblink、kdgui的作者
我在金山毒霸的时候，给他打过一段时间的辅助，给kdgui写了一套更方便更强大的控件库，把开发效率提高了4倍
（之前开发一个完整的项目需要1个月，使用了控件库之后只需要1周）
现在继续给他打辅助，把miniblink的UI部分提取出来