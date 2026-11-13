# moto

摩托车项目工作区。本仓库目前只包含工作区配置骨架，业务代码在此之上逐步添加。

## 目录约定

```
moto/
├── README.md          # 项目说明（本文件）
├── .gitignore         # 忽略规则
├── .gitattributes     # 换行与二进制处理规则
├── .editorconfig      # 编辑器统一风格
└── (后续) src/ docs/ assets/
```

## 开发约定

- 主分支为 `main`，提交前先 `git pull --rebase`。
- 提交信息使用 `<type>(<scope>): <summary>` 形式，type 取 `feat` / `fix` / `docs` / `chore` / `refactor` / `test`。
- 二进制资源（图片、音频、字体）放入 `assets/`，交由 `.gitattributes` 按二进制处理，不进文本 diff。
- 文本文件按 LF 存储；`.bat` / `.cmd` / `.ps1` 保留 CRLF。
- 密钥与本地配置走 `.env`，仓库只提交 `.env.example`。

## 起步

```bash
git clone https://github.com/guan-chengjun/moto.git
cd moto
```
