### Sublime Text 3初始化需要安装的插件包！
这里记录了一些新安装Sublime Text 3时需要安装的插件！

**在安装任何插件以前需要先安装Package Concrol。通过它才可以安装各种插件。**

---
**1. Emmet**

　　使用仿CSS选择器的语法来快速开发HTML和CSS，熟练使用Emmet语法可以提交HTML和CSS代码的书写效率。

**2. JsFormat**

　　在JavaScript文件中可以直接使用Ctrl+Alt+F（默认）来进行自动JS排版，对一些凌乱的JS进行整理。

**3. jQuery**

　　安装此插件后可以提示jQuery的方法。

**4. LESS、Less2Css**

　　动态层叠样式表语言，在LESS文件中嵌套式编写CSS，通过编译转化为CSS文件，极大的提高了CSS编写效率，使代码更加的清晰，使重用、修改更加的方便快捷。
　　在Sublime Text中使用Less2Css需要lessc的支持，推荐的方法是Node.js，简单便捷，安装完Node.js后在`cmd`中输出`npm install less -g`即可，安装结束后输入`lessc`不报错表示安装成功，Sublime Text中使用`Alt+s`（默认）即可将LESS转换为CSS。

**5. Markdown Preview**

　　提供一套Markdown语言的解析方法，主要用于Markdown代码的本地预览，减少与服务器的传递，在本地编写正确后再上传。其他一些功能个人很少用到。
　　安装完该插件后需要自定义设置预览快捷键，可以打开系统默认浏览器预览内容，将以下代码添加在Preferences->Key Bindings - User中：
`{"keys": ["alt+m"], "command": "markdown_preview", "args": { "target": "browser"}}`

**6. Markdown Light**

　　目前为止，本人非常喜欢的一套Markdown标签高亮插件，尤其是它的‘Dark’主题，非常美观！