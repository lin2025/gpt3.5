<div align="center">

[![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)](#lingpt)

<h1 align="center">LinGPT</h1>

<p align="center">A GPT-3.5 Webpage with Just a Single HTML File</p>

<p align="center">只有一个html文件的GPT-3.5聊天网页</p>

<p align="center">
  <a href="https://github.com/lin2025/gpt3.5/"><img height="22" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" alt="Github"></a>
  <a href="https://gitee.com/lin2025/gpt3.5/"><img height="22" src="https://img.shields.io/badge/Gitee-C71D23?style=for-the-badge&logo=gitee&logoColor=white" alt="Gitee"></a>
</p>

[Demo](https://lin2025.github.io/gpt3.5/) • 
  [Download](https://github.com/lin2025/gpt3.5/archive/refs/heads/main.zip) • 
  [网盘下载](https://lin2025.github.io/#gpt3.5-code)

Give a Star 🌟 if you like it.

[![](https://lin2025.github.io/img/other-0705.gif)](#lingpt)

</div>

:point_right: [![English](https://img.shields.io/badge/English-Readme-success)](#lingpt-2)

## LinGPT

 - 简介：仅有一个`.html`文件的GPT，轻量，便捷，零门槛
 - 在线：不到500K的静态网页，托管在 Github / Gitee 非常流畅
 - 下载：下载到电脑，打开html文件即可使用，像打开一张图片一样简单
 - 上传：可上传至托管平台/主机/服务器，支持所有免费的静态网页托管平台
 - 接口：使用Open AI官方API，同时可自定义API。支持免魔法的第三方API
 - 模型：同ChatGPT `gpt-3.5-turbo`。目前仅支持GPT-3.5的两种模型 
 - 密钥：需自备 API Key。过几天增加轮询Key的功能
 - 数据：仅存储于浏览器本地缓存，支持导出、导入和删除


## 在线体验

 :globe_with_meridians:线路 Github: [https://lin2025.github.io/gpt3.5/](https://lin2025.github.io/gpt3.5/)

 :cn:线路 Gitee: [https://lin2025.gitee.io/gpt3.5/](https://lin2025.gitee.io/gpt3.5/)

 :cn:多种下载方式（含网盘）: [https://lin2025.gitee.io/#gpt3.5-code](https://lin2025.gitee.io/#gpt3.5-code)


## 功能

> GPT生成回复采用一次性返回，非流式响应，互交体验会降低，但也有优点 - 不会中断、内容多时响应快

 - **新功能**: 多对话管理、全自动保存、支持创建副本、多标签页数据同步、可导出 (备份/迁移/分享)、可导入 (还原对话)
 
 - **新功能**: 支持浏览器本地存储，支持数据同步、导入、导出、删除、统计等操作
 
 - Smart max_tokens（全自动调节max_tokens）
 
 - API Key、API余额/有效期查询、自定义接口网址、自定义API请求参数（model、max_tokens、temperature、top_p、presence_penalty、frequency_penalty）

 - 支持Markdown（代码块、高亮代码、显示网络图片、显示表格、文章排版)

 - 系统提示词、上下文记忆模式、token统计、一键复制、自动解析OpenAI 错误代码、功能帮助

 - 清空、撤销、重问，并支持快捷键

 - 语言支持简体中文和英语、支持多种方式设置头像（可上传头像）、支持样式设置（字体大小、微信样式的时间、消息时间、区分多轮对话）

 - 可导出单轮聊天记录、全部聊天记录和操作记录，格式为Markdown，支持导出`.md`和`.txt`


## 特点

> 使用 记事本 或 文本编辑.app 即可改代码 修改教程已写在代码里 无需懂技术  
> v6.07 版本开始 多数个性化设置可直接在界面中完成

 - 无门槛 人人都能DIY 小白也能利用免费的静态托管平台轻松建站
 - 支持隐形系统提示词 一分钟即可轻松定制不同用途的AI工具
 - 适合日常轻中度使用场景 多个重要功能正在研究中...


## 更新   
- **7月05日** **v7.05** 1) **新增**本地存储及数据管理功能; 2) **新增**多对话、自动保存、创建副本、数据同步、导出分享、导入还原对话等功能；3) **修复**Windows系统的兼容性问题(滚动条、下拉菜单样式错误)；4) 优化UI。
- **6月15日** 新增**上传头像**功能。**Smart max_tokens**升级全新算法，并加入计算错误后**自动重发**的功能。调整css兼容性。
- **6月12日** 新增**Smart max_tokens**功能，全自动调节`max_tokens`。 修复问题：提示词允许保存空白（之前不小心给限制了）。
- **6月9日** 新增OpenAI报错代码；修复些问题：头像使用相对路径引发的问题、加载时气泡框塌缩的问题、部分浏览器不支持12px以下的字体的问题。
- **6月7日** **v6.07**几乎全新的版本，变化比较大，功能升级，体验升级，适用的场景更多了，也很稳定，不再报错。

<b><details><summary>6月7日之前的更新记录</summary></b>

- **5月17日** 变化不大，小更新：添加`<!DOCTYPE html>`，调整不规范的样式；修补Markdown插件`Marked.js`会过滤掉一些聊天内容的BUG；给气泡框添加小箭头。
- **5月14日** 更新内容：优化加载速度&稳定性；修复频闪；优化布局&体验&增加空间；聊天框失去焦点时可缩小；修改撤销&重问的逻辑；修正发送失败的消息会写入上下文的bug；撤销&重问可实时更新Tokens；按钮使用SVG图标；使用随机问候语验证API-key；代码优化&修正命名&增加可读性...
- **5月09日** **一键复制** **clipboard** 更新内容：支持一键复制、使用SVG替换已经失效的Logo、优化代码、修复小bug。
- **5月06日** **Markdown** **Highlight** 重要更新，支持 Markdown + Highlight 代码高亮。调试了很久，效果还不错。近期会尝试增加些实用功能，应用场景可以从轻度上升到中度。
- **4月28日** **Add English comments.**
- **4月27日** **新增功能**-**查询OpenAI账号余额** 检测API-Key后，点击[Tokens]查询API账号余额，使用OpenAI官方接口，返回数据包含登记的名字、是否绑卡、总额度、余额、有效期等。代码基于以下两位大佬的项目进行调整实现：@ClarenceDan的[openai-billing](https://github.com/ClarenceDan/openai-billing)、@herobrine19的[openai-billing](https://github.com/herobrine19/openai-billing)，已详细注释，安全透明，数据无泄漏风险。
- **4月26日** 给“检测中“和“发送中“这两按钮状态添加动态效果；页面上不再显示API-Key明码；修正些小错误。
- **4月23日** **重要修复 bug fixes** 修复近期多个国家IP无法访问BootCDN而导致网页报错的情况（无法加载Vue与Axios），已添加Unpkg CDN线路，BootCDN挂掉的时候会自动切换到Unpkg。
- **4月16日** 修改PC端的快捷键，改为回车<kbd>Enter</kbd>发送，并支持多种换行方式。适配中文输入习惯，中文输入状态下，一次回车**确认但不发送**，二次回车**才会发送**。
- ...

</details>

---

###

[![English](https://img.shields.io/badge/English-Readme-success)](#lingpt-2)

## LinGPT
 - LinGPT is a lightweight single-page chat application that can be deployed statically, with no need for a server.
 - Can be uploaded to any static website hosting platform like GitHub and provides a very smooth browsing experience.
 - Download and open the <kbd>index.html</kbd> file on your computer, input your OpenAI API Key to get started.
 - This code uses the OpenAI API and supports third-party APIs. 
 - Currently, only the GPT-3.5 model (ChatGPT `gpt-3.5-turbo`) is supported as the GPT-4 model cannot be tested. 
 - An OpenAI API key is required. 
 - User data is stored only in the browser's local cache, supporting export, import, and deletion. 


## Demo

[https://lin2025.github.io/gpt3.5/](https://lin2025.github.io/gpt3.5/)


## Features

> This code does not use streaming response, GPT will generate the complete response text at once.

 - **New Features**: Multiple chats management, automatic saving, copy creation, data synchronization, export (for backup / sharing), import (restore chat data).
 - **New Features**: Support for browser local storage, with operations including data synchronization, import, export, deletion, and statistics.
 - Smart max_tokens (Automatically adjusts the max_tokens)
 - API key, OpenAI API balance inquiry, custom API endpoint, custom API requests (model, max_tokens, temperature, top_p, presence_penalty, frequency_penalty.).
 - Markdown support (code block, syntax highlighting, displaying images, displaying tables, article formatting, etc.).
 - system prompt, context mode, token statistics, one-click copy, automatic parsing of OpenAI error codes, function help.
 - Undo, Retry, Clear Context, and supporting keyboard shortcuts.
 - Supports English and Chinese-Simplified, custom avatars (supports Upload Avatar), custom style (font size, WeChat-style time format, message time, distinguishing multi-turn contexts, etc.).
 - Single-round chat history, all chat history, and operation history can be exported in Markdown format, supporting export as `.md` and `.txt`.


## Updates   

- **July 5th** **v7.05** 1) Added local storage and data management. 2) Added: multiple chats, automatic saving, copy creation, data synchronization, chat export and sharing, and chat import and restoration. 3) Bug fixes for Windows compatibility  (scrollbar, dropdown menu styling errors). 4) Optimized UI.
- **June 15th** New Feature: **Upload Avatar**, Upgraded the **Smart max_tokens** algorithm with the feature to automatically resend requests in case of errors. Adjusted CSS compatibility.
- **June 12th** The new **Smart max_tokens** feature was added, which automatically adjusts the max_tokens parameter. Bug fix: Fix the issue that the prompt allows saving blank space.
- **June 9th** Added explanation for OpenAI error codes; Fixed some issues related to:relative path avatar;  style during loading;  some browsers not supporting fonts below 12px. 
- **June 7th** **v6.07** This is an almost brand new version with significant changes, upgraded features and improved user experience. It is applicable to more scenarios and is also very stable. It has been tested for two weeks without any errors.

[Updates before June 7th](https://github.com/lin2025/gpt3.5#更新)
