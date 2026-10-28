# 三萬次合併之後的審查

〈How the Claude Code team does code review〉（Addy Osmani，2026-10-26 X 長文；Anthropic 官方部落格 2026-10-15 原文的改寫）的繁體中文深度導讀：agent 寫了約九成程式碼之後，Claude Code 團隊怎麼分層把關、把人的時間留給哪裡，以及這些 Anthropic 自述數字該怎麼讀。

## 製作聲明
本導讀的分析、撰稿、審稿與插圖皆由 AI 模型完成，不是人類分析，未經人工逐句校稿。分工：統籌 Claude Sonnet 5.5；撰稿、事實審稿、編輯審稿、潤稿與標重點為 Claude Opus；原文圖 A–F 由 OpenAI Codex imagegen 依原圖重繪為繁中版（原圖由 Anthropic 製作，版權屬原作者）；封面為 AI 生成的概念插畫。文中數字多為 Anthropic 自述，與官方頁面互相比對，單一來源者在文中降級標示。

## 檔案
- `index.html`：導讀網頁（直接用瀏覽器開啟）
- `claude-code-code-review-addy.md`：導讀 Markdown
- `images/`：封面、圖 A–F（各 16:9 與 9:16）、og 縮圖
- 未提供全文譯本（原文受著作權保護）

## 來源
- Addy Osmani，How the Claude Code team does code review（X 長文）：https://x.com/addyosmani/status/2114604912520921136
- 官方原文：https://claude.dev/blog/solving-code-review-at-anthropic
- Code Review 產品文件：https://code.claude.com/docs/en/code-review
- Redesigning source control at Anthropic：https://www.anthropic.com/engineering/redesigning-source-control
- Claude Code best practices：https://code.claude.com/docs/en/best-practices

## 狀態
已發布（2026-10-29）：https://lushinshang.github.io/claude-code-code-review/
