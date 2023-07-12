# Auto-GPT：体验未来的个人全能AI助手


# 更新日志

可以关注此代码空间，在更新发布时及时获得通知

## 20230607：
升级Auto-GPT版本（0.3.1至0.4.0），Auto-GPT现在可以从文档文件中读取文本，并支持PDF，doc，docx，CSV，HTML，TeX等！



![Auto-GPT](https://1024-staging-1258723534.cos.ap-guangzhou.myqcloud.com/assets/AutoGPT.png)

> Auto-GPT 是一个真正自主的人工智能代理，建立在 OpenAI 的 GPT-4 或 GPT-3.5 API 之上，通过将目标划分为子任务并在自我维持的循环中利用互联网和其他工具，以自然语言实现目标。
> 
>为实现其目标，AutoGPT 可以浏览网页、在你的计算机上写入文件、创建和执行代码，以及使用记忆和从自身经验中学习的知识。

[官方仓库地址：https://github.com/Significant-Gravitas/Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT)


Auto-GPT 出现并火热已持续一阵子了，看了很多篇文章讲 Auto-GP T的变革式创新，是下一阶段的AI发展方向。

但很多人受限于 OpenAI API Key、代理和较为复杂的 Auto-GPT 部署安装流程，至今仍然没体验过 Auto-GPT，也包括之前的我。

恰逢了解到 Auto-GPT 新增了 plugins 插件功能，可以“外挂”插件替代/增强 Auto-GPT 本身的部分功能。以及 1024Code 平台的特性及便利之处，所以我开发了一个插件，提供了 3.5模型 API 以及无需代理翻墙使用的搜索服务（替换了 Google 搜索）。

所以现在我们可以直接在 1024Code 上体验 Auto-GPT。

# 在 1024Code 上部署和使用 Auto-GPT

1、Fork 当前这个 Auto-GPT 代码空间

- 确保 Auto-GPT 的 plugins 目录存在引入了开发的插件的 zip 包

2、点击运行按钮，在 Console 里给 Auto-GPT 下达命令，和 Auto-GPT 交互

# 简单示例

1、让 Auto-GPT 使用PyGame创建贪吃蛇游戏

![1](https://1024-staging-1258723534.cos.ap-guangzhou.myqcloud.com/assets/1.png)


2、观察它的返回，适当修正，让它不要把问题复杂化/在死循环到问题里

![2](https://1024-staging-1258723534.cos.ap-guangzhou.myqcloud.com/assets/2.png)

3、持续交互，得到你想要的代码

![3](https://1024-staging-1258723534.cos.ap-guangzhou.myqcloud.com/assets/3.png)

PS：回复 y -10 让它自己持续跑多个命令，加速执行

4、运行代码

![gif](https://1024-staging-1258723534.cos.ap-guangzhou.myqcloud.com/assets/%E8%BF%90%E8%A1%8C%E4%BB%A3%E7%A0%81GIF.gif)

将 Auto-GPT 生成的复制到PyGame代码空间运行，运行成功，但遗憾的是“贪吃蛇”无法移动



# 额外说明

正如 Auto-GPT 官方在仓库里写到的：

> Auto-GPT is an experimental open-source application showcasing the capabilities of the GPT-4 language model. This program, driven by GPT-4, chains together LLM "thoughts", to autonomously achieve whatever goal you set.
>
> Auto-GPT是一个实验性的开源应用程序，展示了GPT-4语言模型的功能。这个程序由GPT-4驱动，将LLM“思想”链接在一起，以自主实现您设定的任何目标。

Auto-GPT 基于 3.5、甚至 4，现在仍然是一个实验，暂时无法实质的帮助我们完成完整任务，生成高可用的内容，甚至卡顿、bug都是常有的。

但我们可以，在和目前 Auto-GPT 的交互中可以感受到 AI 自主思考、分析指令、使用工具，并循环自我矫正的过程。提前体验未来的个人全能AI助手。

Auto-GPT 就像是智能手机时代的安卓，结合 LangChain ，不仅能支持GPT 3.5、GPT 4，Claude、MOSS等模型它都能支持，Auto-GPT 仍处于快速迭代状态，大家不妨持续关注它，再结合 AI 技术的飞速发展，期待个人全能AI助手的真正到来。

# 保持 Auto-GPT 版本更新

在持续使用过程中，需保持 Auto-GPT 始终为最新版本，否则可能会无法正常使用。

运行前在 Shell 中使用 git pull 命令拉取 Auto-GPT 仓库最新的代码版本

```
$ cd Auto-GPT
$ git pull
```

拉取结果如下：

![git_pull](https://1024-staging-1258723534.cos.ap-guangzhou.myqcloud.com/assets/git_pull.png)


# 如果你有好的Auto-GPT使用技巧和用例

欢迎在评论区留言，分享给大家。

