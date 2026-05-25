# 准备篇 · 阅读准备：把工具备齐

> 阅读目标：完成一台准备好的电脑，所有工具账号就位

---

这一章就是一份清单。注册账号、装工具、测试网络。

很多人在第一章就卡住，原因很简单：工具没准备好。打开 Lovable 发现网页加载不出来，或者第九章才发现没有 GitHub 账号。花 30 分钟现在搞定，后面会顺很多。

但你不用一开始就把所有账号都注册完。为了不让准备工作变成新的门槛，我把它分成两个版本。

```text
【最低准备版：先跑通第一章】

□ 网络能打开 Lovable
□ 有一个能注册账号的邮箱或 Google 账号
□ 能在浏览器里保存你的网页 URL

只做到这三项，就可以先进入第一章。
```

```text
【完整推荐版：后面会更顺】

□ GitHub：第九章部署会用
□ Vercel：第九章部署会用
□ Cursor：第十一章工具梯度会用
□ Claude：第五章写 PRD、第十三章互审会用
□ Supabase：第十六章数据库会用
```

---

## 网络环境

本书用到的工具（Lovable、Cursor、GitHub、Vercel、Claude、Supabase）都在海外。如果你在中国大陆，需要稳定的网络工具。

网络环境因地区而异。确认方法很简单：打开本书会用到的工具官网，至少 Lovable、GitHub、Vercel 能正常加载。

---

## 必备账号

直接用 Google 邮箱登录以下账号。大多数都有免费或试用方案，但套餐会变化，正式使用前以官网为准。

**Lovable**（lovable.dev）  
第一章就要用。用 Google 账号或邮箱注册。

**GitHub**（github.com）  
代码托管。你的项目代码存在这里。Lovable、Vercel、Cursor 都需要关联 GitHub。用邮箱注册，选免费计划。

**Vercel**（vercel.com）  
部署平台。把你做好的产品发布到互联网。注册时直接用 GitHub 登录，之后部署会自动关联。

**Claude**（claude.ai）  
用来互审代码、规划方案、写文档。邮箱注册。

**Supabase**（supabase.com）  
数据库服务。第十六章才用到，现在注册的话用 GitHub 账号最方便。

五个账号打开浏览器标签逐个注册，顺利的话半小时内可以搞定。

---

## 必备工具

账号注册完，接下来装两个软件到你的电脑上。

### Cursor

**下载**：cursor.com

代码编辑器，想象成运行在你电脑上的 Lovable。也能通过对话生成代码，但更灵活。

下载对应系统版本（Mac 或 Windows），安装打开。第一次打开登录或注册，通常会有免费或试用额度，具体以官网为准。

打开后右侧有聊天面板。在那里打字，Cursor 帮你写代码。第六章会先简单试一下，第十一章会专门展开什么时候该从 Lovable 升级到 Cursor。

### Codex

**访问**：以 OpenAI 官网和 ChatGPT 内的最新入口为准。截至 2026 年 5 月，Codex 常见入口包括 ChatGPT 里的 Codex、Codex CLI，以及 IDE 插件。

Codex 是 OpenAI 的 AI 编程工具。你可以把它当成一个能读代码、改代码、跑命令的编程助手。它既能在云端委托任务，也能接入终端或 IDE。具体入口、套餐和可用地区变化很快，以 OpenAI 官方最新说明为准。

前面几章用 Lovable 和 Cursor 够了。Codex 先确认能访问就行，用到时再深入。

### Claude Code（选装）

终端编程工具。能理解整个项目的所有文件，跨文件修改。只有 ClawChat 项目用到。

如果你看到“终端安装”就有点害怕，完全可以先跳过。前十章不需要 Claude Code，第十一章讲工具梯度时再回来装也来得及。现在装有两种方式：

**用 AI 帮你装**

打开 Cursor，输入“帮我安装 Claude Code，并按 Anthropic 官方文档核对最新步骤”。它会告诉你步骤。最适合新手。

**自己在终端装**

Claude Code 的安装方式变化较快，下面只是截至 2026 年 5 月常见的参考方式。正式安装前，请以 Anthropic 官方文档为准。

打开终端（Mac 搜“Terminal”），输入：
```
npm install -g @anthropic-ai/claude-code
```
等它跑完，在项目目录里输入 `claude` 回车，看到欢迎界面就成功了。如果这条命令失效，不要硬扛，直接去 Anthropic 官方文档查最新安装方式。

装完用 Claude 账号登录。

---

## 检查清单

逐条确认，全部打勾就可以进第一章。

```text
【阅读准备检查清单】

□ google.com 能正常打开
□ Lovable（lovable.dev）已注册
□ GitHub（github.com）已注册
□ Vercel（vercel.com）已注册
□ Claude（claude.ai）已注册
□ Supabase（supabase.com）已注册
□ Cursor（cursor.com）已下载安装
□ Codex 已确认能访问，或决定之后再开通
□ Claude Code 决定好了（现在装，或之后再装）
```

---

## 要点小结

最低准备版能跑通第一章；完整推荐版能让后面的部署、互审、数据库更顺。Codex 和 Claude Code 不着急，用到再装。重要的是别让账号问题在后面章节里打断你。

清单全部打勾了，就可以进第一章了。

---

下一章：15 分钟发布你的第一个网页到全世界。
