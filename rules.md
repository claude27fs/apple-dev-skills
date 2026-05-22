# Apple Dev Skills 规则

## 目标
每天挖掘 GitHub 上**供 AI Agent 使用的 Skills**（MCP Server、Claude Code Skills、Agent 工具等），要求与**苹果平台开发**（iOS/macOS/watchOS/tvOS/Swift/SwiftUI 等）有相关性。

## 收录规则

1. **Stars > 50**：仅收录 Stars 数超过 50 的 skill
2. **数量**：每天挖掘 5 款流行的 skill
3. **去重**：同一 skill 不重复收录
4. **相似合并**：相似的 skill 只保留 Stars 最多的
5. **必须是 AI Agent Skill**：必须是供 AI Agent（Claude Code、Cursor、Codex、OpenClaw 等）调用的工具/Skills/MCP Server
6. **与苹果开发相关**：skill 必须与 Apple 平台开发相关（iOS/macOS/watchOS/tvOS/Swift/SwiftUI/AppKit/UIKit 等）

## Changelog 格式

每次执行后追加记录：
```
## YYYY-MM-DD

### 新收录
- [skill-name](url) - Stars: N⭐ | 平台: xxx | 描述：xxx

### 统计
- 今日新增：N
- 累计收录：N
```

## 数据来源
- GitHub Topics: `ios-development`、`mcp-server`、`claude-code-skill`、`swift`、`macos` 中与 AI Agent Skills 相关项目
- GitHub 搜索，按 Stars 排序

## 执行时间
每天 02:00 Asia/Shanghai