# ChatGPT Export Organizer / ChatGPT 对话导出整理工具

一个单文件、中文界面的本地工具：把 ChatGPT 官方数据导出里的 `conversations.json`
整理成可搜索、可查看、可导出 Markdown 的对话清单。

## 它不是什么

- **不是 OpenAI 官方工具**，与 OpenAI 无关，不代表、不隶属 OpenAI。
- 不登录、不联网、不上传、不需要 API Key、不收集任何数据。
- 不会自动读取你的 ChatGPT 账号；文件是你自己手动选的。

## 能做什么

- 本地读取 `conversations.json`（ChatGPT 设置 → 数据导出得到的文件）
- 按标题、按内容搜索对话
- 干净地查看一条对话的全部消息（按时间排序）
- 把任意一条对话导出为 Markdown 文件，或复制 Markdown
- 内置一条假示例对话，点“载入示例”就能先看效果

## 不能做什么

- 不能直接连你的 ChatGPT 账号拉对话
- 不能保证兼容未来 ChatGPT 导出格式的每一次改动；解析失败时请先确认文件确实是 `conversations.json`
- 示例对话是假的，仅作格式演示

## 隐私

文件只在你自己的浏览器里用 JavaScript 处理，关闭页面就没了，不会发到任何服务器。
请不要在工具里粘贴密码、密钥或其他敏感信息。

## 使用方法

1. 用浏览器打开 `index.html`
2. 选择你从 ChatGPT 导出的 `conversations.json`
3. 搜索、点开一条对话，导出或复制 Markdown

## License

MIT，见 `LICENSE`。
