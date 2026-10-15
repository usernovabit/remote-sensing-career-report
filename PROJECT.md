# 项目说明

遥感科学与技术专业（一年级）生涯认知与目标初探报告，聚焦 **GNSS / LiDAR** 方向。

## 交付物

| 文件 | 说明 |
|---|---|
| `reports/pdf/生涯认知与目标初探报告.pdf` | 报告终稿，5 页：封面（含姓名、学号）、开篇、职业方向初探、自我认知与规划、附件（匹配度表 + 思维导图） |
| `26303039梁浩然大一成长赛道.zip` | 成长赛道提交材料 |

## 仓库约定

- 提交信息格式：`docs(report): 说明`、`chore: 说明`
- 修改流程：更新 `reports/` 下的文件 → `git add` → `git commit` → `git push`
- `accelerator-ca.pem`、`*.token` 等本机文件不入库（见 `.gitignore`）

## 环境说明（本机）

- 本机通过加速器访问 GitHub，其根证书已导出为 `accelerator-ca.pem` 供 git TLS 校验使用
- git 使用 OpenSSL 后端：`git config http.sslBackend openssl`
- DSH 的 GitHub MCP 插件位于 `~/.dsh/profiles/desktop/`，启动参数含 `--use-system-ca`

## 待办

见仓库 Issues。
