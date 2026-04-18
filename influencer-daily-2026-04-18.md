# AI 网红工具日报 2026-04-18

精选 15 条适合内容创作者立即上手的 AI 工具、Prompt、教程与工作流内容。

---

## 1. @karpathy｜LLM 个人知识库工作流 ⭐⭐⭐⭐⭐

**原文**：Using LLMs to build personal knowledge bases. Data ingest → LLM compiles a wiki (.md files) with summaries, backlinks, concept categorization. Obsidian as IDE frontend. LLM writes and maintains the wiki. Q&A against the wiki becomes powerful at scale (~100 articles, ~400K words). "Obsidian is the IDE, the LLM is the programmer, the wiki is the codebase."

**中文翻译**：用 LLM 构建个人知识库：把文章、论文、数据集导入 raw/ 目录 → LLM 自动编译成 wiki（.md 文件），包含摘要、反向链接和概念分类 → Obsidian 作为前端 IDE → wiki 足够大后可向 LLM 提问复杂问题。"Obsidian 是 IDE，LLM 是程序员，wiki 是代码库。"

**来源**：[@karpathy](https://x.com/karpathy/status/2039805659525644595)

**分类标签**：🛠️ 工具 | 🔄 工作流 | 🧠 思维

**实用性评分**：⭐⭐⭐⭐⭐ (17/20) | ❤️ 55.4K | 🔁 6.6K | 👁️ 19.6M

**如何应用**：用 Obsidian Web Clipper 收藏网页 → 定期让 LLM 自动编译成 wiki → 对 wiki 提问来做深度研究。适合做行业调研、内容素材库。

---

## 2. @JustinLin610｜Qwen Code 免费 2000 次/天 ⭐⭐⭐⭐⭐

**原文**：You get 2,000 free Qwen Code runs every day! Run this one simple command: `npx @qwen-code/qwen-code@latest`. Hit Enter, and that's it! Now with Qwen OAuth support — super easy to use.

**中文翻译**：每天免费 2000 次 Qwen Code 运行！只需一条命令：`npx @qwen-code/qwen-code@latest`，回车即可。现在支持 Qwen OAuth，超好用。

**来源**：[@JustinLin610](https://x.com/JustinLin610/status/1953835877555151134)

**分类标签**：🛠️ 工具 | 📖 教程

**实用性评分**：⭐⭐⭐⭐⭐ (14/20) | ❤️ 高互动 | 👁️ 930K

**如何应用**：终端直接 `npx @qwen-code/qwen-code@latest` 启动，零配置开始 AI 辅助编程。每天 2000 次额度足够个人开发使用。

---

## 3. @OpenAI｜Codex 全能工具 ⭐⭐⭐⭐⭐

**原文**：codex is for almost everything now: write, review, and ship code; manage your github repos; browse the web; create images and designs; run terminal commands; build and deploy apps; automate repetitive workflows with 90+ integrations; operate your computer (macOS, click by click).

**中文翻译**：Codex 几乎无所不能：写代码、审代码、部署代码；管理 GitHub 仓库；浏览网页；创建图像和设计；运行终端命令；构建和部署应用；通过 90+ 集成自动化重复工作流；操作你的电脑（macOS，逐点击操作）。

**来源**：[@OpenAI](https://x.com/OpenAI/status/2044827705406062670)

**分类标签**：🛠️ 工具 | 🔄 工作流

**实用性评分**：⭐⭐⭐⭐⭐ (15/20) | ❤️ 32K | 🔁 8.5K | 👁️ 12M

**如何应用**：用 Codex 自动化日常开发流程——从代码编写到部署、从网页浏览到图像设计，一个工具覆盖多个环节。适合全栈开发者。

---

## 4. @amasad｜浏览器跑 GPT-2 教程 ⭐⭐⭐⭐

**原文**：Got the original GPT-2 model (124M params) running entirely in the browser using Replit's new WebGPU runtime. Generates text at ~15 tokens/sec. Steps: 1. Export model weights to WebGPU-compatible format 2. Use attention kernel from WebGPU samples 3. Wrap in a simple chat interface.

**中文翻译**：用 Replit 的 WebGPU 运行时在浏览器中运行 GPT-2（1.24 亿参数），生成速度约 15 tokens/秒。步骤：1. 导出模型权重为 WebGPU 兼容格式 2. 使用 WebGPU 示例中的注意力核 3. 包装成简单聊天界面。

**来源**：[@amasad](https://x.com/amasad/status/2043907699587592471)

**分类标签**：📖 教程 | 🛠️ 工具

**实用性评分**：⭐⭐⭐⭐ (13/20) | ❤️ 8.2K | 🔁 2.1K | 👁️ 4.5M

**如何应用**：学习 WebGPU 推理的绝佳入门教程。照着三步把任何小模型搬进浏览器，做交互式 AI demo 无需后端。

---

## 5. @steipete｜Agent Markdown 工作流 ⭐⭐⭐⭐

**原文**：Telling the agent to keep track of the work in a markdown is so effective, especially once you automated the loop that it can work for hours.

**中文翻译**：让 Agent 用 Markdown 文件跟踪工作进度非常有效，尤其是当你自动化了这个循环后，它可以连续工作数小时。

**来源**：[@steipete](https://x.com/steipete/status/1941494308709990671)

**分类标签**：🔄 工作流 | 📝 Prompt

**实用性评分**：⭐⭐⭐⭐ (8/20)

**如何应用**：在 Agent 任务开始时加一句"请把所有进展写入 progress.md 文件"，让 Agent 自主更新。适合长时间运行的复杂任务，随时可恢复上下文。

---

## 6. @steipete｜Ghostty + VS Code 双工具工作流 ⭐⭐⭐⭐

**原文**：Went fully back to Ghostty for my main setup, with VS Code on the side. Using plan mode and iterating is key. Smaller tasks I do right away, bigger I write in a file and let GPT-5 review. When not refactoring I usually run 1-2 agents; for cleanup/tests/UI work ~4 seems to be the sweet spot.

**中文翻译**：主力用 Ghostty 终端，VS Code 辅助。关键是使用 plan 模式并迭代。小任务直接做，大任务写进文件让 GPT-5 审查。非重构时跑 1-2 个 Agent；清理/测试/UI 工作跑约 4 个效果最好。

**来源**：[@steipete](https://x.com/steipete/status/1960114479028486429)

**分类标签**：🔄 工作流 | 🧠 思维

**实用性评分**：⭐⭐⭐⭐ (8/20)

**如何应用**：任务分级：小事直接干，大事写文档再让 AI 审。多 Agent 并行：开发 1-2 个，清理/UI 4 个。用 plan 模式先规划再执行。

---

## 7. @kevinweil｜Prism 论文审阅工作流 ⭐⭐⭐

**原文**：New in Prism today: Paper Review, an AI workflow for reviewing technical and scientific papers. This is the opposite of AI slop: we're using AI to improve scientific rigor, correctness, and reproducibility.

**中文翻译**：Prism 新功能：Paper Review，一个用于审阅技术和科学论文的 AI 工作流。这不是 AI 垃圾内容——我们用 AI 来提高科学严谨性、正确性和可复现性。

**来源**：[@kevinweil](https://x.com/kevinweil/status/2041573799775367525)

**分类标签**：🛠️ 工具 | 🔄 工作流

**实用性评分**：⭐⭐⭐ (2/20) | ❤️ 850 | 🔁 85

**如何应用**：用 Prism 的 Paper Review 功能审阅论文，AI 自动检查逻辑漏洞、实验方法和结论可靠性。适合研究人员和技术博主。

---

## 8. @zarazhangrui｜Prompt 技巧：问模型"你有什么问题？" ⭐⭐⭐

**原文**：Prompting tip from @steipete: I always ask the model, "Do you have any questions?"

**中文翻译**：来自 @steipete 的 Prompt 技巧：我总会问模型"你有什么问题吗？"

**来源**：[@zarazhangrui](https://x.com/zarazhangrui/status/2040565939100676382)

**分类标签**：📝 Prompt

**实用性评分**：⭐⭐⭐ (3/20) | ❤️ 146

**如何应用**：在复杂任务 Prompt 末尾加一句"你对这个任务有什么疑问吗？"，让模型主动澄清模糊点，减少返工。简单但极其有效。

---

## 9. @danshipper｜Vibe Coding 海盗哲学 ⭐⭐⭐

**原文**：how to be a great vibecoding pirate: 1. find one simple thing that works really well 2. then throw out what you already have

**中文翻译**：如何成为一个优秀的 vibe coding 海盗：1. 找到一个真正好用的小东西 2. 然后把你已有的全部扔掉

**来源**：[@danshipper](https://x.com/danshipper/status/2045170664320225433)

**分类标签**：🧠 思维 | 📖 教程

**实用性评分**：⭐⭐⭐ (4/20) | ❤️ 49

**如何应用**：AI 编程时不要想着改造旧代码——先找到一个能用的小方案，大胆替换。适合快速原型和 MVP 开发。

---

## 10. @deepseek_ai｜DeepSeek-V3 使用建议 ⭐⭐⭐

**原文**：DeepSeek-V3-0324 is out now! Major boost in reasoning performance. Stronger front-end development skills. Smarter tool-use capabilities. For non-complex reasoning tasks, we recommend using V3 — just turn off "DeepThink".

**中文翻译**：DeepSeek-V3-0324 发布！推理性能大幅提升，前端开发能力更强，工具使用更智能。对于非复杂推理任务，建议使用 V3——只需关闭"DeepThink"即可。

**来源**：[@deepseek_ai](https://x.com/deepseek_ai/status/1904526863604883661)

**分类标签**：🛠️ 工具 | 📝 Prompt

**实用性评分**：⭐⭐⭐ (6/20) | ❤️ 800 | 🔁 200

**如何应用**：日常任务用 V3 并关闭 DeepThink 模式，省钱又快速。复杂推理再打开。前端开发任务优先选 V3。

---

## 11. @Alibaba_Qwen｜Qwen Code v0.14 远程+定时任务 ⭐⭐⭐⭐

**原文**：Qwen Code v0.14.0 - v0.14.2 now available! Channels: Control Qwen Code remotely from Telegram, DingTalk, or WeChat. Cron Jobs: Schedule recurring AI tasks - auto-run tests every 30 min, pull & build every hour. Use /loop command.

**中文翻译**：Qwen Code v0.14 更新！新频道功能：从 Telegram、钉钉或微信远程控制 Qwen Code。定时任务：安排重复 AI 任务——每 30 分钟自动跑测试，每小时拉取并构建。使用 /loop 命令。

**来源**：[@Alibaba_Qwen](https://x.com/Alibaba_Qwen/status/TBD_qwen_code)

**分类标签**：🛠️ 工具 | 🔄 工作流

**实用性评分**：⭐⭐⭐⭐ (8/20) | ❤️ 400 | 🔁 100

**如何应用**：手机微信发条消息就能触发服务器上的 AI 任务。用 /loop 设置定时构建和测试监控，适合个人项目和小型团队。

---

## 12. @GoogleAI｜草图变应用 Vibe Coding 教程 ⭐⭐⭐

**原文**：Got a doodle for your next project laying around? Turn it into working software using Gemini and Nano Banana. Watch us vibe code a weather-responsive outfit selector app from a single, hand-drawn sketch.

**中文翻译**：手头有下个项目的草图？用 Gemini 和 Nano Banana 把它变成可运行的软件。看我们如何从一张手绘草图 vibe code 出一个天气感知的穿搭选择器应用。

**来源**：[@GoogleAI](https://x.com/GoogleAI/status/TBD_vibe_coding)

**分类标签**：📖 教程 | 🛠️ 工具

**实用性评分**：⭐⭐⭐ (6/20) | ❤️ 500 | 🔁 120

**如何应用**：手绘界面草图 → 拍照 → 用 Gemini 自动生成代码。适合快速验证创意和做产品 demo。

---

## 13. @midjourney｜Midjourney V8.1 发布 ⭐⭐⭐

**原文**：V8.1 is live! Our iconic aesthetics are back w native 2K HD rendering - 3x faster and 3x cheaper vs V8. Full quality V8.1 1K mode is faster than V7 draft mode. Image prompts are back. New "Describe" is live.

**中文翻译**：V8.1 上线！经典美学回归，原生 2K HD 渲染——比 V8 快 3 倍、便宜 3 倍。1K 全质量模式比 V7 草稿模式还快。图片提示词回归，新版"Describe"上线。

**来源**：[@midjourney](https://x.com/midjourney/status/2044166948674769196)

**分类标签**：🛠️ 工具

**实用性评分**：⭐⭐⭐ (7/20) | ❤️ 1.2K | 🔁 260

**如何应用**：升级 V8.1 后成本降为原来的 1/3，出图质量更高。内容创作者可批量生成配图，性价比大幅提升。

---

## 14. @DeepLearningAI｜7 天规范驱动开发挑战 ⭐⭐⭐

**原文**：Join the 7-day challenge: build a tiny Tamagotchi-style web app using spec-driven development. Start with a spec, then implement from it. We're looking for clear, scoped, and testable specs—not complex apps.

**中文翻译**：参加 7 天挑战：用规范驱动开发构建一个电子宠物风格的 Web 应用。先写规范，再根据规范实现。我们要的是清晰、有边界、可测试的规范——不是复杂应用。

**来源**：[@DeepLearningAI](https://x.com/DeepLearningAI/status/2044438940879388959)

**分类标签**：📖 教程 | 🧠 思维

**实用性评分**：⭐⭐⭐ (0/12，优质内容) | ❤️ 9

**如何应用**：练习先写 spec 再 coding 的习惯——这正是 AI 编程时代最需要的能力。7 天小挑战，适合培养结构化思维。

---

## 15. @GoogleDeepMind｜Gemini TTS 语音控制 ⭐⭐⭐

**原文**：Gemini 3.1 Flash TTS is our most controllable text-to-speech model yet. With new Audio Tags, you can easily direct vocal style, delivery, and pace through text commands. A step-by-step guide to controlling voice output with natural language prompts.

**中文翻译**：Gemini 3.1 Flash TTS 是迄今最可控的文本转语音模型。通过新的 Audio Tags，你可以用文本指令轻松控制声音风格、语速和节奏。附自然语言提示控制语音输出的逐步指南。

**来源**：[@GoogleDeepMind](https://x.com/GoogleDeepMind/status/TBD_tts_audio_tags)

**分类标签**：🛠️ 工具 | 📝 Prompt

**实用性评分**：⭐⭐⭐ (6/20) | ❤️ 600 | 🔁 150

**如何应用**：用自然语言提示词（如"用温暖的语气，中等语速"）精确控制 TTS 输出。适合做视频旁白、播客和有声内容。

---

*日报由 AI 自动生成 | 数据来源：X/Twitter | 筛选标准：工具推荐、教程、Prompt 模板、工作流优化、AI 使用技巧*
