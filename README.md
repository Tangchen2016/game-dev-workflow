# Game Development Workflow

入口 Skill：`game-production-flow`。自包含12环节的路由、10份阶段说明和模板。

## 本地安装
需要 Node.js 22.20+。在目标项目执行：
```bash
npx skills add /解压路径/game-development-workflow-v2 --skill game-production-flow -a codex
```
全局安装加 `-g`；Claude Code 把 `-a codex` 换成 `-a claude-code`。安装过程中检查目标和同名覆盖提示。

## GitHub 安装
```bash
npx skills add Tangchen2016/game-dev-workflow --skill game-production-flow -a codex -g
```
仓库：https://github.com/Tangchen2016/game-dev-workflow 。无需发布 npm 包。

## 使用
告诉 Agent：“使用 game-production-flow，检查当前游戏，从未完成的已授权环节推进。”

## 验证 / 更新 / 移除
```bash
npx skills list
npx skills check
npx skills update
npx skills remove game-production-flow
```
全局安装的管理命令按CLI帮助添加相应全局选项。从 GitHub 安装后可检查远程更新；本地来源修改后重新安装。

## 说明
Skill说明不附带图像/浏览器/引擎工具。没有自动安装到你的Agent，也没有改动游戏。内置第三方本地快照的来源见SOURCES.json；公开发布前需核对每份上游授权，不能将整个包擅自统一声明为MIT。
