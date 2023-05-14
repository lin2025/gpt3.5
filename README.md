# GPT3.5 one-page web


## 更新 Updates
> 0514 - ....学的越多，改的越多，过几天还有大更新，布局会改变，功能会增加...
- **5月14日** 更新内容：优化加载速度&稳定性；修复频闪；优化布局&体验&增加空间；聊天框失去焦点时可缩小；修改撤销&重问的逻辑；修正发送失败的消息会写入上下文的bug；撤销&重问可实时更新Tokens；按钮使用SVG图标；使用随机问候语验证API-key；代码优化&修正命名&增加可读性...
- **5月09日** **一键复制** **clipboard** 更新内容：支持一键复制、使用SVG替换已经失效的Logo、优化代码、修复小bug。
- **5月06日** **Markdown** **Highlight** 重要更新，支持 Markdown + Highlight 代码高亮。调试了很久，效果还不错。近期会尝试增加些实用功能，应用场景可以从轻度上升到中度。
- **4月28日** **Add English comments.**
- **4月27日** **新增功能**-**查询OpenAI账号余额** 检测API-Key后，点击[Tokens]查询API账号余额，使用OpenAI官方接口，返回数据包含登记的名字、是否绑卡、总额度、余额、有效期等。代码基于以下两位大佬的项目进行调整实现：@ClarenceDan的[openai-billing](https://github.com/ClarenceDan/openai-billing)、@herobrine19的[openai-billing](https://github.com/herobrine19/openai-billing)，已详细注释，安全透明，数据无泄漏风险。
- **4月26日** 给“检测中“和“发送中“这两按钮状态添加动态效果；页面上不再显示API-Key明码；修正些小错误。
- **4月23日** **重要修复 bug fixes** 修复近期多个国家IP无法访问BootCDN而导致网页报错的情况（无法加载Vue与Axios），已添加Unpkg CDN线路，BootCDN挂掉的时候会自动切换到Unpkg。
- **4月16日** 修改PC端的快捷键，改为回车<kbd>Enter</kbd>发送，并支持多种换行方式。适配中文输入习惯，中文输入状态下，一次回车**确认但不发送**，二次回车**才会发送**。
- ...

![](https://lin2025.github.io/img/test0514.png)
![](https://lin2025.github.io/img/other-gpt3.5.gif)
![](https://lin2025.github.io/img/test.jpg)


## 简介
 零门槛 10秒就能搞定的GPT3.5 <kbd>gpt-3.5-turbo</kbd> 

 静态网页 无依赖 无需部署 **仅一个html文件** 打开即用 超级简单

 **在线体验：** [https://lin2025.gitee.io/gpt3.5/](https://lin2025.gitee.io/gpt3.5/) 或 [https://lin2025.github.io/gpt3.5/](https://lin2025.github.io/gpt3.5/)

 **下载方式汇总（含网盘）：** [https://lin2025.gitee.io/#gpt3.5-code](https://lin2025.gitee.io/#gpt3.5-code)


## :globe_with_meridians:
A ChatGPT web page is a lightweight single-page chat application that can be deployed statically, with no need for a server.

Download and open the <kbd>index.html</kbd> file, input your OpenAI API-Key to get started. Functions include: Check OpenAI API balances, System prompts, Support for Markdown, Context, Adjustable temperature settings, Undo, Retry, Clear context, Token count, and Export chat history.

> <kbd>先检测API</kbd>_:Check API first_    <kbd><<检测</kbd>_:Check API-key_    <kbd>发送</kbd>_:Send_    <kbd><<写入指令</kbd>_:Save system prompt_    <kbd>Tokens</kbd>_:Token count_    <kbd>Tokens点击查API余额</kbd>_:(Click)_ _Check OpenAI API balances_    <kbd>清空</kbd>_:Clear context_    <kbd>撤销</kbd>_:Undo_    <kbd>重问</kbd>_:Retry_    <kbd>说明</kbd>_:Help_    <kbd>导出对话</kbd>_:Export chat history_  _..., others are in the code comments._ 


## 功能
 需使用自己的API-Key / 查询OpenAI账号余额 / 上下文记忆 / token统计 / 撤销问答 / 重新回答 / 清空记忆
 / 可调创造力·温度temperature / 可设置指令·系统提示词system / 可导出聊天记录与操作记录
 / 对话框自适应高度
 / 电脑端按回车<kbd>Enter</kbd>发送 支持多种换行方式<kbd>Shift | Ctrl | Cmd</kbd>+<kbd>Enter</kbd> / 支持Markdown 代码高亮 表格

> 回复是一次返回，非Stream流式，不存在中断的情况


## 特点
 无门槛 / 便捷 / 一秒复制一个 / 一分钟轻松定制成AI小工具 / 不用担心挤不上官网 / 无需登录 / 无泄漏风险 / 适合轻中度使用场景

> 使用 记事本 或 文本编辑.app 即可改代码 修改教程已写在代码里 无需懂技术 人人都会改


## 缺点
 使用ChatGPT官方接口 **国内需使用魔法**


## 欢迎交流
 **B站**@[林同学不姓林](https://space.bilibili.com/3493262545389917) **抖音**@[林同学不姓林](https://www.douyin.com/user/MS4wLjABAAAAVBMwb4AQWZt3xkbgvVS4FYCuQ2xzHCU9LgSX4vJz_n76JK62kQGEfHjYjzrOCHs7)

 **提示词导航·分享** [https://lin2025.gitee.io/#zhiling](https://lin2025.gitee.io/#zhiling)

 **林同学的小站（域名跳转Gitee）** [LinTongXue.com](http://LinTongXue.com)

