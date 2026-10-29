# 分享文

## 短版（社群貼文）

> 我用 AI 整理了一篇 Claude Code 團隊 code review 的繁中導讀：〈三萬次合併之後的審查〉。
>
> 重點是 Anthropic 把問題換掉了：不再問「有沒有人讀過」，改問「這個變更可能出什麼錯，哪種檢查最適合抓」。六層檢查加上快速 rollback，人的注意力只留給依風險決定的核准。
>
> 他們自述 6 到 9 月，合併進 Claude Code 的 PR 超過兩倍，需要 revert 的比例下降超過 40%。這是 Anthropic 自己的數字，沒有第三方驗證。
>
> 文中標了哪些是原文說的、哪些是導讀的判斷，另附六張原文圖的繁中重繪版。
>
> 👉 https://lushinshang.github.io/claude-code-code-review/
>
> 聲明：本導讀的分析、撰稿、查證與插圖皆由 AI 模型完成，未經人工逐句校稿。原文為 Addy Osmani 在 X 上的長文，內容改寫自 Anthropic 官方部落格，版權屬原作者。

## 長版（部落格或社群串首文）

> 九成程式碼由 Claude 寫的團隊，怎麼做 code review？
>
> 我整理了 Addy Osmani〈How the Claude Code team does code review〉的繁中導讀，並對照 Anthropic 官方部落格查證。幾個值得帶走的點：
>
> - 不再追問「有沒有人讀過」，改問「這個變更可能出什麼錯、哪種檢查最合適」。
> - 一個變更要過六層檢查，第七項是快速回饋與 rollback，接住漏網之魚。
> - 依風險決定核准：低風險不需人，一般變更一人，最高風險的路徑兩人。
> - 把 incident 與 revert 做成 eval，每天跑，用來調整 reviewer。
> - 他們自述的成績與限制，導讀都標了可信度，並區分「原文說的」與「本文判斷」。
>
> 導讀網頁：https://lushinshang.github.io/claude-code-code-review/
> 原始碼庫：https://github.com/lushinshang/claude-code-code-review
>
> 製作聲明：分析、撰稿、查證、審稿與插圖皆由 AI 模型完成，未經人工逐句校稿。圖 A 到 F 是請 AI 依原文圖重繪的繁中版，出處與版權歸原作者與 Anthropic。數字多為 Anthropic 自述，無第三方驗證。
